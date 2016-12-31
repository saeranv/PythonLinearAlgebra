#Negombo

Negombo is a pure python vector library for Rhino3d/Grasshopper3d - built on top of a modified version of the Linear Algebra course from Udacity. While Rhino3D comes with its own library of basic linear algebra methods for working with vectors, rays, lines, planes - it misses operations that I need for more sophisticated generative algorithms[1], and these methods are usually constrainted to two or three dimensions[2]. 

Negombo has three goals. First is to build a more abstract n-dimensional linear system that allows you to identify solutions in n-dimensions. Secondly, it's a place to consolidate in a more rigorous way the random linear algebra methods I sometimes write up to fill gaps in the Rhino3d library. Thirdly, it's an  excuse for me to strengthen my linear algebra knowledge.      

[1] Finding the intersection of a parametric ray with a line segment.
[2] Numpy and scipy are the obvious alternatives to this, but they aren't easily compatible with IronPython.


##State of Development
16123: Finished vector, line, plane, linear system, parametrization and hyperplane classes. 

##Next Steps
* Add parametric ray/line interesection class to reference
* Integrate Rhino3d vectors and bibl vector into initialzation of classes
* Create transformation matrix reference
 