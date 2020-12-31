# FBLDNET for Denoising
This code is modified by https://github.com/cszn/KAIR
Datasets:
-----------
- [set12](https://github.com/cszn/FFDNet/tree/master/testsets)
- [bsd68](https://github.com/cszn/FFDNet/tree/master/testsets)
- [cbsd68](https://github.com/cszn/FFDNet/tree/master/testsets)
- set5
- set14
- cbsd100

Train
----------
run main_train_fbldnet.py

Testing
----------
run main_test_fbldnet.py

Directory structure
----------
- model_zoo (pretrained model)
- options (some sets)
- models (network, train method definition)
- testsets
- trainsets
- utils
