---
published: true
---
## Linear Combination and Spans

This laboratory activity aims to implement the principles and techniques of representing linear combinations in the 2-dimensional plane. This also aims to visualize spans using vector fields in Python and to perform vector field operations using scientific programming.

The practices of the activity include combining linear scaling and the addition of a vector. This activity teaches and implies the techniques of representing linear combinations in the 2-dimensional plane and visualizing spans using vector fields in python. Some functions were used such as np.arange() function that returns evenly spaced values within a given interval [1], plt.scatter() function that makes the plotting of the x and y components of a vector into a plane faster [2], plt.axhline() and plt.axvline() functions that adds a horizontal and vertical line across the axes [3][4], np.meshgrid() function that returns coordinate matrices from coordinate vectors [5]. The deliverables of the activity are to provide a linear equation and vector form of the linear combination. It was achieved by providing random values to be used in the equations and the vector form of the linear combination. 

![Figure 1]({{site.baseurl}}/images/LAB3.1.jpg)

Activity 1 Flowchart

![Figure 2]({{site.baseurl}}/images/LAB3.2.jpg)

Activity 2 Flowchart

The result of the two activities done by implementing the principles and techniques of representing combinations in the 2-dimensional plane and visualizing spans using vector fields by performing operations using scientific programming was presented in this section.

![Figure 3]({{site.baseurl}}/images/LAB3.3.jpg)

The code snippet above shows the code of block created to show the linear combination visualization. It was achieved by first creating 3 different arrays of vectors and arranging 3 different scalar values by using the np.array() function and np.arrange() function. The step used in 3 different scalars is 0.5. The linear combinations are created by multiplying the scalar values to the unit vectors or the individual vectors. Lastly, these linear combinations in 1 vector were plotted into a 2-dimensional plane using the plt.scatter() function.

![Figure 4]({{site.baseurl}}/images/LAB3.4.jpg)

The Figure above shows the output of 3 linear combinations in 1 vector. Each combination intersects in the origin and makes a line and it can be observed that they are not linearly dependent on each other.


## You can access the code here:

[Laboratory 3 Repository](https://github.com/RovilSurioJr/Laboratory-3)
