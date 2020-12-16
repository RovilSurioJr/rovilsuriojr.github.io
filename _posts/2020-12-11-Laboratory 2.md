---
published: true
---
## Plotting Vector using NumPy and MatPlotLib

This laboratory activity aims to implement the principles and techniques of plotting a vector with the use of the MathPlot library for creating visualizations in Python and the NumPy library for fast operations on arrays.

The practices of the activity include creating arrays and plotting of vectors. This teaches and implies the techniques of manipulating arrays and plotting of vectors. The deliverables of the activity are to provide an array and formulas needed to completely plot the vectors. Lastly, it was achieved by reading the documentation of the functions.

The results from the activities done by implementing the principles and techniques of representing the vectors through plotting using the MathPlot library and NumPy library to manipulate arrays were presented in this section. The first activity was focused on providing necessary formulas to complete the code while the second activity was all about code analysis and how to transform a project that lacks coding conventions into a well-created project that follows coding convention. Lastly, the third activity was about understanding the relationship of each vector used to represent data.

![Figure 1]({{site.baseurl}}/images/LAB2.1.jpg)

![Figure 2]({{site.baseurl}}/images/LAB2.2.jpg)

Figures 1 and 2 show the code executed and the sample output or the Philippine Eagle Flight Plotter. The task was to fill in the necessary codes to make the function works. Three 2-D arrays were created which is assigned into dist1, dist2, and dist3 variable from the long and lat variable which generates random integers. In computing the total distance, the computation of three arrays was performed in the dist_total variable therefore, it holds the value of the summation of dist1, dist2, and dist3. The magnitude of the displacement was computed next which is assigned into disp variable and the L2 norm was used which is calculated as the square root of the sum of the squared vector values and executed using the function np.linalg.norm [1]. The angle of the displacement was calculated next using the equation provided \arctan{\ \left(\frac{y}{x+\alpha}\right)} wherein Figure 1 is equal to np.arctan(dist_total[1]/(dist_total[0]+alpha)) and it was assigned to theta variable wherein after getting the result, the value of theta was converted into degrees using the code provided np.degrees from the Numpy library.
	
	Proceeding to the plotting of vectors, plt.quiver was used because it plots a 2D field of arrows based on the parameter provided [2]. As shown in Figure 1, the first vector was plotted using the line of code that includes plt.quiver (0,0, dist1[0], dist1[1]) this is the parameter used to identify the location of the arrow, the 0,0 is the origin of the tail of the arrow while the dist1[0] and the dist[1] is the head of the arrow. The code that follows this is for the modification of how the arrow will look and the code needed for the legend of the graph. The same concept was used in plotting the second vector and for the third, the addition of the first vector and the second is used as the origin of the tail and still used its value dist3[0] and dist3[1] for its arrowhead. The displacement was plotted using the values of variable dist_total and in the same line of code, for the legend, it includes the variable theta or the degree. The plt.legend() shows the legend at the right top side of the graph as shown in Figure 2 and the plt.show() show what is inside the plt or the vectors plotted in the canvas. Lastly, the track_eagle(make_figs=True) is the one that confirms if the saving of the graph into an image will be executed so, if it was set to False then no image will be saved.











## Note:

The advantage of using python is that it has a lot of documentation and its community is big so there are a lot of tutorials. Also, comparing to other languages, Python programming language is more flexible in terms of syntax. Likewise, in Jupyter Notebook, it is extremely useful in data science because of its capability to produce such graphs and vectors which is a good representation of many things.

## You can access the code here:

[Laboratory 2 Repository](https://github.com/RovilSurioJr/Laboratory-2)
