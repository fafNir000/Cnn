# CNN: using ResNet-18 for CIFAR10

## Dataset

CIFAR10 from Kaggle (you need to use kaggle.json)

https://www.kaggle.com/competitions/cifar-10/data

Train samples :: 40000
Validation samples :: 10000
Test samples :: 10000
------------------------------------
Number of classes :: 10
Classes list ::
0 :։ class airplane
1 :։ class automobile
2 :։ class bird
3 :։ class cat
4 :։ class deer
5 :։ class dog
6 :։ class frog
7 :։ class horse
8 :։ class ship
9 :։ class truck
Image shape :: torch.Size([3, 224, 224])

## Training

Epoch 1/20 | Train Loss: 0.38257748110294343 | Val Loss: 0.28130189849028164 | Train Acc: 87.0275% | Val Acc: 90.56%
Epoch 2/20 | Train Loss: 0.16778055662214755 | Val Loss: 0.267130241794571 | Train Acc: 94.265% | Val Acc: 91.39%
Epoch 3/20 | Train Loss: 0.09646564785912633 | Val Loss: 0.23070018038533296 | Train Acc: 96.75% | Val Acc: 92.45%
Epoch 4/20 | Train Loss: 0.053026657899469136 | Val Loss: 0.26756242934353414 | Train Acc: 98.195% | Val Acc: 92.08%
Epoch 5/20 | Train Loss: 0.05085548303732648 | Val Loss: 0.2276150272643063 | Train Acc: 98.245% | Val Acc: 93.62%
Epoch 6/20 | Train Loss: 0.03662286792248488 | Val Loss: 0.2265796389691769 | Train Acc: 98.7875% | Val Acc: 93.54%
Epoch 7/20 | Train Loss: 0.03288628131868318 | Val Loss: 0.21493966795821454 | Train Acc: 98.88% | Val Acc: 94.0%
Epoch 8/20 | Train Loss: 0.025959080425277354 | Val Loss: 0.2838453192732469 | Train Acc: 99.105% | Val Acc: 91.95%
Epoch 9/20 | Train Loss: 0.02617649076730013 | Val Loss: 0.24446916065303384 | Train Acc: 99.1375% | Val Acc: 93.25%
Epoch 10/20 | Train Loss: 0.027058850514143706 | Val Loss: 0.24447723810270333 | Train Acc: 99.1275% | Val Acc: 93.21%
Epoch 11/20 | Train Loss: 0.009164124797889963 | Val Loss: 0.17820290973481195 | Train Acc: 99.7675% | Val Acc: 94.85%
Epoch 12/20 | Train Loss: 0.003114393394161016 | Val Loss: 0.17042521403355013 | Train Acc: 99.96% | Val Acc: 95.11%
Epoch 13/20 | Train Loss: 0.002160869549331255 | Val Loss: 0.16669811390097117 | Train Acc: 99.9825% | Val Acc: 95.32%
Epoch 14/20 | Train Loss: 0.0017889764347113668 | Val Loss: 0.16617257862609877 | Train Acc: 99.9875% | Val Acc: 95.22%
Epoch 15/20 | Train Loss: 0.001530671297176741 | Val Loss: 0.16690344186306924 | Train Acc: 99.9975% | Val Acc: 95.12%
Epoch 16/20 | Train Loss: 0.001367926143715158 | Val Loss: 0.1632376883422161 | Train Acc: 99.9975% | Val Acc: 95.32%
Epoch 17/20 | Train Loss: 0.001224939586338587 | Val Loss: 0.1622232857996681 | Train Acc: 100.0% | Val Acc: 95.35%
Epoch 18/20 | Train Loss: 0.0011371412057662382 | Val Loss: 0.16168064818269673 | Train Acc: 100.0% | Val Acc: 95.42%
Epoch 19/20 | Train Loss: 0.0011307630841387436 | Val Loss: 0.15931339462800842 | Train Acc: 100.0% | Val Acc: 95.36%
Epoch 20/20 | Train Loss: 0.0010843007104936987 | Val Loss: 0.16004624196393474 | Train Acc: 100.0% | Val Acc: 95.36%

## Metrics

Final Test Accuracy: 95.34

<img width="500" height="369" alt="image" src="https://github.com/user-attachments/assets/fd6d625b-2430-4341-af76-12d9b288533c" />
<img width="489" height="371" alt="image" src="https://github.com/user-attachments/assets/120d33e3-2038-4fdd-a864-43acab14e6bc" />
<img width="756" height="681" alt="image" src="https://github.com/user-attachments/assets/3a219d4c-793e-4cd3-8440-16b5b0205086" />

              precision    recall  f1-score   support

           0       0.96      0.97      0.96      1000
           1       0.97      0.98      0.97      1000
           2       0.96      0.93      0.95      1000
           3       0.89      0.88      0.89      1000
           4       0.96      0.97      0.96      1000
           5       0.92      0.92      0.92      1000
           6       0.96      0.98      0.97      1000
           7       0.97      0.96      0.97      1000
           8       0.97      0.97      0.97      1000
           9       0.97      0.96      0.97      1000

    accuracy                           0.95     10000
    macro avg       0.95      0.95      0.95     10000
    weighted avg       0.95      0.95      0.95     10000

## Inference

<img width="296" height="333" alt="image" src="https://github.com/user-attachments/assets/fca303ff-00df-4eca-a1ee-39c5a7a463bc" />


## Best Weights

[https://drive.google.com/file/d/1Ep1ufOWpEYx65Lk1e3Xso7b1_6oaNQvM/view?usp=sharing](https://drive.google.com/file/d/1dwdqXi59KYn_-jWzC8U2i79iZUjd0AlC/view?usp=drive_link)
