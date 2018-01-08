# A Tensorflow implementation of Capsule networks

## Requirements
  * NumPy >= 1.11.1
  * TensorFlow >= 1.4 (Probably 1.3 should work, too, though I didn't test it)
  * numpy
  * pillow
  * scipy

## Capsule network
I tried to implement the idea in [Dynamic Routing Between Capsules](https://arxiv.org/abs/1710.09829)
<img src="figure/capsNet.png">

## File description
  * `config.py` includes all hyper parameters that are needed.
  * `utils.py` contains functions regarding loading and saving.
  * `model.py` has all building blocks for capsNet and whole model implementation.
  * `train.py` has the model.
  * `eval.py` is for evaluation.

## Results
<img src="figure/total_loss.png" style="width: 200px;">
<img src="figure/margin_loss.png" style="width: 200px;">
<img src="figure/reconstruction_loss.png" style="width: 200px;">