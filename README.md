# Homework 2 Part 2

Repository for Homework 2 Part 2 for the IDL course at CMU.

## Run

Run the following command:

```bash
python3 driver.py
```

## Hyperparameters

I tuned the number/size of layers, number of BatchNorm layers, learning rate, data augmentation, kernel_size, and learning rate scheduling. I ran five epochs to get the reported test accuracy.

I settled on reduce on plateau scheduler.

## 

I used the SGD optimizer with cross-entropy loss and a learning rate of .01 with reduce on plateau scheduling.

## Results

The model achieves an accuracy of 91.636% on the verification task and 75.333% on the classification task. 

# vlr-hw1
