---
title: 'Assignment 8: Project'
author: 'Mr. Berg'
geometry: margin=1in
urlcolor: cyan
---

# Neural Net Project

In this project, you will get the opportunity to make a more complex neural network than what we did in Assignment 8. You will be able to work in groups of 4 or fewer. You can create the group in github classroom when you are cloning the initial repository.

The goal of this project if for you to run through the neural net on your own dataset (or one that you have found online).  You can find your dataset on UCI Machine Learning Repository or Kaggle or anywhere else.  Your error may be much larger than what we have done in class, which isn't great, but not the point of this project.  We would like you to try to do what was done in class on your own, and get some output, but if the error is too high you will not be docked points.

You can follow this process to complete your project, but feel free to try to work through your own process as well:
f you need help with the strategy on how to preprocess your data choice, let me know and I will help you as best as I can.  The basic strategy that I used was:
1. Import your dataset into this directory
2. Create a file to run through the program, give it a meaningful name
3. Bring in the imports and functions `parse_line` and `normalize` to your file
4. Alter `parse_line` to work for your dataset
* If you have classifications, you will have to number them in some way
3. Print out each line after it has run through `parse_line` to make sure the output is the way that you think it should be
4. Normalize the data using the `normalize` function
5. Print out each line to see if it is printing out correctly
6. Create your `NeuralNet`
7. `train_test_split` your data if possible
8. Train on your training data
9. Test on your testing data
10. Can you come up with a way to see how accurate your model was?
* Print that model to the screen

When finished, make sure that your project is pushed to github.  I will be cloning all of your repositories in order to grade the project and I will post that grade i google classroom.
