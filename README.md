# Ddos-traffic-classification
We have used a FNN based learning model for classifying whether traffic is regular or ddos traffic<br>
About the Dataset:<br>
The  dataset has aldready been attatched.
we have used several parameters for the classification of the labels:<br>
1.switch<br>	2.src<br>	3.dst<br>	4.pktcount<br>	5.bytecount<br>	6.dur<br>	7.dur_nsec<br>	8.tot_dur<br>	9.flows<br>	10.packetins<br>	11.pktperflow<br>	12.byteperflow<br>	13.pktrate<br>	14.Pairflow<br>	15.Protocol<br>	16.port_no<br>	17.tx_bytes<br>	18.rx_bytes<br>	19.tx_kbps<br>	20.rx_kbps<br>	21.tot_kbps<br>
# About the Layers and parameters:<br>
1. Input Layer:
Type: Dense Layer
Units: 64
Activation Function: Rectified Linear Unit (ReLU)<br>
2. Hidden Layer 1:
Type: Dense Layer
Units: 32
Activation Function: Rectified Linear Unit (ReLU)<br>
3. Output Layer:
Type: Dense Layer
Units: 1
Activation Function: Sigmoid
Output Dimension: 1 (binary classification, as indicated by the activation function)<br>
4. Compilation Parameters:
Optimizer: Adam
Loss Function: Binary Crossentropy
Metrics: Accuracy<br>
5. Training Parameters:
Epochs: 10
Batch Size: 32
Validation Split: 0.1 (10% of the training data used for validation during training)
Verbose: 1<br>
# Results
We got an accuracy of 99.5% and a F1 score of 99.3%
![Screenshot 2024-01-01 150759](https://github.com/Tamogh123/Ddos-traffic-classification/assets/91934369/e1c37750-fa80-42fe-9866-282fea454189)
