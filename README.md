# MonkeyPox-Symptomatic-analysis-and-prediction
MonkeyPox disease prediction system by getting symptoms from patients.  

An outbreak of monkeypox, a viral disease, was confirmed in May
2022. It got reported in more than 30 countries. Monkeypox is a
rare viral disease that is transmitted from animals to humans and can also spread
from person to person. Early detection of monkeypox is important for controlling
outbreaks and preventing the spread of the virus.
Currently, mpox is detected using laboratory tests including the enzymelinked immunosorbent assay (ELISA), polymerase chain reaction (PCR), and
virus culture. While these tests are effective at detecting mpox, they can be timeconsuming and require specialized equipment and trained personnel. The goal of
this study was to develop and evaluate a mpox detection system based on the
symptoms being experienced by the patients , that is accurate, reliable, and easy
to use. The research has been done to find out the most prominent symptoms
based on the case definitions and the patient record data provided by health
organizations. The symptoms include fever, rashes, skin lesions and genital
ulcers.  
In this study, we developed and evaluated a mpox detection system using
machine learning algorithms to predict mpox using the symptoms reported by the
patients to provide quick and easy mean to confirm and differentiate it from other
similar diseases like chicken-pox , which has been challenging for doctors at
times.

## Problem statement
Monkeypox is a rare viral disease that can cause severe illness in humans and other primates.
The symptoms of monkeypox are similar to other diseases like chickenpox, making it difficult
to diagnose accurately. Traditional laboratory methods for detecting monkeypox are timeconsuming and resource-intensive. This project aims to develop a machine learning-based
model that can accurately detect monkeypox in a rapid and cost-effective manner to improve
the early identification of cases and aid in outbreak control efforts.  
  
This problem statement highlights the main challenges of detecting monkeypox which include:  
 the similarity of symptoms with other diseases  
 the complexity of traditional laboratory methods  

## Objective
The main objective of a monkeypox disease detection model project would be to develop a
machine learning-based model that can accurately and rapidly detect monkeypox in order to
aid public health officials in their efforts to control the spread of the disease and improve
patient outcomes.  

Specifically, the model could be used to:  
 Improve diagnostic accuracy: By using machine learning algorithms to analyze data
from patients, the model could accurately identify cases of monkeypox, even when
symptoms are similar to other diseases.  
 Reduce the time to diagnosis: Traditional laboratory methods for detecting monkeypox
can be time-consuming and resource-intensive. A machine learning-based model could
provide a faster and more efficient way to diagnose the disease.  
 Improve outbreak control efforts: Early identification of cases is critical for controlling
the spread of monkeypox. The model could help public health officials identify and
respond to outbreaks more quickly.  
 Reduce the cost of diagnosis: By using machine learning algorithms, the model could
be designed to be cost-effective, reducing the overall cost of diagnosis.  

## System Architecture 

![tempsnip](https://github.com/gaurav19940/MonkeyPox-Symptomatic-analysis-and-prediction/assets/70307677/7f217f60-65bf-4d1b-8222-1e8551e8bc2e)

## System development approach
The system is designed in various phases:  
 Data processing  
 Modeling over various Machine Learning Algorithms.  
 Comparing models based on evaluation methods.  
 Implementing with best fitted algorithm.  

## Algorithms 
 **Naive Bayes Algorithm**  
 **Decision Trees**  
 **Logistic Regression**  
 **Random Forest**  

 The Algorithms were chosen after analysing previous works and performance of various algorithms on similar works.  
 Also, ANN and Ensemble model over these algorithms were implemented.  

## Evaluation Metrices

**Accuracy**: The percentage of correctly classified instances out of all instances.  
**Specificity**: The percentage of true negative predictions out of all actual negative instances.  
**Sensitivity**: The percentage of true positive predictions out of all actual positive instances.  
**ROC Curve**:The Receiver Operator Characteristic (ROC) curve is an evaluation metric for binary classification problems. It is a probability curve that plots the TPR against FPR at various threshold values and essentially separates the ‘signal’ from the ‘noise.’  

## Results 

**Decision Trees**: achieved an accuracy of 68.14%, specificity of 83%, sensitivity of 40%.
**Random Forest**: achieved an accuracy of 68.33%, specificity of 85%, sensitivity of 38%.
**Logistic Regression**: achieved an accuracy of 66.88%, specificity of 89%, sensitivity of 26%.
**Naive Bayes**: achieved an accuracy of 68.65%, specificity of 91%, sensitivity of 28%.
**ANN**: achieved an accuracy of 70%.
**Ensemble Learning**: achieved an accuracy of 69.86%.

## Limitations 
Discussion of the limitations and potential biases of the study  

There were several limitations to our study. Firstly, our dataset was relatively small, which could have affected the accuracy of our models. Secondly, we only considered symptoms in our analysis, and did not include other factors such as age, gender, and medical history. Finally, our study was based on a retrospective analysis of medical records, which could have introduced biases in the data.  

## Conclusion

Machine learning algorithms can be an effective tool for predicting monkeypox based on symptoms. These algorithms can accurately identify patients with the disease, even in cases where symptoms may be atypical.  

Future research on monkeypox prediction using machine learning should focus on validating findings on larger and diverse datasets, developing more sophisticated algorithms like deep learning, and investigating the impact of external factors on prediction accuracy. Additionally, comparing machine learning with traditional diagnostic methods would provide valuable insights into the potential of machine learning for monkeypox diagnosis and prediction. Overall, there is significant potential for machine learning to advance monkeypox prediction based on symptoms.
 
 
