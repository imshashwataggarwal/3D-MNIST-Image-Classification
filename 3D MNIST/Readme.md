# 3D MNIST IMAGE CLASSIFICATION

- Code + Acc + 2-3 lines
- In Results
  - ML : Table, ROC, Confusion Matrix
  - CNNs : Confusion Matrix, learning curves
- Conclusion

<br>

| Classifier                   | Accuracy (%)    |
| :-------------              | :-------------  |
| Logistic  Regression        | 58.2            |
| Decision Trees              | 48.65           |
| Linear SVM                  | 55.7            |
| K Nearest Neighbors         | 59.05           |
| Random Forests              | <strong>68.5</strong>            |



<br>
# 2D CNN

tried several but this gave best:

* accuracy : 69.8
* shape : 16 * 16 * 16

Epoch 1/30
3s - loss: 2.0299 - acc: 0.2922 - val_loss: 2.2644 - val_acc: 0.1960
Epoch 2/30
3s - loss: 1.4517 - acc: 0.4913 - val_loss: 2.0336 - val_acc: 0.4440
Epoch 3/30
3s - loss: 1.3081 - acc: 0.5364 - val_loss: 1.6669 - val_acc: 0.5140
Epoch 4/30
3s - loss: 1.2385 - acc: 0.5595 - val_loss: 1.4951 - val_acc: 0.5667
Epoch 5/30
3s - loss: 1.1959 - acc: 0.5799 - val_loss: 1.2812 - val_acc: 0.5813
Epoch 6/30
3s - loss: 1.1682 - acc: 0.5826 - val_loss: 1.1254 - val_acc: 0.6053
Epoch 7/30
3s - loss: 1.1552 - acc: 0.5909 - val_loss: 1.0595 - val_acc: 0.6240
Epoch 8/30
3s - loss: 1.1247 - acc: 0.6008 - val_loss: 0.9993 - val_acc: 0.6460
Epoch 9/30
3s - loss: 1.0981 - acc: 0.6142 - val_loss: 0.9978 - val_acc: 0.6313
Epoch 10/30
3s - loss: 1.0928 - acc: 0.6103 - val_loss: 0.9892 - val_acc: 0.6527
Epoch 11/30
3s - loss: 1.0770 - acc: 0.6202 - val_loss: 0.9940 - val_acc: 0.6387
Epoch 12/30
3s - loss: 1.0627 - acc: 0.6215 - val_loss: 0.9916 - val_acc: 0.6573
Epoch 13/30
3s - loss: 1.0704 - acc: 0.6239 - val_loss: 1.0423 - val_acc: 0.6400
Epoch 14/30
3s - loss: 1.0524 - acc: 0.6296 - val_loss: 0.9560 - val_acc: 0.6573
Epoch 15/30
3s - loss: 1.0331 - acc: 0.6320 - val_loss: 0.9504 - val_acc: 0.6540
Epoch 16/30
3s - loss: 1.0215 - acc: 0.6353 - val_loss: 0.9428 - val_acc: 0.6800
Epoch 17/30
3s - loss: 1.0052 - acc: 0.6461 - val_loss: 0.9492 - val_acc: 0.6633
Epoch 18/30
3s - loss: 1.0090 - acc: 0.6389 - val_loss: 0.9468 - val_acc: 0.6693
Epoch 19/30
3s - loss: 0.9957 - acc: 0.6520 - val_loss: 0.9322 - val_acc: 0.6700
Epoch 20/30

Epoch 00019: reducing learning rate to 0.000500000023749.
3s - loss: 0.9831 - acc: 0.6507 - val_loss: 0.9482 - val_acc: 0.6653
Epoch 21/30
3s - loss: 0.9643 - acc: 0.6636 - val_loss: 0.8976 - val_acc: 0.6767
Epoch 22/30
3s - loss: 0.9341 - acc: 0.6679 - val_loss: 0.8920 - val_acc: 0.6873
Epoch 23/30
3s - loss: 0.9078 - acc: 0.6785 - val_loss: 0.8755 - val_acc: 0.6933
Epoch 24/30
3s - loss: 0.9386 - acc: 0.6650 - val_loss: 0.8968 - val_acc: 0.6840
Epoch 25/30
3s - loss: 0.9130 - acc: 0.6792 - val_loss: 0.8872 - val_acc: 0.6900
Epoch 26/30
3s - loss: 0.8946 - acc: 0.6765 - val_loss: 0.8736 - val_acc: 0.6960
Epoch 27/30
3s - loss: 0.8997 - acc: 0.6785 - val_loss: 0.8668 - val_acc: 0.7060
Epoch 28/30
3s - loss: 0.8802 - acc: 0.6879 - val_loss: 0.8859 - val_acc: 0.6853
Epoch 29/30
3s - loss: 0.8877 - acc: 0.6890 - val_loss: 0.8732 - val_acc: 0.6967
Epoch 30/30
3s - loss: 0.8832 - acc: 0.6858 - val_loss: 0.8768 - val_acc: 0.6913
0.698
Model Saved.

