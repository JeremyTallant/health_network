# Partnering to Protect You from Peril
## Description
Have you ever wondered who keeps an eye on your favorite restaurants to make sure your food is safe? Or removes old tires from vacant lots before they fill with standing water that could attract mosquitos that spread disease? These tasks are among the services provided by local health departments in the United States. These health departments partner with other health departments to share information and coordinate services, which is especially crucial during public health emergencies. In this project, we will explore the 2016 national network of local health departments and use centrality measures and visualization to identify key health departments nationally, regionally, and locally. Which health departments are most connected? Where are there gaps? What are the characteristics of central health departments?

The data in this project was taken from a survey by the National Association of County and City Health Officials (NACCHO), which you can read about [here](https://www.naccho.org/).
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with R kernel support. Make sure to install the required packages such as `tidyverse`. You can do this by running the following commands in a code cell within the notebook:
``` r
install.packages("tidyverse")
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the R kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Install the R kernel for Jupyter Notebook by running the following commands in your R console:
``` r 
install.packages("IRkernel")
IRkernel::installspec()
```
After completing the installation, launch Jupyter Notebook, navigate to the folder containing the notebook file, and open it to begin running the analysis.
## Contents
1. **Ebola, hurricanes, and forest fires, oh my:** Import the network ties and the characteristics of each health department in the network.
2. Cleaning up the network object
3. Getting to know the network
4. Connections facilitating coordination nationwide
5. Connections for regional coordination
6. Which health departments are central in Texas and Louisiana?
7. Visualizing the central health departments
8. What about state-level networks during emergencies?
9. Are central health departments urban?
10. Which health departments have high betweenness?