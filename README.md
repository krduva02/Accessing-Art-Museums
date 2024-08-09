# Accessing Art Museums
## Comparing Art Museum Admission Costs to Local Income Data
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/30/Metropolitan_Museum_of_Art_%28The_Met%29_-_Central_Park%2C_NYC.jpg/1280px-Metropolitan_Museum_of_Art_%28The_Met%29_-_Central_Park%2C_NYC.jpg" alt="Metropolitan Museum of Art" width="500" height="300">

## Overview
As art museums continue to market accessibility and the value of experiencing visual art, costs of admission continue to rise, often past what is accessible to the community in which the museum is based. This project aims to evaluate the economic accessibility of art museums in the United States by comparing costs of admission to income data of the local community.

## Data

The following data sets are used in this project:
1. US Art Museums (CSV) - Art museums in the United States with data points including website, city, state, ZIP Code, and cost of admission
2. 2022 Census Income Data (CSV) - [Income data by ZIP Code from the United States Census Bureau](https://data.census.gov/table?q=S1903:%20Median%20Income%20in%20the%20Past%2012%20Months%20(in%202022%20Inflation-Adjusted%20Dollars)&g=010XX00US$8600000)

### Project Structure
---

The project is organized as follows:

- **Data Exploration:** Jupyter notebooks to explore the dataset.

- **Analysis:** Using Python with the Pandas package to clean the data.

- **Visualizations :** Using Matplotlib to visualize my findings. 

## Features Utilized for the project

  | Feature        | Description                           |
  |----------------|---------------------------------------|
  | Read TWO data files| Used 2 CSV files          |
  | Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.      | Cleaned my data and merged them with pandas. Then calculated stats from various data points for the new set. |
  | Make 3 matplotlib visualizations to display your data. | Made various graphs with matplotlib to show data. |
  | Utilize a virtual environment      | Made a venv for this project to keep my computer clean. |
  | Notate your code with markdown cells in Jupyter Notebook | Included in my code, you will find clear notes describing each code block. |

## Getting Started

To run this project, follow these steps:

1. Clone the repository: `git clone https://github.com/krduva02/Accessing-Art-Museums`
2. Install the necessary dependencies: `pip install -r requirements.txt`
3. Explore the Jupyter notebooks or scripts in the respective folders.

##  Virtual Environment Instructions
---
1. After you have cloned the repo to your machine, navigate to the project 
folder in GitBash/Terminal.
1. Create a virtual environment in the project folder. 
1. Activate the virtual environment.
1. Install the required packages. 
1. When you are done working on your repo, deactivate the virtual environment.

Virtual Environment Commands

| Command | Linux/Mac | GitBash |
|---------|-----------|---------|
| Create | `python3 -m venv venv` | `python -m venv venv` |
| Activate | `source venv/bin/activate` | `source venv/Scripts/activate` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |

## Data Interpretation
The data shows that presumed offenders of excessively high admission prices, particularly museums in large cities like New York and Los Angeles, actually trend fair when considering relation to income of the local area. Mid-size cities like Akron (OH), Louisville (KY), and Peoria (IL) are a few of the cities with the largest discrepancy between art museum admission prices and median income of the local area. This leads to the question of whether there exists an unspoken national standard for art museum admissions, which creates the larger discrepancy for mid-size cities with lower income ($20 in Los Angeles is not the same as $20 in Louisville, KY). Small towns and rural areas trend toward the most accessible museums at $0 per admission, possibly due to community efforts and less reliance on tourism. Moving forward, there is more work that can be done on this project to investigate the trends of art museum admission prices.

Ideas for continuing the project:
- Develop "community sets" so Index is not tied exclusively to ZIP code, rather to a combination of ZIP codes. This is particularly important in larger cities where multiple ZIP codes within commuting range to the museum may exist.
- Show change over time by incorporating historic general admission prices and changes in median income.
- Create a dashboard that can be filtered by users to pull specifically requested information.