# Using the Monte Carlo Method to find $\pi$ and other quantities
> Nathan Lee

In this repository, we will be using the Monte Carlo Method to determine the approximate values of the following:
* [the area of a unit circle](https://github.com/naatthaan/monte_carlo/blob/main/area_of_circle.ipynb)
* [the volume of a unit sphere](https://github.com/naatthaan/monte_carlo/blob/main/volume_of_sphere.ipynb)
* [the circumference of a unit circle](https://github.com/naatthaan/monte_carlo/blob/main/circumference_of_circle.ipynb)
* [the surface area of a unit sphere](https://github.com/naatthaan/monte_carlo/blob/main/surface_area_of_sphere.ipynb)

The Monte Carlo Method uses repeated random sampling to obtain numerical results, and in particular, can be used to estimate the value of $\pi$. Using Python, we can generate random points inside of a square circumscribed by a circle of radius 1. After counting the number of points inside of the circle, we can find the ratio of the number of points inside of the circle and the number of points in total to find an estimated value of $\pi$, i.e., the area of a unit circle.

We can also use similar methods to find the volume of a sphere, the circumference of a circle, and the surface area of a sphere. For a very large number of randomly generated points, say, 1,000,000+, the Monte Carlo Method will provide an accurate estimate of these results - the more points there are, the more accurate the estimate will be. We can just use counting to obtain these geometric quantities, rather than using formulas.
