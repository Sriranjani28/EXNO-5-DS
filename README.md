# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:

import matplotlib.pyplot as plt

x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]

plt.plot(x_values,y_values)

<img width="572" alt="SS 01" src="https://github.com/user-attachments/assets/2ca44235-3d09-46e2-9ab8-469f1f6cb425" />

plt.show()

import matplotlib.pyplot as plt

x=[1,2,3]

y=[2,4,1]

plt.plot(x,y)

<img width="503" alt="SS 02" src="https://github.com/user-attachments/assets/b6d3fd77-a7f5-4bad-9663-29f7f71108aa" />

plt.xlabel('x - axis')

<img width="542" alt="SS 03" src="https://github.com/user-attachments/assets/5c401265-a505-4771-b867-59c82192cfd6" />

plt.ylabel('y - axis')

<img width="568" alt="image" src="https://github.com/user-attachments/assets/ea8bbe71-0634-4791-bc50-4335590071f1" />

plt.title('My first graph!')

<img width="566" alt="SS 05" src="https://github.com/user-attachments/assets/2485c899-68ec-4333-bf40-4eca1fb43830" />

plt.show()

import matplotlib.pyplot as plt

x1=[1,2,3]

y1=[2,4,1]

plt.plot(x1,y1,label="line 1")

<img width="581" alt="SS 06" src="https://github.com/user-attachments/assets/02c22d4a-b56e-4d80-bf14-51339463dd9f" />

x2=[1,2,3]

y2=[4,1,3]

plt.plot(x2,y2,label="line 2")

<img width="568" alt="SS 07" src="https://github.com/user-attachments/assets/379ee6ee-24b4-44e2-87a5-ff2ea19086e0" />

plt.xlabel("x-axis")

<img width="530" alt="SS 08" src="https://github.com/user-attachments/assets/74016af3-1c45-462b-a9ec-91a4b75520f7" />

plt.ylabel('y-axis')

<img width="603" alt="SS 09" src="https://github.com/user-attachments/assets/c0edc822-3dd3-45de-8881-8560d15f73a0" />

plt.title('Two lines on same graph!')

<img width="568" alt="SS 10" src="https://github.com/user-attachments/assets/313ea011-c8b0-42e6-b1b8-55002a56dba3" />

plt.legend()

<img width="905" alt="SS 11" src="https://github.com/user-attachments/assets/388bda47-5fc8-4583-9f1b-13840ed7b638" />

plt.show()

import matplotlib.pyplot as plt

x=[1,2,3,4,5,6]

y=[2,4,1,5,2,6]

plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)

<img width="454" alt="SS 12" src="https://github.com/user-attachments/assets/e42180e7-9b65-43ec-a5b2-96b8378c5237" />

plt.ylim(1,8)

plt.xlim(1,8)

<img width="468" alt="SS 13" src="https://github.com/user-attachments/assets/917c8d30-f384-4190-b162-91cecf24e54a" />

plt.xlabel()

<img width="479" alt="SS 14" src="https://github.com/user-attachments/assets/9dabf3e2-1d01-471a-bacb-c7db99ffbb01" />

plt.ylabel('y-axis')

<img width="515" alt="SS 15" src="https://github.com/user-attachments/assets/250140f3-7b56-481a-a642-30db994482f5" />

plt.title('Some cool customizations!')

<img width="473" alt="SS 16" src="https://github.com/user-attachments/assets/2b8a3bf7-5687-4fb9-90e8-fed083ab8cc6" />

plt.show()

yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]

plt.plot(yield_apples)

<img width="468" alt="SS 17" src="https://github.com/user-attachments/assets/11779774-085e-48ce-83e2-93a673be57d1" />

years=[2010,2011,2012,2013,2014,2015]

yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]

plt.plot(years, yield_apples)

<img width="496" alt="SS 18" src="https://github.com/user-attachments/assets/83b042ad-dc07-43d3-87ea-984e2d39eb80" />

years = range (2000, 2012)

apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]

oranges = [0.962, 0.941, 0.930, 0.923, 0.918, 0.908, 0.907, 0.904, 0.901, 0.898, 0.9, 0.896, ]

plt.plot(years, apples)

plt.plot(years, oranges)

plt.xlabel('Year')

plt.ylabel('Yield (tons per hectare)');

<img width="493" alt="SS 19" src="https://github.com/user-attachments/assets/44419e51-0976-4c40-bf50-7e39e59c4b9f" />

