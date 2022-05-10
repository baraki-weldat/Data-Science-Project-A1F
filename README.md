# Data Science Project A1F
### Course Objective
 The student will study a problem related to data science, and show that he/she has acquired an intellectual maturity in the field. e.g., by being able to critically evaluate different methods for data analysis. The project can be carried out in collaboration with an external organization. The work shall be carried out in connection with the research interests of the researchers at the University of Skövde and project ideas can be found under Files --> Project ideas. The student can of course pitch his/her own idea, which has to be discussed with a potential supervisor.
### EXPLAINABLE HATE SPEECH CLASSIFICATION:Comparative Analysis of BERT Variants
1. **INTRODUCTION:** In this research, the researcher studies three pre-trained Bidirectional Encoder Representations from Transformers (BERT) models that are used to detect hate speech and offensive language on Twitter data sets. The data set used for the study is based on real Twitter data, where sentences have been manually classified as either hate, offensive, or neither by users. The natural language processing data sets have similar patterns and characteristics which can be  reused. Training machine learning Natural Language Processing (NLP) models from scratch is a repetitive process and computationally expensive which requires adapting the previous model's knowledge and reuse in other related tasks. So, pre-trained BERT transformers are fine-tuned using the collected data sets, with less computational costs. The three models were evaluated using accuracy and f1-score performance measurement metrics.
2. **Datasets:** Twitter datasets with three classes of hate, offensive and nuetral texts were collected. 
3. **Methods and Tools:** BERT models were used for classification of the twitter tweets. To show how the class was determined was explained using [SHAP](https://shap.readthedocs.io/en/latest/index.html). SHAP is the most suited explanation technique to explain the prediction results of this particular scenario. Especially, the additive property of the Shapley values is the most important feature available in SHAP Explanation tool to find contributions of individual words based on prediction result. SHAP method is the only method to deliver full explanation. SHAP is simple to use, provide an overall view of the prediction results, and how their values are impacting the model’s predictions.

Click the link to read the full report of the Comparative Analysis of the [EXPLAINABLE HATE SPEECH CLASSIFICATION](Data Science Project on HateSpeech Explainable Classification Model.pdf).

**Sample Explanations from the SHAP:** 
![Experimental Setup](</Sample Explanations/Experimental Setup.png>)
![Saliency Plots for Selected Tweets](</Sample Explanations/SaliencyPlotsAllTop.png>)
![Interactive Plots for Hate speech](</Sample Explanations/SaliencyPlotsForHateSpeech.png>)
![Visualizing of the to Top Words Impacting the "Hate Speech” Class ](</Sample Explanations/BarHateSpeech.png>)
### Course Literature
- Berndtsson, M. et. al. (2007). Thesis Projects: A Guide for Students in Computer Science and Information Systems. London: Springer-Verlag London Ltd. ISBN9781848000087.
- Dawson, C. W. (2009). Projects in Computing and Information Systems: A Student’s Guide. Harlow:Addison Wesley Professional. ISBN 0273721313.

