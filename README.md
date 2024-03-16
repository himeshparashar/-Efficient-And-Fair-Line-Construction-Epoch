# Efficient and Fair Line Construction Project

## Overview
This project aims to optimize the construction of gas pipelines to service a set of houses, minimizing costs while ensuring equitable service distribution. Developed by the Kasukabe Defense Force team, it utilizes the California housing dataset to explore three key objectives: constructing an efficient line, a fair line, and multiple efficient lines to serve all houses based on their geographical coordinates.

## Team: Kasukabe Defense Force
This project is brought to you by the Kasukabe Defense Force, a team committed to leveraging computational methods for real-world applications. Our team members, who have contributed their expertise to this project, include:

- [Himesh Parashar](https://github.com/himeshparashar)
- [Prateek Choudhary](https://github.com/Prateekcgudu1305)
- [Yuvraj Singh](https://github.com/YuvvrajSingh)
- [Swapnil Gadkari](https://github.com/swapnilgad)


## Objectives
1. **Efficient Line**: Minimize the sum of squared distances from all houses to the pipeline.
2. **Fair Line**: Minimize the maximum distance from any house to the pipeline.
3. **Multiple Efficient Lines**: Optimize service lines for diverse and dispersed housing clusters.

## Dataset
The project utilizes latitude and longitude data from the California housing dataset provided by `sklearn.datasets`.

## Methodology
- **Data Preprocessing**: Standardization of geographical coordinates.
- **Efficient Line Construction**: Application of PCA to find the direction of maximum variance.
- **Fair Line Construction**: Iterative adjustment strategy to minimize the maximum distance from houses to the line.
- **Multiple Efficient Lines**: Employing k-means clustering followed by PCA within each cluster.

## Installation
Clone this repository to your local machine:
