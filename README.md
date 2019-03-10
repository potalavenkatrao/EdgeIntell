# EdgeIntell
EdgeIntell


from io import StringIO

import pandas as pd
\nimport requests
\nurl='https://raw.githubusercontent.com/potalavenkatrao/EdgeIntell/Shares/Final_File.csv'
\ndf=pd.read_csv(url)
\n#print(df)
\nX = df.iloc[4:495, 3:13]   # Using 1:2 as indices will give us np array of dim (10, 1)
\ny = df.iloc[0:,12]
\ndf.head()
