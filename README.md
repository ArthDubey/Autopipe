# Automatic pipeline for Making your own Texture classifier
High paced high accuracy DIY Texture classifier
# Aim

This Project aims to build an image classifier that is extremely convenient to personalise and to train your own data in 3 simple steps. Accuracy is substaintially high for all regular purposes.

## Background
Visual classification for quality assurance and other purposes in the mechanical field has been game-changing. Inspired by the recent success of Convolutional neural networks in estimating the life of cutting tools, This project has tried to automate the process of texture classification for mechanical tools with CNN’s.
## Getting Started

Clone the repository in your system and follow these steps-
1. Check if the requirements are satisfied.

2. Make 4 new folders named classif1, classif2, test1 and test2. Run the script trainer.py

3. Read the steps carefully which will be displayed in the command prompt.

4. Press 1 and enter and you'll get window pop-up with webcam stream, here you have to show the perfect part and make sure it fills the black boundation box and click pictures by pressing spacebar. 20-30 is a good limit.

5. Press Esc and then your start with imperfect parts and click again 20-30 images.

6. Again press Esc and and click 4-5 pictures of perfect part (For cross validation) and again Esc and 4-5 of imperfect parts.

7. Press Esc and that program will terminate. Now your dataset is ready to be trained.

9. Run the script Neuralclsf.py and enjoy while it trains.

10. Now run Model.py and another window will pop up, Now you can show either the perfect or the imperfect and the software will determine is it perfect or not.

11. Enjoy your results.


### Prerequisites

1.SciPy 

2.Numpy 

3.Imageio 

4.Open-cv

5.Tenserflow

Note- All of these can be easily installed via pip

```
pip install scipy
pip install numpy
```

### Installing

Clone the repository in your system and follow these steps-
1. Follow getting started.

## Approach
An intuitive program is developed for anyone to train their personalized data and use the model for classification. This has vast applications in quality assurance, inventory classification, and other similar purposes. The network chosen for the system is tested for its versatility to work with a plethora of textures by means of images. The pipeline was built within mind to put minimal effort on the side of the user. Although the system itself is quite flexible so it is easy for an experienced person to change even the hyperparameters according to his/her liking. It has 3 modules, Data feed, Training, and usage. Data feed automates the data input by just a click of a button. The network is a 2D CNN which saves the defining features of the perfect and imperfect model. Usage is also simply accomplished by running a program.
## Running the tests

It is explained in Getting started subsection.

## Conclusion
The network employed is highly versatile and has great accuracy for most general purposes.
## Contributing

Janhavi Subedarpage


## Authors

* **Arth Dubey** 
