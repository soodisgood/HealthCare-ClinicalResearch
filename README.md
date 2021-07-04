# HealthCare-ClinicalResearch
The aim of this project is to build Machine Learning models to predict health conditions of patients based on Electronic Health Records

Background
When a person gets ill and visits a hospital, there are two common questions that are posed in front of the person:
1. What has happened to me?
2. How does my future look like?
While the first question refers to the diagnosis of the current situation to know the illness, the second is about predicting future medical risks. Exploring the answer to the first question is easy due to the availability of a broad spectrum of diagnostic tools today. The technology is much less advanced today to provide answers to the second question. Traditionally, this question about medical risk is answered only by experienced clinicians.
The challenge that the Healthcare industry is facing today, is that the experienced specialists are highly expensive and have limited availability. This is where modern Electronic Health Records (EHRs) bring a ray of hope as they promise to offer a fast and cheap alternative.

Typically, an EHR contains the history about the patient, hospital encounters, diagnoses and interventions, lab tests, and clinical narratives. The full adoption of EHRs has led to intensified research in building predictive models from this rich data source in the past few years.
Data Science facilitates building of such predictive models on patient-level temporal healthcare data. These models must address four open challenges:
• Long-term dependencies on healthcare. For instance, the onset of diabetes at middle age remains a risk factor for the rest of the life
• Representation of admission: The admission data is complex and consists of information related to diagnoses, interventions, and other such details.
• Medical records varying significantly in length are inherently episodic and irregular
• Medical records are a blend of the course of illness, intervening, and the developmental processes
In addition to addressing these four challenges, a predictive system is expected to comprehend medical records, determine present illness states, and predict future outcomes based on the data at hand.


Use Cases
The models shall mainly support the following use cases:
1. Predicting the future health outcomes of the patients: Build a model to use a patient's health timeline to predict the future conditions that the patient might be diagnosed with. This model can be used to predict any condition that might appear in the future. You can focus on lifelong non-communicable conditions like diabetes, hypertension, obesity, et al.
2. Predicting the future costs incurred by the patients: Build a model to predict the costs incurred by the patients in the next 12 months. Your model should be able to distinguish between the costs for medications and encounters. Think of it as a solution for an insurance company that wants to assess how much a patient would be spending on visiting a hospital for checkups and treatment and what they would be spending on medications.
3. Clustering of patients based on their health conditions: Build an unsupervised clustering model to group the patients into multiple clusters. Assess these clusters to get a sense of
which clusters (and with what conditions) patients fall into. This exercise will be useful in identifying various co-morbidities that co-occur in patients.
