# Human-Activity-Recognition
Recognizing human activities based on sensor data 

We have 2 datasets: the first one recording the sensor data (binary type - on/off) with timestamps and the other is the corresponding activities at that time. 

The idea is to use a Hidden Markov Model on these training data in order to recognize human activities in the future sensor data. 

In the first time we will find the parameters of our Hidden Markov Model using frequency counting method. 

Next we will use Viterbi algorithm to find the most probable sequence of activities that matchs the sequence of sensor data.

The idea and dataset are based on the article “Accurate Activity Recognition in a Home Setting” of Tim van Kasteren, Athanasios Noulas, Gwenn Englebienne and Ben Krose.

We also tried 2 other approaches: one used k-Near Neighbors algorithm and one used Artificial Neural Network. 

The error rate is approximately 20%. 

