
# Predicting heart disease using machine learning
1.Problem Definition
Given clinical parameters about a patient, can we predict whether or not they have heart disease?

2. Features
This is where you'll get different information about each of the features in your data. You can do this via doing your own research (such as looking at the links above) or by talking to a subject matter expert (someone who knows about the dataset).



age - age in years
sex - (1 = male; 0 = female)
cp - chest pain type
Typical angina: chest pain related decrease blood supply to the heart
Atypical angina: chest pain not related to heart
Non-anginal pain: typically esophageal spasms (non heart related)
Asymptomatic: chest pain not showing signs of disease
trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
chol - serum cholestoral in mg/dl serum = LDL + HDL + .2 * triglycerides above 200 is cause for concern
fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) '>126' mg/dL signals diabetes
restecg - resting electrocardiographic results
Nothing to note
ST-T Wave abnormality can range from mild symptoms to severe problems signals non-normal heart beat
Possible or definite left ventricular hypertrophy
Enlarged heart's main pumping chamber
thalach - maximum heart rate achieved
exang - exercise induced angina (1 = yes; 0 = no)
oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
slope - the slope of the peak exercise ST segment
Upsloping: better heart rate with excercise (uncommon)
Flatsloping: minimal change (typical healthy heart)
Downslopins: signs of unhealthy heart
ca - number of major vessels (0-3) colored by flourosopy colored vessel means the doctor can see the blood passing through the more blood movement the better (no clots)
thal - thalium stress result 1,3: normal
fixed defect: used to be defect but ok now
reversable defect: no proper blood movement when excercising
target - have disease or not (1=yes, 0=no) (= the predicted attribute)

