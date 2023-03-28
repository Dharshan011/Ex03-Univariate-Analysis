# Ex03-Univariate-Analysis
## Aim:
To detect the Univariate Analysis by using default functions.

## Algorithm:
1.Import pandas(),numpy()and seaborn() for a required detection.

2.use the head()

3.The information and is null function.

4.Use the describe function.

5.Figure the boxplot.

6.plot the countrplot,Displot,Histoplot.

7.Print the program.

## program:
```
import pandas as pd
import numpy as np
import seaborn as sns
data=pd.read_csv('/content/SuperStore (1).csv')
data
data.head()
data.info()
data.dtypes
data['Sales'].value_counts()
data.describe()
data.isnull().sum()
sns.boxplot(x='Postal Code', data=data)
sns.countplot(x='Postal Code',data=data)
sns.distplot(data["Postal Code"])
sns.histplot(x='Postal Code',data=data)
```
## OUPUT:
![Screenshot 2023-03-28 153546](https://user-images.githubusercontent.com/113497491/228205313-e46f3642-7982-4e13-a3fe-061743c98137.png)
![Screenshot 2023-03-28 153615](https://user-images.githubusercontent.com/113497491/228205430-ccc62c02-9fbc-49d2-a007-f02fa5ce77a8.png)
![Screenshot 2023-03-28 153633](https://user-images.githubusercontent.com/113497491/228205504-40770345-9c7d-4a6a-a52d-df342bb9f94c.png)
![Screenshot 2023-03-28 153643](https://user-images.githubusercontent.com/113497491/228205657-a565fa14-1bd6-4c06-a019-7dd00f5952ba.png)
![Screenshot 2023-03-28 153652](https://user-images.githubusercontent.com/113497491/228205724-bcdbb8cc-fdf9-4969-97e0-cc37e3e13888.png)
![Screenshot 2023-03-28 153701](https://user-images.githubusercontent.com/113497491/228205778-b1b4a6e4-7b95-42f8-b7fa-6260e1f6ceb3.png)




![Screenshot 2023-03-28 153708](https://user-images.githubusercontent.com/113497491/228205849-3be54f79-5bec-4fae-892f-618530a26275.png)





![Screenshot 2023-03-28 153717](https://user-images.githubusercontent.com/113497491/228205909-5ee2c119-5910-4306-ab3e-08f4b6866528.png)
![Screenshot 2023-03-28 153727](https://user-images.githubusercontent.com/113497491/228205966-675565b4-d47e-4831-97d0-5c5a3ec25030.png)
![Screenshot 2023-03-28 153737](https://user-images.githubusercontent.com/113497491/228206014-8e3ec7eb-23b8-4702-97c1-220396555262.png)
![Screenshot 2023-03-28 153744](https://user-images.githubusercontent.com/113497491/228206052-4c57c6df-f1cc-4e51-a01c-ea3da290562b.png)

## RESULT:
Hence the univariate analyses is verified.