# 3D CNN

* accuracy : 77.1%
* shape : 16 * 16 * 16 * 3

Epoch 1/30
11s - loss: 2.1194 - acc: 0.2912 - val_loss: 2.1434 - val_acc: 0.1660
Epoch 2/30
10s - loss: 1.3554 - acc: 0.5274 - val_loss: 1.8831 - val_acc: 0.4933
Epoch 3/30
10s - loss: 1.1520 - acc: 0.5954 - val_loss: 2.0278 - val_acc: 0.3427
Epoch 4/30
10s - loss: 1.0604 - acc: 0.6272 - val_loss: 1.3859 - val_acc: 0.5500
Epoch 5/30
10s - loss: 0.9991 - acc: 0.6448 - val_loss: 1.2405 - val_acc: 0.6000
Epoch 6/30
10s - loss: 0.9305 - acc: 0.6756 - val_loss: 1.0759 - val_acc: 0.6113
Epoch 7/30
10s - loss: 0.8790 - acc: 0.6939 - val_loss: 1.0644 - val_acc: 0.6673
Epoch 8/30
10s - loss: 0.8295 - acc: 0.7087 - val_loss: 0.8908 - val_acc: 0.6920
Epoch 9/30
10s - loss: 0.7648 - acc: 0.7289 - val_loss: 0.9673 - val_acc: 0.6940
Epoch 10/30
10s - loss: 0.7001 - acc: 0.7542 - val_loss: 0.8410 - val_acc: 0.7047
Epoch 11/30
10s - loss: 0.6485 - acc: 0.7719 - val_loss: 0.8781 - val_acc: 0.7133
Epoch 12/30
10s - loss: 0.5999 - acc: 0.7912 - val_loss: 0.8172 - val_acc: 0.7180
Epoch 13/30
10s - loss: 0.5375 - acc: 0.8147 - val_loss: 0.8366 - val_acc: 0.7207
Epoch 14/30
10s - loss: 0.4936 - acc: 0.8284 - val_loss: 0.8288 - val_acc: 0.7193
Epoch 15/30
10s - loss: 0.4337 - acc: 0.8494 - val_loss: 0.8528 - val_acc: 0.7320
Epoch 16/30
10s - loss: 0.4099 - acc: 0.8593 - val_loss: 1.0491 - val_acc: 0.6907
Epoch 17/30
10s - loss: 0.3601 - acc: 0.8764 - val_loss: 0.9005 - val_acc: 0.7333
Epoch 18/30
10s - loss: 0.3492 - acc: 0.8838 - val_loss: 0.9155 - val_acc: 0.7060
Epoch 19/30
10s - loss: 0.2939 - acc: 0.9000 - val_loss: 1.2862 - val_acc: 0.7007
Epoch 20/30
10s - loss: 0.2837 - acc: 0.9058 - val_loss: 0.9119 - val_acc: 0.7093
Epoch 21/30

Epoch 00020: reducing learning rate to 0.000500000023749.
10s - loss: 0.2786 - acc: 0.9104 - val_loss: 0.9305 - val_acc: 0.7287
Epoch 22/30
10s - loss: 0.1521 - acc: 0.9508 - val_loss: 1.0142 - val_acc: 0.7473
Epoch 23/30
10s - loss: 0.0944 - acc: 0.9699 - val_loss: 1.0704 - val_acc: 0.7300
Epoch 24/30
10s - loss: 0.0831 - acc: 0.9746 - val_loss: 1.1331 - val_acc: 0.7407
Epoch 25/30
10s - loss: 0.0691 - acc: 0.9773 - val_loss: 1.1615 - val_acc: 0.7393
Epoch 26/30

Epoch 00025: reducing learning rate to 0.000250000011874.
10s - loss: 0.0665 - acc: 0.9785 - val_loss: 1.1331 - val_acc: 0.7340
Epoch 27/30
10s - loss: 0.0468 - acc: 0.9856 - val_loss: 1.1230 - val_acc: 0.7367
Epoch 28/30
10s - loss: 0.0347 - acc: 0.9888 - val_loss: 1.1312 - val_acc: 0.7460
Epoch 29/30

Epoch 00028: reducing learning rate to 0.000125000005937.
10s - loss: 0.0283 - acc: 0.9919 - val_loss: 1.1361 - val_acc: 0.7340
Epoch 30/30
10s - loss: 0.0285 - acc: 0.9906 - val_loss: 1.1466 - val_acc: 0.7327
0.771
Model Saved.
