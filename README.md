# ML Prediction Models of mRS levels
This gives an access to the Machine Learning models that were developed to predict functional outcome and death at 3 months after stroke in Sweden between the period 2015 to 2020. 

This is in connection to the manuscript: **Developing a Machine Learning Prediction Model of Functional Outcome and Death at 3 months after Stroke in Sweden.**

The models are Multi-class Logistic regression (main effects model without regularization), Artificial neural network, Support vector machines, and XGBoost.

### Outcome of Interest
Functional outcome and death at 3 months after stroke.

The target variable was categorised into 3 classes (mRS 0-2: Independent, mRS 3-5: Dependent, mRS 6: Dead), coded as 0, 1, 2. 

### How to use the models
-code?
-?

### Features (Variables)
In that order, the features (after one-hot encoding) included:




| First Header  | Second Header | Third Header   | Forth Header | Fifth Header | Sixth Header    |
| ------------- | :-----------: | -------------: | :----------: | :----------: | --------------- |
| Tall Cell     |          *Long Cell*          ||         *Long Long Cell*                    |||
| ^^            |   **Bold**    | 1. first item  | *Italic*     | 3. third item | + first point  |\
| ^^            |               | 1. second item |              | 1. forth item | + second point |








|Feature (Variable)| Naming in the dataset|  Comment |
| :---:| :---:   | :---: | 
|Age | age   |  Continuous 18 to 110 years |
|Sex| sex |  0-Female 1-Male |
|:Atrial Fibrillation (AF):| atrial_fibrillation_-9 |      |

| atrial_fibrillation_1 |          |



| type_of_strokePrimaryIntracerebralHaemorrhage |   |
| type_of_strokeUknown |   " |
|NIHSS  |   stroke severity  |
| Inpatient_at_time_of_stroke_-9 |    |
| Inpatient_at_time_of_stroke_1 |       |
| hour_of_admission_4h_band040000to075959_-9 |          | 
| hour_of_admission_4h_band040000to075959_1 |         | 
| hour_of_admission_4h_band080000to115959_-9 |          | 
| hour_of_admission_4h_band080000to115959_1 |         | 
| hour_of_admission_4h_band120000to155959_-9 |          | 
| hour_of_admission_4h_band120000to155959_1 |          | 
| hour_of_admission_4h_band160000to195959_-9 |         | 
| hour_of_admission_4h_band160000to195959_1 |          | 
| hour_of_admission_4h_band200000to235959_-9 |          | 
| hour_of_admission_4h_band200000to235959_1 |          | 
| day_of_week_of_admissionMonday_-9 |          |
| day_of_week_of_admissionMonday_1 |          |
| day_of_week_of_admissionTuesday_-9 |          |
| day_of_week_of_admissionTuesday_1 |          |
| day_of_week_of_admissionWednesday_-9 |          |
| day_of_week_of_admissionWednesday_1 |          |
| day_of_week_of_admissionThursday_-9 |          |
| day_of_week_of_admissionThursday_1 |          |
| day_of_week_of_admissionFriday_-9 |          |
| day_of_week_of_admissionFriday_1 |         |
| day_of_week_of_admissionSaturday_-9 |          |
| day_of_week_of_admissionSaturday_1 |          |
| hypertension_-9 |  BP lowering drug    |
| hypertension_1 |     |

| diabetes_-9 |          |
| diabetes_1 |     |     |
| previous_stroke_tia_-9 |          |
| previous_stroke_tia_1 |          |
| rankin_scale_prestroke_-9 |         |
| rankin_scale_prestroke_3 |          |
| rankin_scale_prestroke_4|          |
| rankin_scale_prestroke_5 |          |                   
| smoking_-9 |          | 
| smoking_1 |          | 
| lipid_-9 |     lipid lowering drug     | 
| lipid_1 |     "     | 
| wake_up_stroke_-9 |          | 
| wake_up_stroke_1 |          | 
| stroke_alert_-9 |          | 
| stroke_alert_1 |          | 
| ambulance_-9 |          | 
| ambulance_1 |          | 
| prior_anticoagulation_-9 |          | 
| prior_anticoagulation_1 |          | 

NB:- Age and NIHSS (0-42) were used as continuous features while others as binary (0/1). -9 denote the separate category for missing values.              
                  
                  
                  
                  
                
