
<div align="center">    
 
# Handwritten Text Recognizer Project

<!-- ![CI testing](https://github.com/PyTorchLightning/deep-learning-project-template/workflows/CI%20testing/badge.svg?branch=master&event=push) -->


<!--  
Conference   
-->   
</div>
 
## Description   
The main goal of the project is to develop an end to end deep learning system which understands the contents of handwritten paragraphs.  
- We will be using modern stack of PyTorch and PyTorch-Lightening

## How to run
This project requires `conda` for setting up the working environment.

First, install dependencies
```bash
# clone project
git clone https://github.com/gauravtanwar03/handwritten-text-recognizer-project.git

cd handwritten-text-recognizer-project
make conda-update
conda activate text-recognizer
make pip-tools
```
**Note:** add `export PYTHONPATH=.:$PYTHONPATH` to your `~/.bashrc` and run `source ~/.bashrc`

<!-- 
## How to run   
First, install dependencies   
```bash
# clone project   
git clone https://github.com/YourGithubName/deep-learning-project-template

# install project   
cd deep-learning-project-template 
pip install -e .   
pip install -r requirements.txt
 ```   
 Next, navigate to any file and run it.   
 ```bash
# module folder
cd project

# run module (example: mnist as your main contribution)   
python lit_classifier_main.py    
```

## Imports
This project is setup as a package which means you can now easily import any file into any other file like so:
```python
from project.datasets.mnist import mnist
from project.lit_classifier_main import LitClassifier
from pytorch_lightning import Trainer

# model
model = LitClassifier()

# data
train, val, test = mnist()

# train
trainer = Trainer()
trainer.fit(model, train, val)

# test using the best model!
trainer.test(test_dataloaders=test)
```

### Citation   
```
@article{YourName,
  title={Your Title},
  author={Your team},
  journal={Location},
  year={Year}
}
```    -->