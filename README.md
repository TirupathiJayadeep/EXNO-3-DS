## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
### Feature Encoding:
<img width="1241" height="436" alt="image" src="https://github.com/user-attachments/assets/b5af1673-c7f3-43d4-8097-ba1b412c3b6e" />
<img width="1232" height="352" alt="image" src="https://github.com/user-attachments/assets/da9182a5-a5c4-4cb1-8c2f-ccabcd7cbe54" />
<img width="1216" height="400" alt="image" src="https://github.com/user-attachments/assets/4512310a-93e3-4a63-b562-af7b5b104b39" />
<img width="1224" height="523" alt="image" src="https://github.com/user-attachments/assets/b815a97e-a4da-49b2-9d7c-b704d8652a9d" />
<img width="1212" height="499" alt="image" src="https://github.com/user-attachments/assets/2ec3488a-0904-4040-8190-629f11a639fe" />
<img width="1222" height="380" alt="image" src="https://github.com/user-attachments/assets/44d7b984-be45-46d4-99e8-1c6457061451" />
<img width="1224" height="505" alt="image" src="https://github.com/user-attachments/assets/a7482a93-11dc-4a34-9f40-657245cd1cb1" />
<img width="1238" height="500" alt="image" src="https://github.com/user-attachments/assets/13d6da22-3e3a-4d0f-80f4-b73500f9a03a" />
<img width="1229" height="498" alt="image" src="https://github.com/user-attachments/assets/157aaa2c-f284-4c68-a405-6b02d863271a" />

### Feature Transformation:
<img width="1218" height="518" alt="image" src="https://github.com/user-attachments/assets/31e2a4d0-1a43-4a74-9f25-0bd826886f64" />
<img width="1211" height="162" alt="image" src="https://github.com/user-attachments/assets/03e88884-f3db-441f-84c5-f2a805b31320" />
<img width="1220" height="672" alt="image" src="https://github.com/user-attachments/assets/ef07520e-07e8-4f2d-a27e-bc6b01874234" />
<img width="1236" height="560" alt="image" src="https://github.com/user-attachments/assets/47c6fa6f-bc82-4970-a53b-7604b6f71e2e" />
<img width="1231" height="554" alt="image" src="https://github.com/user-attachments/assets/3841cbd6-c398-4630-b827-85d9c2dfdd94" />
<img width="1222" height="557" alt="image" src="https://github.com/user-attachments/assets/209f0a94-3d16-462d-8fa5-ca860a940f40" />
<img width="1239" height="546" alt="image" src="https://github.com/user-attachments/assets/7889dac6-00d1-454c-9859-64619cdc1770" />
<img width="1244" height="560" alt="image" src="https://github.com/user-attachments/assets/68010b0e-b3ba-4d73-9b37-b2a635000029" />
<img width="1231" height="500" alt="image" src="https://github.com/user-attachments/assets/1783d770-81b0-4389-a09f-d7c2072ab655" />
<img width="1234" height="590" alt="image" src="https://github.com/user-attachments/assets/bbcdb4d0-ab78-4092-b45f-f2069c93e66f" />
<img width="1230" height="484" alt="image" src="https://github.com/user-attachments/assets/af27479a-7b17-4673-910f-039f83ccf739" />
<img width="1220" height="591" alt="image" src="https://github.com/user-attachments/assets/ee0b438e-4add-4a6f-8145-952be1bba4e4" />
<img width="1228" height="494" alt="image" src="https://github.com/user-attachments/assets/b22c1a8e-b23c-423d-b807-b55b89b67314" />
<img width="1237" height="595" alt="image" src="https://github.com/user-attachments/assets/91feba8c-7515-4d30-b3cb-91c4e848ab19" />
<img width="1230" height="486" alt="image" src="https://github.com/user-attachments/assets/26e589bc-3a39-44d7-b1df-38e07e2a008c" />
<img width="1224" height="587" alt="image" src="https://github.com/user-attachments/assets/9d3ffbf7-d6e9-4e64-a4f1-298deb6685d4" />
<img width="1222" height="494" alt="image" src="https://github.com/user-attachments/assets/d5004852-be4a-43b1-9b4c-4424611fe56b" />
<img width="1223" height="584" alt="image" src="https://github.com/user-attachments/assets/8ac89cd1-08ba-4885-9560-d40026d7f4b1" />
<img width="1228" height="561" alt="image" src="https://github.com/user-attachments/assets/401fd1ff-ee1b-4e74-a8a8-a4ac97366391" />
<img width="1228" height="584" alt="image" src="https://github.com/user-attachments/assets/665a2bdd-86f5-40b9-840c-afe6ed07dba3" />










   
# RESULT:


       
