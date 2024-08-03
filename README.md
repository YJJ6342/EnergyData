# Energy Theft Detection using DL, CNN, LSTM, Transformer, ImageTransfomation
Time Series Data Analysis

Energy Theft Detection using image transformation technique and tiled convolutional neural network

Dataset : https://github.com/henryRDlab/ElectricityTheftDetection 

No.	Method	Data Preparation			Batch	Epoch	Kernel Size		Confusion Matrix			
		"Window
(day)"	"Total
(day)"	Scaling			Residual	DCNN	Accuracy	Precision	Recall	F-1
1	"Base
(LSTM + DCNN)"	7	1029	Global	64	20	3	3	0.9053	0.9506	0.9467	0.9487
2		7	1029	Row	64	20	3	3	0.9263	0.9438	0.9785	0.9609
3		14	1036	Row	64	20	3	3	0.9238	0.9441	0.9745	0.9591
4		28	1036	Row	64	20	3	3	0.9203	0.9458	0.9684	0.9570
5		28	1036	Row	64	20	5	5	0.9101	0.9383	0.9653	0.9516
6	"New
(Attention + DCNN)"	7	1029	Row	64	20	-	3	0.9155	0.9490	0.9602	0.9546
7		14	1036	Row	64	20	-	3	0.9188	0.9450	0.9675	0.9562
8		28	1036	Row	64	20	-	3	0.9054	0.9488	0.9489	0.9489
9	ViT	28	1036	Row	64	76	-	-	0.8546	0.9495	0.8885	0.9180
![image](https://github.com/user-attachments/assets/c4746985-61d3-47c0-8dc0-3b88407ffcdd)


[Reference]

1. Huang Q. et al, A Novel Electricity Theft Detection Strategy Based on Dual-Time Feature Fusion and Deep Learning Methods, Energies 2024, 17, 275.

2. Inam Ullah Khan et al, A Stacked Machine and Deep Learning-Based Approach for Analysing Electricity Theft in Smart Grids, IEEE TRANSACTIONS ON SMART GRID, VOL. 13, NO. 2, MARCH 2022.
   
3. Encoding Time Series as Images for Visual Inspection and Classification Using Tiled Convolutional Neural Networks, ZhiguangWang and Tim Oates, Trajectory-Based Behavior Analytics: Papers from the 2015 AAAI Workshop, 2015.

4. Zibin Zheng, Yatao Yang, Xiangdong Niu, Hong-Ning Dai, Yuren Zhou, "Wide and Deep Convolutional Neural Networks for Electricity-Theft Detection to Secure Smart Grids", IEEE Transactions on Industrial Informatics,vol. 14, no. 4, pp. 1606-1615, April 2018 Publication year: 2018

