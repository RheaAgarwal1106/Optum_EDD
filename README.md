# Emergency Department Diversion Algorithm

## Aim

The aim of Emergency Department Diversion model is to predict the number of visits to Emergency Room per patient and classify the patients into high, medium and low level risk.

## Methodology
<img width="1421" height="1049" alt="image" src="https://github.com/user-attachments/assets/d480d2b1-362a-42a6-825e-daa41b4ee259" />

## Modelling Process

1. Data Preprocessing
- Obtaining features from dNHI, Symmetry and SDOH databases
- Engineering features to capture risk scores, severity level, impact of social factors in consultation with clinical experts

2. Exploratory Data Analysis
- Data transformation to handle skewness of numerical variables
- Removal of features based on frequency distributions and correlation matrix
- Removal of features with more than 80% 0s

3. Feature Selection
- A subset of most important features is selected to save computation time and improve model interpretability
  
4. Binary Model
- Classification techniques predict whether a person visits the ER over next 12 months
  
5. Conditional Model
Determines the frequency of visits for members who are expected to visit ER in the next 12 months

## Model Metrics

### Binary Model

<img width="401" height="97" alt="image" src="https://github.com/user-attachments/assets/e0c6d9f9-96f5-4de3-a967-33cd94383fec" />

### Conditional Model

<img width="401" height="97" alt="image" src="https://github.com/user-attachments/assets/d39bcc31-ca2a-4203-9dad-ae0f94bd65e3" />


