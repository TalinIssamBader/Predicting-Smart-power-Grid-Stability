
# Abstract
```
The stability of any system in the power grid is very important, and the concern is due to the high 
demand and supply of smart cities, homes, factories, and so on. The stability appears in: 

1- Provide sufficient capacity for voltage stability at every portion of the grid.
2- Smart grid also motivates the use of renewable energy resources rather than nonrenewable 
ones [4].
3- Generation has to match the demand at any time for immediate outages.
4- Smart grids can be used to enhance the smooth functioning of every domain like electricity 
generation either from renewable or nonrenewable energy resources [3].

Which is by dynamically estimating grid stability becomes not only a concern but a major 
requirement. Decentral Smart Grid Control (DSGC) systems monitor one particular property of 
the grid—its frequency. The user can change the consumption by the perception of the price of 
the consumption.so the DSGC is mainly collecting the data such as consumer demand.
After collect consumption data the information will sent to center to evaluate against current 
supply conditions, after that the system will predict the price information then sent back to 
consumers to change their usage depending on the cost. Finally the DSGC depend on time to 
keep grid stable.
So to deal with the stability prediction problem in the smart energy grids that will be by using 
different prediction models in artificial intelligence (AI) in Different machine learning (ML) and 
deep learning (DL).
The accuracy will show how the model learns well, by using metrics accuracy measures.
This project will use the deep learning predictive model ANN optimized with Adam optimizer 
provides better results than other predictive models.
Finally, provide the network administrator with all required information about the current 
network power balance, so that it can price its energy offering—and inform consumers—
accordingly.
```
![image](https://user-images.githubusercontent.com/123263600/215717427-ac7220b2-a57d-472c-9e40-e62f59a80819.png)

# The differences between a traditional power grid and a smart grid
![image](https://user-images.githubusercontent.com/123263600/215716068-c9290a2b-80a7-477f-bd58-2135cd47a0f4.png)


# Dataset
```
The dataset contains 14 columns, divided in 12 primary predictive features (Columns), and 2 
dependent variables, 60,000 observations(rows).
The dataset was collected for the purpose of building a model that can check energy grid stability 
from simulations of grid stability comprising one power source (a centralized generation node) 
supplying energy to three consumption nodes (4 - node star network) to decentralize smart grid 
control (DSGC ) which increases the stability of the smart grid  
```

  ![image](https://user-images.githubusercontent.com/123263600/215707735-04a529f5-99fe-4e45-a099-60ef261c0f09.png)
```  
This control system keeps track of the power demand and supply frequency on every producerconsumer node of the grid.
The most careful part of the decentralized smart energy grid is the information flow of electricity 
distribution. The information flow helps in deciding the stability of the decentralized smart grid. 
The model takes into consideration some parameters (features) such as:
1. Balancing power flow: the total power balance (nominal power produced or consumed at 
each grid node, deals with the units produced or consumed by the producer or consumer, 
respectively.)
2. The reaction time of nodes: the response time of participants to adjust consumption 
and/or production in response to price changes, deals with the change in the response 
according to the rise or fall in the price of power units.
3. energy price elasticity.
This dataset is augmented version by 3 times, thats mean the original dataset contains 10,000 
observations (rows), it can be augmented in to reach 60,000 observations, this is possipole and 
representing a permutation of the three consumers occupying three consumer nodes (4 - node star 
network).
```
# Methodology
   ![image](https://user-images.githubusercontent.com/123263600/215708121-6b734b0a-bdd7-42ac-9dba-282a146ca221.png)


# Conclusion
```
This study is based on power smart grid stability. to determine if it is stable or not the study 
uses Artificial neural networks (ANN) also several classification models such as (Support vector 
classification (SVM) by using RBF and POLY kernel, Random Forest Classifier, Decision Tree 
Classifier, K Neighbors Classifier (K-NN), Naive-Bayes, and Logistic Regression. These all 
models used open source data set (smart grid data) and finally based on the accuracy that got 
from models the comparison between models has been.
The result section shows the best accuracy is 98% when deep learning optimizer 'ANN' has been 
used. With activation of ReLU (for X) and Sigmoid (for y) activation, also used the best 
optimizer which is the ‘adam optimizer’.
The structure of ANN built to one input layer (12 input nodes), also three of hidden layers (24, 
24 and 12 respectively) and finally one output layer (single-node).
In any prediction model, the accuracy will be improved when the feature in the data set 
increases. Also, the feature must be relative to have the right prediction, In ANN the accuracy 
increases when increasing the number of epochs but be careful from over fitting.
In the last decade, the world has observed a huge change in climate change and renewable 
energy increase, and these two things cause a negative impact on power grid stability. This 
problem forced the change the grid to be smart and due to that Deep learning (DL) will play a 
major role in the smart grid, DL’s major applications in SG include energy forecasting, fault 
detection, cybersecurity awareness, prediction, and optimization
```
   ![image](https://user-images.githubusercontent.com/123263600/215708834-49d0d878-29a8-4364-a40b-6b47ffda0c84.png)

# Implement Artifiient Neutral Network (ANN)

![image](https://user-images.githubusercontent.com/123263600/215727302-3afaa57d-74d4-4a4b-bf33-e07ea29dee45.png)

# References
```
[1] Breviglieri, P., Erdem, T. & Eken, S. Predicting Smart Grid Stability with Optimized Deep Models. SN COMPUT. 
SCI. 2, 73 (2021). https://doi.org/10.1007/s42979-021-00463-5
[2] Smart grid evolution, 2018. Eolas Magazine. URL:https://www.eolasmagazine.ie/smartgrid-evolution/ (accessed 2.18.22).
[3] Smart Cities 2021, 4(2), 548-568; https://doi.org/10.3390/smartcities4020029
[4] Smart Grid System Report, U.S. Department of Energy. Available online: https://www.energy.gov/sites/prod/files/2019/02
/f59/Smart%20Grid%20System%20 Report%20November%202018_1.pdf (accessed on 15 January 2021).
[5] V. V. S. Lanka, M. Roy, S. Suman, and S. Prajapati, “Renewable energy and demand forecasting in an integrated smart grid,” 
in 2021 Innovations in Energy Management and Renewable Resources(Iemre 2021), A. K. Bar, M. Pal, S. Ghosh et al., Eds., IEEE, New York, 2021.
[6] M. Jayachandran, C. R. Reddy, S. Padmanaban, and A. H. Milyani, “Operational planning steps in smart electric power delivery
system,” Scientific Reports, vol. 11, no. 1, p. 17250, 2021
[7] Smart Grid System Report, U.S. Department of Energy. Available online:  https://www.energy.gov/sites/prod/files/2019/02/f59/
Smart%20Grid%20System%20Report%20 November%202018_1.pdf (accessed on 15 January 2021).
[8] Smart Cities 2021, 4, 548–568. https://doi.org/10.3390/smartcities4020029
[9] M. Massaoudi et al.: DL in SG Technology: A Review of Recent Advancements and Future Prospect
[10] Dataset website: https://www.kaggle.com/code/mineshjethva/power-grid-stability-with-deep-learning
```
