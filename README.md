### This repo contains the tensorflow implementation of the paper "[Question Answering on Knowledge Bases and Text using Universal Schema and Memory Networks](https://arxiv.org/abs/1704.08384)".

### Notes

(naetherm) Made small modifications so it's possible to use the newest TensorFlow version (currently version 1.2.0) when training.

### Dependencies
* TensorFlow 1.2.0

## Training
I have set up training with most default params on a very small dataset so that it is easier to get started. Just running the script should work.
```
/bin/bash run.sh ./config.sh
```
### Data
The processed data (train/dev/test split) is stored in data_formatted/ directory.
To download the KB files used for the project run,
```
sh get_data.sh
```
After downloading the data, you will have to change the appropriate entries in the config.sh file (kb_file and text_kb_file).


### Model outputs
We are also releasing the output predictions of our model for comparison. Find them in the model_outputs directory.

### Trained Model
We are also sharing our pretrained model. Get it [here]( http://iesl.cs.umass.edu/downloads/spades/max_dev_out.ckpt)

