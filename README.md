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

# Coding :

Matplotlib:
```
import matplotlib.pyplot as plt
import numpy as np

x = np.arange(20, 50)
y = np.arange(50, 80)
a = np.arange(80, 110)
b = np.arange(110, 140)

plt.scatter(x, y, c='b')
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Graph in 2D')
plt.show()

```

2D Diagram:

```

plt.plot(x, y, 'b*', linestyle='dashed', linewidth=1, markersize=10)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('2D Diagram')
plt.show()

```
```

plt.subplot(3, 2, 1)
plt.plot(x, y, 'r.')
plt.subplot(3, 2, 2)
plt.plot(x, y, 'b*')
plt.subplot(3, 2, 3)
plt.plot(x, y, 'yo')
plt.subplot(3, 2, 4)
plt.plot(x, y, 'g*')
plt.subplot(3, 2, 5)
plt.plot(x, y, 'r.--')
plt.subplot(3, 2, 6)
plt.plot(x, y, 'g*')

```
```

x = np.arange(1, 10)
y = x * x

plt.plot(x, y, 'ro')
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Graph')
plt.show()

```

Sinewave and Coswave:

```

x = np.arange(0, 6 * np.pi, 0.1)
y_sin = np.sin(x)
y_cos = np.cos(x)

plt.subplot(2, 1, 1)
plt.plot(x, y_sin, 'y-')
plt.title('Sine Wave')
plt.show()

plt.subplot(2, 1, 2)
plt.plot(x, y_cos, 'b-')
plt.title('Cos Wave')
plt.show()

```

Bargraph:

```

x = [2, 4, 6]
y = [3, 5, 7]
x2 = [12, 14, 16]
y2 = [13, 15, 17]

plt.bar(x, y, color='b')
plt.bar(x2, y2, color='y')
plt.title("Bar Graph")
plt.show()

```

Histogram:

```

a = np.array([34, 65, 79, 90, 82, 10, 94, 39, 34, 92, 72, 49])
plt.hist(a)
plt.title("Histogram")
plt.show()

```

BoxPlot:

```

a = [np.random.normal(0, std, 100) for std in range(1, 4)]
plt.boxplot(a, vert=True, patch_artist=True)
plt.show()

plt.boxplot(a, vert=False, patch_artist=False)
plt.show()

```

Pie Chart:

```

labels = ['RCB', 'CSK', 'MI', 'SRH']
sizes = [250, 250, 250, 250]
colors = ['red', 'yellow', 'blue', 'orange']
explode = (0.4, 0, 0, 0)

plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%.1f')
plt.axis('equal')
plt.show()

```

Output : 

<img width="630" height="457" alt="image" src="https://github.com/user-attachments/assets/b3968f4c-faf7-48b3-baae-a2d65ab7c654" />
<img width="638" height="495" alt="image" src="https://github.com/user-attachments/assets/d2c16aae-228f-4d35-bcfc-52abf1174e3f" />
<img width="654" height="478" alt="image" src="https://github.com/user-attachments/assets/69195afc-63c6-433d-9bba-180539c0bec5" />
<img width="626" height="466" alt="image" src="https://github.com/user-attachments/assets/9eb3d161-98e3-40db-8935-e75bcaef6251" />
<img width="678" height="519" alt="image" src="https://github.com/user-attachments/assets/a7040d8b-d057-4cd4-b266-ecb9a77b948a" />
<img width="667" height="511" alt="image" src="https://github.com/user-attachments/assets/6aef4774-71ee-4524-a344-c229bbb7c519" />
<img width="631" height="488" alt="image" src="https://github.com/user-attachments/assets/cb5a8b8e-acdb-4bb8-9ce6-f29145e9b586" />
<img width="589" height="484" alt="image" src="https://github.com/user-attachments/assets/81bf28f6-a1cd-44c2-beee-46f7c5e8d6a3" />
<img width="457" height="420" alt="image" src="https://github.com/user-attachments/assets/5c909f8c-9ced-4f7e-8c0f-c53115d87f26" />



# Result:
 Include your result here
