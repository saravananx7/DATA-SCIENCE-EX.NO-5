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

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

marks = [13,45,63,78]

student=['ABC','QOR','EFB','TOB']

plt.plot(marks,student)

plt.xlabel('Marks')

plt.ylabel('Student Name')

plt.show()

student = ['A','B','C','D']

attendence = [90,85,73,88]

plt.plot(student,attendence)

plt.xlabel('Attendence')

plt.ylabel('student Name')

plt.show()
<img width="739" height="755" alt="image" src="https://github.com/user-attachments/assets/34df0e79-0411-4658-a046-cff8fbac143e" />

x=[10,20,30,40,50]

y=[100,200,300,400,500]

plt.scatter(x,y,label='stars',color='green',marker='*',s=30)

plt.show() x=np.arange(0,15)

y=np.arange(0,15)

x

y plt.scatter(x,y,c='r')

plt.xlabel('X axis')

plt.ylabel('y axis')

plt.title('Scatter plot')

plt.show()
<img width="685" height="739" alt="image" src="https://github.com/user-attachments/assets/edb8a667-0a48-4d69-9777-f26db2ae2c41" />

act=['eat','sleep','work','play']

slices=[3,7,8,6]

color=['r','y','g','b']

plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()

feedback=

['Good','excellent','Perfect','Ok'] slices=[4,10,3,8] color=['y','r','b','g']

plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()
<img width="705" height="689" alt="image" src="https://github.com/user-attachments/assets/c2c254c4-bc93-4fc4-a6c3-8ff176b50670" />

x = [1, 2, 3, 4, 5]

y1 = [10, 12, 14, 16, 18]

y2 = [5, 7, 9, 11, 13]

y3 = [2, 4, 6, 8, 10]

plt.fill_between(x, y1, color='blue')

plt.fill_between(x, y2, color='green')

plt.plot(x, y1, color='red')

plt.plot(x, y2, color='black')

plt.legend(['y1','y2'])

plt.show()
<img width="619" height="358" alt="image" src="https://github.com/user-attachments/assets/51b05356-55d3-4492-95e9-ea6a118fd3e7" />

height = [10, 24, 36, 40, 5]

names = ['one', 'two', 'three', 'four', 'five']

c1=['red', 'green']

c2=['b', 'g']

plt.bar (names, height, width=0.8, color=c1)

plt.xlabel('x - axis')

plt.ylabel('y - axis')

plt.title('My bar chart!')

plt.show()
<img width="548" height="401" alt="image" src="https://github.com/user-attachments/assets/ab5ce92b-3999-4593-861a-e7514fbd5d30" />

x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]

plt.hist(x, bins = 10, color='blue', alpha=0.5)

plt.show()

<img width="532" height="349" alt="image" src="https://github.com/user-attachments/assets/21259ef7-d475-424f-97e3-98e83ac53bfe" />

np.random.seed(0)

data=np.random.normal(loc=0, scale=1, size=100)

data
<img width="637" height="371" alt="image" src="https://github.com/user-attachments/assets/54c1ccd5-50ed-4856-a792-df0904465a4b" />

fig, ax= plt.subplots()

ax.boxplot(data)

ax.set_xlabel('Data')

ax.set_ylabel('Values')

ax.set_title('Box Plot')
<img width="612" height="425" alt="image" src="https://github.com/user-attachments/assets/b69edb2d-dfeb-40f5-9d13-f32e8e56ff54" />


 

# Result:
 Perform Data Visualization using matplot python library was implemented successfully.
