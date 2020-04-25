# MSDS19012_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# VGG-16 (FC Only)
•	Training set results:
1.	Accuracy of the network on the 12,000 training images is 96%.
2.	Confusion matrix :
                      (Predicted value)
     	                 Infected	Normal
(True value)	Infected	4657	   262
	             Normal	  187	     6894 
•	Validation set results:
1.	Accuracy of the network on the 1500 validation images is 92%.
2.	Confusion matrix :
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	557	    58
	             Normal	  51	    834
•	Test set results:
1.	Accuracy of the network on the 1500 test images is 97%
2.	Confusion matrix :
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected  589	    26
	             Normal	  15	    870
3.	Precision: 0.975
4.	Recall:    0.958
5.	F1 score:  0.966

# ResNet-18 (FC Only)
•	Training set results:
1.	Accuracy of the network on the 12,000 training images is 87%.
2.	Confusion matrix:
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	3899	1020
	             Normal	  456	  6625
•	  Validation set results:
1.	Accuracy of the network on the 1500 validation images is 84%.
2.	Confusion matrix:
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	458	    157
	             Normal	  79	    806
•	Test set results:
1.	Accuracy of the network on the 1500 test images is 90%
2.	Confusion matrix:
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	515	  100
	             Normal	  37	  848
3.	Precision: 0.933
4.	Recall:    0.837
5.	F1 score:  0.883

# VGG-16 (Full Network)
•	Training set results:
1.	Accuracy of the network on the 12,000 training images is 96%.
2.	Confusion matrix
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	4609	310
	             Normal	  114	  6967
•	Validation set results:
1.	Accuracy of the network on the 1500 validation images is 92%.
2.	Confusion matrix
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	557	  71
	             Normal	  37	  848
 •	Test set results:
1.	Accuracy of the network on the 1500 test images is 97%
2.	Confusion matrix
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	584	   31
	             Normal	  10	   875
3.	Precision: 0.983
4.	Recall:    0.950
5.	F1 score:  0.966

# ResNet-18 (FC Only)
•	Training set results:
1.	Accuracy of the network on the 12,000 training images is 95%.
2.	Confusion matrix:
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	4624	 295
	             Normal	   236	 6845
•	  Validation set results:
1.	Accuracy of the network on the 1500 validation images is 92%.
2.	Confusion matrix:
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	555	   60
	             Normal	   53	   832
•	Test set results:
1.	Accuracy of the network on the 1500 test images is 96%
2.	Confusion matrix:
                    (Predicted value)
	                  Infected	Normal
(True value)	Infected	580	  35
	             Normal	  13	 872
3.	Precision: 0.978
4.	Recall:    0.943
5.	F1 score:  0.960
