- **age**: Displays the age of the individual.

- **sex**: Displays the gender of the individual:
  - `1` = Male
  - `0` = Female

- **cp**: Chest-pain type, displays the type of chest pain experienced by the individual:
  - `0` = Typical angina
  - `1` = Atypical angina
  - `2` = Non-anginal pain
  - `3` = Asymptomatic

- **trestbps**: Resting Blood Pressure, displays the resting blood pressure value of an individual in mmHg. A value above 130-140 is typically cause for concern.

- **chol**: Serum Cholesterol, displays the serum cholesterol level in mg/dl.

- **fbs**: Fasting Blood Sugar, compares the fasting blood sugar value of an individual with 120 mg/dl:
  - `1` = Fasting blood sugar > 120 mg/dl (True)
  - `0` = Fasting blood sugar <= 120 mg/dl (False)
  
  *Note*: A value greater than 126 mg/dL signals diabetes.

- **restecg**: Resting ECG, displays resting electrocardiographic results:
  - `0` = Normal
  - `1` = ST-T wave abnormality (e.g., T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - `2` = Showing probable or definite left ventricular hypertrophy by Estes' criteria

- **thalach**: Maximum heart rate achieved by the individual.

- **exang**: Exercise-induced angina:
  - `1` = Yes
  - `0` = No

- **oldpeak**: ST depression induced by exercise relative to rest, displayed as an integer or float.

- **slope**: Slope of the peak exercise ST segment:
  - `0` = Upsloping (Better heart rate with exercise, uncommon)
  - `1` = Flat (Minimal change, typical healthy heart)
  - `2` = Downsloping (Signs of an unhealthy heart)

- **ca**: Number of major vessels (0–3) colored by fluoroscopy, displayed as an integer or float.

- **thal**: Displays the thalassemia condition:
  - `1`, `3` = Normal
  - `6` = Fixed defect
  - `7` = Reversible defect (No proper blood movement during exercise)

- **target**: Indicates whether the individual is suffering from heart disease:
  - `1` = Yes
  - `0` = No

