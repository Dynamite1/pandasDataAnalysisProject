# pandasDataAnalysisProject
In this project I will be working with Pandas library to analyse the data. 

# Reading the DataFrame

![image](https://user-images.githubusercontent.com/16399584/195719114-75fe8b7f-32c9-4946-b73c-d93e4014f4d4.png)

# To Know how many Rows and Columns

![image](https://user-images.githubusercontent.com/16399584/195719608-8c75deea-edb4-4f32-b589-b1da4bc142a5.png)

# info() method prints information about the DataFrame

![image](https://user-images.githubusercontent.com/16399584/195720401-f39886fe-5c08-4705-88c6-5d7f72f0c4e6.png)

# To Read Excel file need to mention sheet No 

![image](https://user-images.githubusercontent.com/16399584/195720714-e64fbad5-4cb7-424e-963b-7f0225a5ddb7.png)

# To read selected columns

![image](https://user-images.githubusercontent.com/16399584/195720883-514b2e9b-d483-4ba9-8046-b8162260848e.png)

# loc and iloc

![image](https://user-images.githubusercontent.com/16399584/195722651-f5299207-9f3f-4de5-b599-d9dd21125c40.png)

# sorting values

![image](https://user-images.githubusercontent.com/16399584/195722881-0269b45a-9e21-4d9e-852f-fe57e02d0462.png)

# Aggregation

import pandas as pd
df_excel=pd.read_excel(r"C:\Users\tareq\Downloads\IMDB_Movie.xlsx",sheet_name=0)
print(df_csv['movie_title'].count())
df_csv['duration'].sum()
df_csv['duration'].min()
df_csv['duration'].max()
df_csv['duration'].mean()

# Join 

![image](https://user-images.githubusercontent.com/16399584/195724297-b1a815ca-c308-49b9-9cc2-3595e200b09d.png)

