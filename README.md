# Nearest Points Finder
This project implements a Python tool to compute distances between points using different norms (Manhattan, Euclidean, and Cosine distance) and to find the nearest points between two sets of points based on these distance metrics.


# Overview
This project provides a Python-based solution to calculate the distance between points using various norms, including Manhattan, Euclidean, and Cosine distance. It also includes functionality to find the nearest points between two sets of points based on these distance metrics.

The project can be useful for tasks in machine learning, data science, and geometric computations, where it is necessary to measure the similarity or proximity between data points in high-dimensional spaces.

# Features
Distance Calculation: Compute distances between points using different norms:
Manhattan Distance (L1 norm): Measures distance by summing the absolute differences along each dimension.
Euclidean Distance (L2 norm): The standard straight-line distance in Euclidean space.
Cosine Distance: Measures the cosine of the angle between two points (transformed into distance by subtracting the cosine similarity from 1).
Nearest Point Search: For each point in one array, the tool finds the closest point in another array based on the chosen distance norm.

# Installation
Clone the repository: Clone this project from GitHub to your local machine.
Install dependencies: Ensure you have Python 3.x installed, and install the required dependencies using pip, such as NumPy.

# Usage
This project allows you to input two arrays of points. You can choose the distance metric you want to use, and for each point in the first array, it will find the closest point from the second array.

# Error Handling
The system checks for the validity of the selected norm. If an unsupported norm is passed, an appropriate error is raised, ensuring that only valid norms (Manhattan, Euclidean, or Cosine) are used.

# Customization
Distance Metric: You can customize the distance calculation by selecting from Manhattan (L1), Euclidean (L2), or Cosine distance. This is done by setting the norm parameter to either 1, 2, or 'co' respectively.

Point Sets: The points are passed in as NumPy arrays, allowing for flexibility in working with any number of points in any dimension.
