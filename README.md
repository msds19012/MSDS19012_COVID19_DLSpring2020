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

