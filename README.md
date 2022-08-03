# Modulation-Recognition
Exploring a dataset of modulated radio signals using deep learning with Keras.
## Dataset Description
This dataset consists of radio signals modulated using different modulation techniques and different signal to noise ratios. The task was to try different neural network architectures to classify the signals based on the modulation technique that is used. The performance of the networks was compared accross all signal to noise ratios. The best average accuracy on the test data was 62% which is high compared to the results achieved by the paper Deep learning for modulation recognition which worked with the same dataset.
## Approach
Three different architectures where tried a plain fully connected network, a plain CNN, RNN and RNN with LSTM. The highest accuracy was obtained using the CNN approach.
