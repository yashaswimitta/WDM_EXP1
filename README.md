### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE:  11.2.24
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
Training Data Set -> Employee Table

<img width="180" alt="wdm 1-1" src="https://github.com/yashaswimitta/WDM_EXP1/assets/94619247/ea53e36a-6fd5-49ca-9421-bafdb8b7c1b6">

Training Data Set-> Weather Table

<img width="169" alt="wdm 1-2" src="https://github.com/yashaswimitta/WDM_EXP1/assets/94619247/d06c775d-e8c3-4883-8afd-a2b681b6f022">


### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
Employee Table after adding new attribute ADDRESS:

<img width="215" alt="wdm 1-3" src="https://github.com/yashaswimitta/WDM_EXP1/assets/94619247/add817c5-7172-444a-a79e-fb32ffe9e1d9">

Weather Table after adding new attribute CLIMATE:

<img width="215" alt="wdm 1-4" src="https://github.com/yashaswimitta/WDM_EXP1/assets/94619247/0ef0b077-7d52-4b04-9a9d-ee32d5348a4b">


### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
Employee Table after removing attributes SALARY, GENDER:

<img width="267" alt="wdm 1-5" src="https://github.com/yashaswimitta/WDM_EXP1/assets/94619247/49b92ba7-3c8e-42ba-9fa0-55f74f5a4eef">

Weather Table after removing attributes WINDY, PLAY:

<img width="192" alt="wdm 1-6" src="https://github.com/yashaswimitta/WDM_EXP1/assets/94619247/7acb9cb2-e2f3-4dba-8582-97ab358f104b">


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
Employee Table after Normalizing ID, EXP, PHONE:

<img width="185" alt="wdm 1-7" src="https://github.com/yashaswimitta/WDM_EXP1/assets/94619247/8fcdba8d-4f85-4181-9506-4b98f7899b4e">

Weather Table after Normalizing TEMPARATURE, HUMIDITY:

<img width="312" alt="wdm 1-8" src="https://github.com/yashaswimitta/WDM_EXP1/assets/94619247/df87cd1c-dbbd-4d84-a4af-9be3e72a9cf3">


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
