# CNN: using ResNet-18 for CIFAR10

## Dataset

CIFAR10 from Kaggle (you need to use kaggle.json)

https://www.kaggle.com/competitions/cifar-10/data

Train samples :: 40000

Validation samples :: 10000

Test samples :: 10000

Number of classes :: 10

Classes list

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

| Epoch | Train Loss | Val Loss | Train Acc | Val Acc |
| :---: | :---: | :---: | :---: | :---: |
| 1/20 | 0.3826 | 0.2813 | 87.03% | 90.56% |
| 2/20 | 0.1678 | 0.2671 | 94.27% | 91.39% |
| 3/20 | 0.0965 | 0.2307 | 96.75% | 92.45% |
| 4/20 | 0.0530 | 0.2676 | 98.20% | 92.08% |
| 5/20 | 0.0509 | 0.2276 | 98.25% | 93.62% |
| 6/20 | 0.0366 | 0.2266 | 98.79% | 93.54% |
| 7/20 | 0.0329 | 0.2149 | 98.88% | 94.00% |
| 8/20 | 0.0260 | 0.2838 | 99.11% | 91.95% |
| 9/20 | 0.0262 | 0.2445 | 99.14% | 93.25% |
| 10/20 | 0.0271 | 0.2445 | 99.13% | 93.21% |
| 11/20 | 0.0092 | 0.1782 | 99.77% | 94.85% |
| 12/20 | 0.0031 | 0.1704 | 99.96% | 95.11% |
| 13/20 | 0.0022 | 0.1667 | 99.98% | 95.32% |
| 14/20 | 0.0018 | 0.1662 | 99.99% | 95.22% |
| 15/20 | 0.0015 | 0.1669 | 100.0% | 95.12% |
| 16/20 | 0.0014 | 0.1632 | 100.0% | 95.32% |
| 17/20 | 0.0012 | 0.1622 | 100.0% | 95.35% |
| 18/20 | 0.0011 | 0.1617 | 100.0% | 95.42% |
| 19/20 | 0.0011 | 0.1593 | 100.0% | 95.36% |
| 20/20 | 0.0011 | 0.1600 | 100.0% | 95.36% |

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
