# shanmathi-Exp-5
from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\Users\Shanmathi\Downloads\airline-passengers.csv')
print(series.head())
series.plot()
pyplot.show()
![Screenshot (1)](https://github.com/user-attachments/assets/84f8f8fc-bf00-4f35-a8b5-8fa85bee0657)
series.plot(style='-.')
pyplot.show()
![Screenshot (3)](https://github.com/user-attachments/assets/882bf07a-09c2-46c6-a083-cc3272783eca)
series.hist()
pyplot.show()
![Screenshot (7)](https://github.com/user-attachments/assets/2a8a6f6a-6a25-4e1b-96ba-2c8f027f3d6d)
series.plot(kind='kde')
pyplot.show()
![Screenshot (6)](https://github.com/user-attachments/assets/10552a51-a2c0-4a16-ad78-d15ba2a7f13d)
