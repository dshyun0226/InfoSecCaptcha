# Captcha Breaker!
Tensorflow-based captcha breaker<br><br>
This project highly referenced the JackonYang's captcha classifier at https://github.com/JackonYang/captcha-tensorflow

## How to use

### Training
<br>

#### Before run
For train,
put the training images at images/train/
and put the testing images at images/test/
And modify the images/meta.json file according to the images you use.

#### Run
run "python cnn_n_char.py --data_dir images/"

<br><br>

### Testing (After training, with the model files created at training step)
<br>

#### Before run
put the testing images at images/test/
And modify the images/meta.json file according to the images you use.

#### Run
run "python load_test.py --data_dir images/"

