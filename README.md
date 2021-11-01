# DEEP LEARNING ON CT SCANS FOR ACCURATE COVID-19 DIAGNOSIS 

COVID-19 is an infectious disease that is caused by a virus named SARS-CoV-2 which was first detected in late 2019. Apart from claiming almost 5 million lives since its emergence, it has also caused severe economic and social impacts all around the world. Existing diagnostic tools have limited success and often results in high false-negative rates which further accelerates the spread of this disease.

CT is fast and effective in capturing CT manifestations such as GGO and consolidations that are associated with COVID-19. Emerging machine learning techniques (deep learning) are also widely adopted and used in current medical diagnosis for diseases such as breast cancer. The CT dataset was assessed and obtained from https://www.kaggle.com/maedemaftouni/large-covid19-ct-slice-dataset7593 which consists of 7593 CT data from 466 patients with COVID-19 and 6893 CT data from 604 healthy followed by applying basic pre-processing operations. In this study, a self-developed model as well as CNN state-of-the-art pre-trained models such as VGG16 and VGG19 were used. 

After optimization of the various deep learning models, the Tuned custom VGG16 model was identified as the best model with a classification accuracy and sensitivity of 94.20% and 90.74% respectively while also possessing an AUROC of 0.985. The comparison with similar studies indicates that having a large dataset and the application of data augmentation techniques do reduce the degree of overfitting which resulted in higher performance deep learning models. The applicability of deep learning to be used in the clinical diagnosis of COVID-19 is clearly evident where it can possibly serve as an alternative solution to address current demands and a mean to alleviate the COVID-19 situation globally. 
