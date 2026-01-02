## Estimation of Obesity Levels Based On Eating Habits and Physical Condition

As it is known, obesity and exessive weight is a common problem nowadays. Accessibility of high-calorie food and lack of physical activity results in significant part of people dealing with weight problems. In that context apps and programs which are able to predict obesity using input factors describing person's lifestyle and habits seem quite useful. Such algorithms could be used in healthcare system or in apps which help to manage healthy lifestyle, eating habits, exercising. 

Dataset includes data for the estimation of obesity levels in individuals from the countries of Mexico, Peru and Colombia, based on their eating habits and physical condition. The data contains 17 attributes and 2111 records, the records are labeled with the class variable NObesity (Obesity Level), that allows classification of the data using the values of Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II and Obesity Type III. 77% of the data was generated synthetically using the Weka tool and the SMOTE filter, 23% of the data was collected directly from users through a web platform.

The goal of the project is to predict weight category based on the attributes, presented in dataset, using appropriate classification algorithm. Model should demonstrate accurasy of at least 80%

__Variables:__ 
| Name                          | Type        | Description |
|------------------------------|------------|-------------|
| Gender                        | Categorical |  |
| Age                           | Continuous  |  |
| Height                        | Continuous  |  |
| Weight                        | Continuous  |  |
| family_history_with_overweight | Binary      | Has a family member suffered or suffers from overweight? |
| FAVC                          | Binary      | Do you eat high caloric food frequently? |
| FCVC                          | Integer     | Do you usually eat vegetables in your meals? |
| NCP                           | Continuous  | How many main meals do you have daily? |
| CAEC                          | Categorical | Do you eat any food between meals? |
| SMOKE                         | Binary      | Do you smoke? |
| CH2O                          | Continuous  | How much water do you drink daily? |
| SCC                           | Binary      | Do you monitor the calories you eat daily? |
| FAF                           | Continuous  | How often do you have physical activity? |
| TUE                           | Integer     | How much time do you use technological devices such as cell phone, videogames, television, computer, and others? |
| CALC                          | Categorical | How often do you drink alcohol? |
| MTRANS                        | Categorical | Which transportation do you usually use? |
| NObeyesdad                    | Categorical | Target variable |



_Source: https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition_
