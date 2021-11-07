# LSTM-and-Bidirectional-LSTM-NLP
<h1> LSTM </h1>
An LSTM has a similar control flow as a recurrent neural network. It processes data passing on information as it propagates forward. The differences are the operations within the LSTM’s cells.</br>
The core concept of LSTM’s are the cell state, and it’s various gates. The cell state act as a transport highway that transfers relative information all the way down the sequence chain. You can think of it as the “memory” of the network. The cell state, in theory, can carry relevant information throughout the processing of the sequence. So even information from the earlier time steps can make it’s way to later time steps, reducing the effects of short-term memory. As the cell state goes on its journey, information get’s added or removed to the cell state via gates. The gates are different neural networks that decide which information is allowed on the cell state. The gates can learn what information is relevant to keep or forget during training.</br>
![image](https://user-images.githubusercontent.com/67821036/140633386-d18a4886-216a-4356-beea-633f3bff3c8e.png)
<h1>Bidirecitonal LSTM </h1>
A Bidirectional LSTM, or biLSTM, is a sequence processing model that consists of two LSTMs: one taking the input in a forward direction, and the other in a backwards direction.
![image](https://user-images.githubusercontent.com/67821036/140633439-4e9bbba9-879c-41e2-b498-43ada3148d6c.png)
