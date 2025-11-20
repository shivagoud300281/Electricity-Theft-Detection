# Electricity-Theft-Detection
As one of the major factors of the non-technical losses (NTLs) in distribution networks, the 
electricity theft causes significant harm to power grids, which influences power supply quality 
and reduces operating profits. In order to help utility companies solve the problems of 
inefficient electricity inspection and irregular power consumption, a novel hybrid 
convolutional neural network-random forest (CNN-RF) model for automatic electricity theft 
detection is presented in this paper. In this model, a convolutional neural network (CNN) firstly 
is designed to learn the features between different hours of the day and different days from 
massive and varying smart meter data by the operations of convolution and down sampling. In 
addition, a dropout layer is added to retard the risk of overfitting, and the backpropagation 
algorithm is applied to update network parameters in the training phase. And then, the random 
forest (RF) is trained based on the obtained features to detect whether the consumer steals 
electricity. To build the RF in the hybrid model, the grid search algorithm is adopted to 
determine optimal parameters. Finally, experiments are conducted based on real energy 
consumption data, and the results show that the proposed detection model outperforms other 
methods in terms of accuracy and efficiency
