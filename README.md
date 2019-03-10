# EdgeIntell
EdgeIntell


from io import StringIO

import pandas as pd
import\ requests
url='https://raw.githubusercontent.com/potalavenkatrao/EdgeIntell/Shares/Final_File.csv'
df=pd.read_csv(url)
#print(df)
X = df.iloc[4:495, 3:13]   # Using 1:2 as indices will give us np array of dim (10, 1)
y = df.iloc[0:,12]
df.head()
