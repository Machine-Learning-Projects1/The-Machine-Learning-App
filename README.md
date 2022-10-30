# <b>About the dataset</b> 
- Factors assessed by the BRFSS in 2020 included health status and healthy days, exercise, inadequate sleep, chronic health conditions, oral health, tobacco use, cancer screenings, and health-care access (core section). Optional Module topics for 2020 included prediabetes and diabetes, cognitive decline, electronic cigarettes, cancer survivorship (type, treatment, pain management) and sexual orientation/gender identity (SOGI).

</br>

## Dataset Description [Source](https://www.cdc.gov/brfss/annual_data/2020/pdf/codebook20_llcp-v2-508.pdf)

<br>

|Category|Label|Question|Value| 
|-|-|-|-|
|<b>HeartDisease</b>|Ever had CHD or MI| <i>-Respondents that have ever reported having coronary <br> -heart disease (CHD) or myocardial infarction (MI)</i>|-Yes<br>-No|
|<b>BMI</b>|Computed body mass index|<i>Computed body mass index</i>|Integer[1-9999]
|<b>Smoking</b>|Smoked at Least 100 Cigarettes|<i>Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes]</i>|-Yes<br>-No|
|<b>AlcoholDrinking</b>|Heavy Alcohol Consumption Calculated Variable|<i>Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week)</i>|-Yes<br>-No|
|<b>Stroke</b>|Ever Diagnosed with a Stroke|<i>(Ever told) (you had) a stroke.</i>|-Yes<br>-No|
|<b>PhysicalHealth</b>|Number of Days Physical Health Not Good|<i>Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good?</i>|Number of days [1-30]|
|<b>MentalHealth</b>|Number of Days Mental Health Not Good|<i>Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good?</i>|Number of days [1-30]|
|<b>DiffWalking</b>|Difficulty Walking or Climbing Stairs|<i>Do you have serious difficulty walking or climbing stairs?</i>|-Yes<br>-No|
|<b>Sex</b>|Are you male or female?|<i>Are you male or female?</i>|-Male<br>-Female|
|<b>AgeCategory</b>|Reported age in five-year age categories calculated variable|<i>Fourteen-level age category</i>|-Age [18-79]<br>-Age [80 or older]|
|<b>Race</b>|Imputed race/ethnicity value|<i>Imputed race/ethnicity value (This value is the reported race/ethnicity or an imputed race/ethnicity, if the respondent refused to give a race/ethnicity. The value of the imputed race/ethnicity will be the most common race/ethnicity response for that region of the state)</i>|-White<br>-Black<br>-Asian<br>-American Indian/Alaskan Native<br>-Hispanic<br>-Other|
|<b>Diabetic</b>|(Ever told) you had diabetes|<i>(Ever told) (you had) diabetes? (If ´Yes´ and respondent is female, ask ´Was this only when you were pregnant?´. If Respondent says pre-diabetes or borderline diabetes, use response code 4.)</i>|-Yes<br>-No<br>-No, borderline diabetes<br>-Yes (during pregnancy)|
|<b>PhysicalActivity</b>|Exercise in Past 30 Days|<i>During the past month, other than your regular job, did you participate in any physical activities or exercises such as running, calisthenics, golf, gardening, or walking for exercise?</i>|-Yes<br>-No|
|<b>GenHealth</b>|General Health|<i>Would you say that in general your health is:</i>|-Excellent<br>-Very good<br>-Good<br>-Fair<br>-Poor|
|<b>SleepTime</b>|How Much Time Do You Sleep|<i>On average, how many hours of sleep do you get in a 24-hour period?</i>|Number of hours [1-24]|
|<b>Asthma</b>|Ever Told Had Asthma|<i>(Ever told) (you had) asthma?</i>|-Yes<br>-No|
|<b>KidneyDisease</b>|Ever told you have kidney disease?|<i>Not including kidney stones, bladder infection or incontinence, were you ever told you had kidney disease?</i>|-Yes<br>-No|
|<b>SkinCancer</b>|(Ever told) you had skin cancer?|<i>(Ever told) (you had) skin cancer?</i>|-Yes<br>-No|

