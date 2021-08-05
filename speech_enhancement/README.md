# Speech enhancement
On this page, you will find examples related to the speech enhancement task
  (the speech of one speaker in a noisy environment is enhanced).
The model ([DPTNet](https://arxiv.org/pdf/2007.13975.pdf)) was trained on [LibriMix](https://arxiv.org/pdf/2005.11262.pdf) with 16Khz data.
  
We randomly selected unseen data from the  [LibriMix](https://arxiv.org/pdf/2005.11262.pdf) dataset and processed it by the network to create examples.

    
Each example is composed of :
* `The mixture` The original wav file that will be fed to the network. This mixture is a clean utterance mixed
 with noise.
* `The source` The clean utterance.
* `The estimate` The output of the network.
