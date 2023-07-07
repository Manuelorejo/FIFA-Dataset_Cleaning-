# FIFA-Dataset_Cleaning-
This a data cleaning project on a FIFA dataset gotten from Kaggle(https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring)

The steps taken to clean the data are:
1. The "Height" column was stripped of the feet(') and inches(") characters and converted to centimeters and float data type
2. the "Weight" column was stripped of the pounds(lbs) units and converted to integer data tyoe
3. The newline characters were removed from the dataset
4. The "Value","Wage" and "Release clause" columns were stripped of the Million(M) and thousand(K) characters, multiplied then converted to integer data type i.e "200M" became "200000000"
5. The columns with the star "★" characters were stripped of them and converted to integers
   
