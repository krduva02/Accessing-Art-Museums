# Accessing Art Museums
## Comparing Art Museum Admission Costs to Local Income Data
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/30/Metropolitan_Museum_of_Art_%28The_Met%29_-_Central_Park%2C_NYC.jpg/1280px-Metropolitan_Museum_of_Art_%28The_Met%29_-_Central_Park%2C_NYC.jpg" alt="Metropolitan Museum of Art" width="500" height="300">


## About
As art museums continue to market accessibility and the value of experiencing visual art, costs of admission continue to rise, often past what is accessible to the community in which the museum is based. This project aims to evaluate the economic accessibility of art museums in the United States by comparing costs of admission to income data of the local community.


## Data Sources
The following data sets are used in this project:
1. US Art Museums (CSV) - Art museums in the United States with data points including website, city, state, ZIP Code, and cost of admission
2. 2022 Census Income Data (CSV) - [Income data by ZIP Code from the United States Census Bureau](https://data.census.gov/table?q=S1903:%20Median%20Income%20in%20the%20Past%2012%20Months%20(in%202022%20Inflation-Adjusted%20Dollars)&g=010XX00US$8600000)

## Setup
The following installations are required for running this project:
 - Python - This project was developed using Python 3.12.4. Installation or upgrades to current versions can be accessed at the [Python website](https://www.python.org/downloads/).
 - Git - This project includes a repository (repo) that requires cloning. Installation of Git can be accessed at the [Git website](https://git-scm.com/downloads).

Follow these steps to run the project on a local machine:

1. **Access and clone repo**

   ```
  https://github.com/krduva02/Accessing-Art-Museums
   ```

2. **Install virtual environment**

 1. After cloning the repo to your machine, navigate to the project folder in GitBash/Terminal.
 2. Create a virtual environment in the project folder.

 On Windows:

 ```
 python -m venv venv
 ```

 On macOS and Linux:

 ```
 python3 -m venv venv
 ```

 3. Activate the virtual environment. `source venv/bin/activate`
 4. Install the required packages. `pip install -r requirements.txt`

 A new virtual environment named `venv` will now be in the current directory.
 
3. **Install required packages**

   Install the required packages by running the following command:

   ```
   pip install -r requirements.txt
   ```

4. **Run the ```Accessing Art Museums.ipynb``` file:**
    - This project was developed using Jupyter Notebook, which was installed in the previous step (installing packages).
    - After opening ```Accessing Art Museums.ipynb```, run all cells in the notebook by selecting **Run All** or run each cell individually by selecting **Execute Cell** at the top left of each cell.
