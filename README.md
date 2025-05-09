# Data Engineering Project

For this project, I used the Netflix User Database dataset from Kaggle.
https://raw.githubusercontent.com/Zhangylay-2000/de-zoomcamp/b4d18e83c4b6a20e98235a7c0fa4228f8110a8f6/Netflix%20Userbase.csv

![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/3ba0641f-6909-46d7-8f2a-08b1b4767e99)

Aim of the project: 
* Select a dataset of interest: Netflix User Base
* Creating a pipeline for processing this dataset and putting it to a datalake:
The data was loaded via the API into Mage, then after some small transformations I loaded it into gcs.
![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/af09c953-0531-441f-a98c-7258ca2555f3)

![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/15327b09-fbf8-4388-8d02-ebe8a7d071b8)

With gcs the data was loaded into local spark. After processing, it was sent back to gcs.
![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/bf586737-7d14-44ab-a02b-62eb266f7e00)

![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/6872ba0f-6349-4edd-984f-2d47a4cae32b)

![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/cd21e158-1f68-492f-995f-4bf4d7ba0925)

Next, the data was loaded back into Mage and transferred to BigQuery.
![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/08c2539b-2361-4805-8036-3ce42d5b8f66)

The data was sent using the following command:
![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/43ad6cc1-418a-4e0b-88a3-400b0e9416d7)

In the end, using data from BigQuery, the data was visualized in Looker:
https://lookerstudio.google.com/reporting/59405f98-b5fc-4641-92e7-71b08200e5fe/page/evlwD/edit
![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/8ffe72a3-38f9-4168-8885-81ea2281821b)

![image](https://github.com/Zhangylay-2000/StudyMaterials/assets/68446698/62c81956-4721-406e-bd9f-2429dd46762e)












