# Change Status Reason Prediction Model
A machine learning model that predicts the change status reason of a Cisco network change prior to implementing the network change.
Leveraged a network change management CSV file with approximately 30,000 rows of network change data to train the 
predictive model, enabling the identification of reasons for specific change statuses and the correlation with product types.
- [Powerpoint with more information](https://github.com/hadiplays/Cisco-Change-Status-Reason-Prediction-Model/blob/main/Internship%20Recap%202023.pptx)
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Data](#data)
- [Contact](#contact)

## Installation :floppy_disk:
To install and use the project, you must have the latest version of Python, Anaconda, and Jupyter Notebook installed on your device. Links to both are provided below:
- [Python](https://www.python.org/downloads/)
- [Anaconda](https://www.anaconda.com/)
- [Jupyter Notebook](https://jupyter.org/install)

  - Although having Anaconda is not necessary, it is reccommended to download in order to run our program on a seperate virtual environment. This is to allow easier access to download and delete python libraries without the hassle of directly downloading them to the base environment (aka the local device) and potentially take up space on the memory. To do this, open the Anaconda command line interface and type `conda activate rizzerator`. From here, you would run `jupyter notebook` and locate the directory containing the files. 
  - If Anaconda is not downloaded, run the program on any other IDE of your liking (we reccomend VS Code) :)
  - To install different Python libraries, you can run `pip install` followed by the library you choose to download or, if you downloaded Anaconda, you can run `conda install` followed by the library of your choosing. 
  - Note: some Python libraries might not have `conda install`, so its still fine to run `pip install' while using Anaconda.

## Usage :computer:
After downloading all the necessary tech stack above, you can successfully run the `Change Status Reason Prediction Model.ipynb` file. To do this run each individual block of code in order from top to bottom 
to finalize before you reach the classification models. Run the classification models and review the results that are produced. Data on accuracy, precision, f1 score, and recall will be shown for each model 
as well as their respective confusion matrices.

## Contributing :family:
Others can contribute to the project by:
- Feeding the model more training data in order for it to better predict the correct results.
- Keeping track of any new issues added to the GitHub repository.

## Data :link:
- [NCM-Change Management - Results - CISCO dataset](https://github.com/hadiplays/Cisco-Change-Status-Reason-Prediction-Model/blob/main/NCM-Change%20Management%20-%20Results%20-%20CISCO.xlsx)

## Contact :email:
If you have any questions, concerns, or contributions contact: [Hadi](https://github.com/hadiplays) :construction_worker:
