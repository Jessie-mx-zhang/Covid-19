# Covid-19

## About Dataset

# Context
Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus. Most people infected with COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment. Older people, and those with underlying medical problems like cardiovascular disease, diabetes, chronic respiratory disease, and cancer are more likely to develop serious illness.

During the entire course of the pandemic, one of the main problems that healthcare providers have faced is the shortage of medical resources and a proper plan to efficiently distribute them. In these tough times, being able to predict what kind of resource an individual might require at the time of being tested positive or even before that will be of immense help to the authorities as they would be able to procure and arrange for the resources necessary to save the life of that patient.

This project aimed to apply machine learning techniques to analyze clinical data of COVID-19 patients to predict their risk levels. By modeling patients' current symptoms, status, and medical histories, we developed several predictive models, including Logistic Regression, Linear Discriminant Analysis (LDA), and Quadratic Discriminant Analysis (QDA).

After training and validation, these models demonstrated a strong predictive capability for determining patient risk levels, as evidenced by Receiver Operating Characteristic (ROC) curves and Area Under the Curve (AUC) metrics. Our results indicate that the Logistic Regression model performed the best, followed by LDA and QDA models.

In the current phase of the project, we have successfully carried out an initial analysis of the data and provided robust models that can support decision-making in the allocation of medical resources. These models have the potential to assist healthcare providers in identifying high-risk patients who should be prioritized for treatment and could lead to improved patient outcomes through more strategic distribution of medical resources.

While our analysis has yielded positive results, it is important to note that any clinical application of machine learning models requires thorough validation and testing. Therefore, although this project will not continue to further development, we encourage future researchers to build upon these preliminary findings and further test and refine these models in broader clinical settings.

# content
The dataset was provided by the Mexican government ([link](https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico)). This dataset contains an enormous number of anonymized patient-related information including pre-conditions. The raw dataset consists of 21 unique features and 1,048,576 unique patients. In the Boolean features, 1 means "yes" and 2 means "no". values as 97 and 99 are missing data.