plt.plot(years, apples)

plt.plot(years, oranges)

plt.xlabel('Year')

plt.ylabel('Yield (tons per hectare)')

plt.title("Crop Yields in Kanto")

plt.legend (['Apples', 'Oranges']);

<img width="553" alt="SS 20" src="https://github.com/user-attachments/assets/c39cd6b8-b8ae-4962-be23-d24baf76acf4" />

plt.figure(figsize=(12,6))

plt.plot(years,oranges,marker='o')

plt.title("Yield of Oranges(tons per hectare)");

<img width="768" alt="SS 21" src="https://github.com/user-attachments/assets/225487c6-057b-48a9-9af5-5209e11c642f" />

plt.plot(years,apples,marker='o')

plt.plot(years,oranges,marker='x')

plt.xlabel('Year')

plt.ylabel('Yield(tons per hectare)')

plt.title("Crop Yields in Kanto")

plt.legend(['Apples','Oranges'])

<img width="460" alt="SS 22" src="https://github.com/user-attachments/assets/3351f4fb-02cf-4590-bd7e-443494a8105b" />

import matplotlib.pyplot as plt

x_values=[0,1,2,3,4,5]

y_values=[0,1,4,9,16,25]

plt.scatter(x_values,y_values,s=30,color="blue")

plt.show()

<img width="428" alt="SS 23" src="https://github.com/user-attachments/assets/2e67504f-3aab-405b-a4f4-d550b1d958d6" />

import matplotlib.pyplot as plt

x=[1,2,3,4,5,6,7,8,9,10]

y=[2,4,5,7,6,8,9,11,12,12]

plt.scatter(x,y,label="stars",color="green",marker="*",s=30)

<img width="412" alt="SS 24" src="https://github.com/user-attachments/assets/64897f7b-a972-42e1-ae7c-dd63f69f60e0" />

plt.xlabel('x-axis')

<img width="512" alt="SS 25" src="https://github.com/user-attachments/assets/497f1dd0-b203-4798-ab78-61885578daa7" />

plt.ylabel('y-axis')

<img width="463" alt="SS 26" src="https://github.com/user-attachments/assets/8cccb451-62c4-452b-b64c-c0cd139af930" />

plt.title('My scatter plot!')

<img width="436" alt="SS 27" src="https://github.com/user-attachments/assets/4b93dde2-887b-4afa-b7a9-99a9d86bf944" />

plt.legend()

<img width="925" alt="SS 28" src="https://github.com/user-attachments/assets/18112029-7b70-4be7-9d15-7a8f7f3aaa09" />

plt.show()

import matplotlib.pyplot as plt

import numpy as np

import pandas as pd

x=np.arange(0,10)

y=np.arange(11,21)

x

<img width="317" alt="SS 29" src="https://github.com/user-attachments/assets/16fd6aa0-f183-4347-aaf9-516903db0b15" />

y

<img width="341" alt="SS 30" src="https://github.com/user-attachments/assets/32a105f0-a449-4dd1-be83-a0d6c2fcb43f" />

plt.scatter(x,y,c='r')

plt.xlabel('X-axis')

plt.ylabel('Y-axis')

plt.title('Graph in 2D')

plt.savefig('Test.png')

<img width="479" alt="SS 31" src="https://github.com/user-attachments/assets/13f741f2-7113-49b1-8d58-f20ca2919909" />

y=x*x

y

<img width="565" alt="SS 32" src="https://github.com/user-attachments/assets/a0c88056-3a36-4d46-b945-2b3b59c06d9c" />

plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)

plt.xlabel('X-axis')

plt.ylabel('Y-axis')

plt.title('2d Diagram')

<img width="479" alt="SS 33" src="https://github.com/user-attachments/assets/a98f4dc5-1c64-47e4-a52e-d4ce577330dc" />

plt.subplot(2,2,1)

plt.plot(x,y,'r--')

plt.subplot(2,2,2)

plt.plot(x,y,'g*--')

plt.subplot(2,2,3)

plt.plot(x,y,'bo')

plt.subplot(2,2,4)

plt.plot(x,y,'go')

<img width="407" alt="SS 34" src="https://github.com/user-attachments/assets/bfb31e45-ee10-432b-8a9f-1f036806f40b" />

np.pi

<img width="426" alt="SS 35" src="https://github.com/user-attachments/assets/d1c364aa-10f3-431a-bef1-51714fbcd128" />

