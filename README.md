# DoS-Classification-Using-Deep-Learning

A Denial-of-Service (DoS) attack is an attack meant to shut down a machine or network, making it inaccessible to its intended users. DoS attacks accomplish this by flooding the target with traffic, or sending it information that triggers a crash. In both instances, the DoS attack deprives legitimate users (i.e. employees, members, or account holders) of the service or resource they expected.

Victims of DoS attacks often target web servers of high-profile organizations such as banking, commerce, and media companies, or government and trade organizations. Though DoS attacks do not typically result in the theft or loss of significant information or other assets, they can cost the victim a great deal of time and money to handle.

## Dataset

The dataset used is the <a href="http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html">DDOS Attack Network Logs from Kaggle</a>. The dataset contains around 2,100,000 labelled network logs from various types of network attacks. The types of network attacks logged are:

1. UDP-Flood 

2. Smurf 

3. SIDDOS 

4. HTTP-FLOOD 

5. Normal 

## Models

#### CNN

The network architecture used was a basic CNN model, with Max Pooling, Dropout and ReLU Activation functions. Input is preprocessed for optimal calculation and then fed into the Convolutional layer. 

#### LSTM

The network architecture used was a basic LSTM model, with Dropout Layer. Input is preprocessed for optimal calculation and then fed into the layer. 

#### CNN-LSTM

The network architecture used was a basic CNN-LSTM model, with Max Pooling and ReLU Activation functions. Input is preprocessed for optimal calculation and then fed into the LSTM layer. 

#### DNN

The network architecture used was a basic DNN model, with Dropout Layer. Input is preprocessed for optimal calculation and then fed into the Neural Network. 
