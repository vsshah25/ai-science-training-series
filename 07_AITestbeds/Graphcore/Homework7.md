#Homework 7

I choose Graphcore system to do this homework.

Attaching a screenshot of the MNIST example run on Graphcore.

![MNIST Run on Graphcore](mnist_run.png)

Here we change the learning rate, number of epochs, and batch size to compare the accuracy of the model on testing data.

This can be achieved by changing the arguments passed while running the script ( --lr  --epochs  --batch-size )
1) Keeping a high learning rate (0.1)  caused the model to perform very poorly while keeping a low rate (0.001) caused a slight decrease in accuracy
2) Increasing the batch size to 32 didn't cause any significant changes however reducing the batch size to 2 caused decreased accuracy
3) Reducing epochs to a very small number causes the training to terminate early and have less accuracy while allowing for a high number of epochs leads to overtraining which in turn decreases accuracy.
