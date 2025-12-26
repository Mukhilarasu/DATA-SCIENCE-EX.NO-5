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
```
import numpy as np
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
```
<img width="758" height="475" alt="image" src="https://github.com/user-attachments/assets/b26015ba-b212-46a9-953c-68cfde66af90" />

<img width="734" height="487" alt="image" src="https://github.com/user-attachments/assets/d9d82eb2-ea85-4d53-9544-af1b1a411442" />

```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```

<img width="734" height="470" alt="image" src="https://github.com/user-attachments/assets/a8f291fd-7e83-4947-a76b-b6db3f5a6036" />

<img width="772" height="511" alt="image" src="https://github.com/user-attachments/assets/807423e2-72fa-4055-a7a8-f1ee8f799371" />

```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

<img width="661" height="464" alt="image" src="https://github.com/user-attachments/assets/5bea2ea5-ccdf-4ceb-a107-daaf8738a95e" />

<img width="636" height="472" alt="image" src="https://github.com/user-attachments/assets/82f03b91-bfec-4091-9945-fd477e7b4d87" />

```
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
```

<img width="743" height="456" alt="image" src="https://github.com/user-attachments/assets/1607c0b4-af0b-465c-bdd9-98a31d89358c" />

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('bar chart')
plt.show()
```

<img width="756" height="500" alt="image" src="https://github.com/user-attachments/assets/440e11eb-85fc-49ea-ab55-c257f0a25242" />

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```

<img width="652" height="457" alt="image" src="https://github.com/user-attachments/assets/6c23ef44-e3f2-41de-8115-c8f0f84aaa03" />

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="794" height="392" alt="image" src="https://github.com/user-attachments/assets/975c4dcd-518a-4d5b-8e26-ae806437b236" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="847" height="543" alt="image" src="https://github.com/user-attachments/assets/05f0f6fa-5934-4673-8393-a30f4bc62246" />

# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
