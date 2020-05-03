# MSDS19012_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# VGG-16 (FC Only)
•	Training set results:  
Accuracy of the network on the 12,000 training images: 96 %  
Confusion Matrix:  
| true\predicted | infected | normal |
|--- |--- |--- |
| infected | 4657 | 262 |
| normal | 187 | 6894 |

•	Validation set results:  
Accuracy of the network on the 1500 validation images: 92 %  
Confusion Matrix:  
|true\predicted |  infected |    normal |
|--- |--- |--- |
|infected       | 557     |  58 |
|normal         | 51      |  834 |

•	Test set results:  
Accuracy of the network on the 1500 test images: 97 %  
Confusion Matrix:  
| true\predicted | infected |   normal |
|--- |--- |--- |
|    infected    |   589  |       26 |
|    normal      |   15   |      870 |

Precision: 0.975  
Recall:    0.958  
F1 score:  0.966  

# ResNet-18 (FC Only)
•	Training set results:  
Accuracy of the network on the 12,000 training images: 87 %  
Confusion Matrix:   
| true\predicted | infected  |   normal |
|--- |--- |--- |
|    infected    |   3899  |    1020 |
|    normal      |   456   |    6625 |

•	  Validation set results:  
Accuracy of the network on the 1500 validation images: 84 %  
Confusion Matrix: 
| true\predicted | infected |   normal |
|--- |--- |--- |
|    infected    |   458  |    157 |
|    normal      |   79   |    806 |

•	Test set results:  
Accuracy of the network on the 1500 test images: 90 %  
Confusion Matrix: 
| true\predicted | infected | normal |
|--- |--- |--- |
|    infected    |   515  |  100 |
|    normal      |   37   |  848 |

Precision: 0.933  
Recall:    0.837  
F1 score:  0.883  



# VGG-16 (Full Network)
•	Training set results:  
Accuracy of the network on the 12,000 training images: 96 %  
Confusion Matrix:  
|true\predicted | infected  |   normal |
|--- |--- |--- |
|   infected    |   4609  |    310 |
|   normal      |   114   |    6967 |

•	Validation set results:  
Accuracy of the network on the 1500 validation images: 92 %  
Confusion Matrix: 
| true\predicted|  infected |    normal|
| --- |--- |--- |
| infected      | 544     | 71|
| normal        | 37      | 848|

•	Test set results:  
Accuracy of the network on the 1500 test images: 97 %  
Confusion Matrix: 
|  true\predicted | infected |   normal |
|--- |--- |--- |
|     infected    |   584  |       31 |
|     normal      |   10   |      875 |

Precision: 0.983  
Recall:    0.950  
F1 score:  0.966  


# ResNet-18 (Full Network)
•	Training set results:  
Accuracy of the network on the 12,000 training images: 95 %  
Confusion Matrix: 
|  true\predicted | infected  |   normal |
|--- |--- |--- |
|     infected    |   4624  |    295 |
|     normal      |   236   |    6845 |

•	Validation set results:  
Accuracy of the network on the 1500 validation images: 92 %  
Confusion Matrix: 
|  true\predicted | infected  |  normal |
|--- |--- |--- |
|     infected    |   555   |   60 |
|     normal      |   53    |   832 |

•	Test set results:  
Accuracy of the network on the 1500 test images: 96 %  
Confusion Matrix: 
|  true\predicted | infected  |  normal |
|--- |--- |--- |
|     infected    |   580   |   35 |
|     normal      |   13    |   872 |

Precision: 0.978  
Recall:    0.943  
F1 score:  0.960  

# Dataset
https://drive.google.com/open?id=1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK&authuser=1

# vgg16_FC_Only.pth:
https://drive.google.com/open?id=1--oHNuBA7b1U_M-46xiiDKpRuYp9l2fw

# resnet18_FC_Only.pth:
https://drive.google.com/open?id=1-1RfpDVs3LAsVmY5igq-fDBOiNok56wd

# vgg16_entire.pth:
https://drive.google.com/open?id=14nVLCJ7dpjymV5flDR3fcdShaGbGIYTH

# resnet18_entire.pth
https://drive.google.com/open?id=1--L93Z0AAcvnIRQ-VrqueV7HOSwB-V7W

# Part 2 (with/ without Focal Loss)
# Dataset
https://drive.google.com/open?id=1eytbwaLQBv12psV8I-aMkIli9N3bf8nO&authuser=1

# VGG-16 without Focal Loss
Training Precision: 96.37%  
Training Recall:    95.95%  
Training F1-score:  95.94%  
  
Validation Precision: 95.11%  
Validation Recall:    95.34%  
Validation F1-score:  95.03%  

# ResNet-18 without Focal Loss  
Training Precision: 94.59%  
Training Recall:    93.72%  
Training F1-score:  93.89%  
  
Validation Precision: 92.47%  
Validation Recall:    91.45%  
Validation F1-score:  91.58%  


# VGG-16 with Focal Loss  
Training Precision: 93.45%  
Training Recall:    92.38%  
Training F1-score:  92.42%  
  
Validation Precision: 93.42%  
Validation Recall:    92.52%  
Validation F1-score:  92.58%  

# ResNet-18 with Focal Loss  
Training Precision: 93.93%  
Training Recall:    92.44%  
Training F1-score:  92.83%  
  
Validation Precision: 92.30%  
Validation Recall:    90.53%  
Validation F1-score:  91.04%  
