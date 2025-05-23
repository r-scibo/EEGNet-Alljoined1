# EEGNet EEG-to-Image Classification
This repo contains a notebook implementing EEGNet to classify EEG responses to natural images (Alljoined1 dataset) across multiple participants.
The code is made to be run on __Colab__, training the model on their free GPUs and integrating with your personal Drive.

The __dataset__ is public on Hugging Face, you can find the original paper [here](https://arxiv.org/abs/2404.05553) and the dataset [here](https://huggingface.co/datasets/Alljoined/05_125).

Possible __next steps__ could involve:
- Re-weighting the loss to improve performance on less represented classes
- Treating the temporal‐conv kernel length (currently 64) and the number of temporal filters (16→32) as hyperparameters, and grid‐search over them.

## License
This project is released under the MIT License.