x=np.arange(0,4*np.pi,0.1)

y=np.sin(x)

plt.title("sine wave form")

plt.plot(x,y)

plt.show()

<img width="493" alt="SS 36" src="https://github.com/user-attachments/assets/931e7a2f-051d-4b6c-8f7d-57103d170af7" />

import matplotlib.pyplot as plt

import numpy as np

x=[1,2,3,4,5]

y1=[10,12,14,16,18]

y2=[5,7,9,11,13]

y3=[2,4,6,8,10]

plt.fill_between(x,y1,color='blue')

<img width="416" alt="SS 37" src="https://github.com/user-attachments/assets/c89632f2-d843-4421-8bfd-5d792053ea10" />

plt.fill_between(x,y2,color='green')

<img width="416" alt="SS 38" src="https://github.com/user-attachments/assets/3f72d27f-4e36-474e-8abf-dddbd8f22816" />

plt.legend(['y1','y2'])

<img width="422" alt="SS 39" src="https://github.com/user-attachments/assets/88c3a53b-b2f9-4719-8786-6e69d8137527" />

plt.show()

plt.stackplot(x,y1,y2,labels=['Line 1','Line 2','Line 3'])

<img width="437" alt="SS 40" src="https://github.com/user-attachments/assets/6e7c7aae-aff2-4257-83af-42b2241e376d" />

plt.legend(loc='upper left')

<img width="912" alt="SS 41" src="https://github.com/user-attachments/assets/50452ddb-feed-4a50-91e9-f1a4558be68e" />

plt.title('Stacked Line Chart')

<img width="469" alt="SS 42" src="https://github.com/user-attachments/assets/a8e1e600-1072-4cb7-a28f-4b7bdcf8d17a" />

plt.xlabel('X-axis')

<img width="423" alt="SS 43" src="https://github.com/user-attachments/assets/2a608da6-ccd4-4480-ae8f-b7118e4072cc" />

plt.ylabel('Y-axis')

<img width="449" alt="SS 44" src="https://github.com/user-attachments/assets/513427a5-c8d2-460f-98fd-332f33665dd1" />

plt.show()

import numpy as np

import matplotlib.pyplot as plt

from scipy.interpolate import make_interp_spline

x=np.array([1,2,3,4,5,6,7,8,9,10])

y=np.array([2,4,5,7,8,8,9,10,11,12])

spl=make_interp_spline(x,y)

import matplotlib.pyplot as plt

values=[5,6,3,7,2]

names=["A","B","C","D","E"]

plt.bar(names,values,color="green")

plt.show()

<img width="392" alt="SS 45" src="https://github.com/user-attachments/assets/7e4003b8-a5fe-44b1-b94e-325904a7e4e6" />

import matplotlib.pyplot as plt

values=[5,6,3,7,2]

names=["A","B","C","D","E"]

plt.bar(names,values,color="yellowgreen")

plt.show()

<img width="413" alt="SS 46" src="https://github.com/user-attachments/assets/f082358d-6086-4aad-ac1a-774c8bb585b5" />

import matplotlib.pyplot as plt

x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,5,9,2,1]

plt.hist(x,bins=10,color='blue',alpha=0.5)

plt.show()

<img width="412" alt="SS 47" src="https://github.com/user-attachments/assets/5ce5d918-6c1a-4fd0-8ec5-d968050a2c6f" />

import matplotlib.pyplot as plt

import numpy as np

np.random.seed(0)

data=np.random.normal(loc=0,scale=1,size=100)

data

<img width="469" alt="SS 48" src="https://github.com/user-attachments/assets/00c58e95-946a-4913-bfa9-3817b9d5cc87" />

fig,ax=plt.subplots()

ax.boxplot(data)

ax.set_xlabel('Data')

ax.set_ylabel('values')

ax.set_title('Box Plot')

<img width="513" alt="SS 49" src="https://github.com/user-attachments/assets/df4d458f-fc2f-4c19-b156-1a98e1036eb0" />

import matplotlib.pyplot as plt

activities=['eat','sleep','work','play']

slices=[3,7,8,6]

colors=['r','y','g','b']

plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()

<img width="397" alt="SS 50" src="https://github.com/user-attachments/assets/4520d83a-46d6-48be-96a1-72c449b4afc9" />

# Result:
   Thus the Data Visualization using matplot python library has been implemented for the given datas.
