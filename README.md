### About NoFoodWaste-Metronom Project
The data analysis in this report has been done on one of Metro's department store data for the month january 2020. Due to the limitations of the study, the ultimate goal of this report is not to reach to significant statistical results but to give a fair and true view about the dataset we received. 
However, I have tried to focus on exploring the daily sales in different main product categories to figure out trends and distributions and if possible to find a correlation between sales and shrinkage data. The data science libraries such as Pandas, Seaborn & etc. has helped me a lot in analysing the data and visualizing the results. 
Since we lack sufficient data for shrinkage, a linear correlation could not be derived from the shrinkage and sales data. Moreover, shrinkage values are not derived by an automated process and huge errors can be find in its measurement. Hence, from the trend analysis it can be predicted that the sales go down on Fridays and increas on Mondays in the following weeks because it has troughs & peaks on a regular basis. Considering the fact that real data have extreme values, statistical analyses show us that all of the main product group categories are positively skewed to the right. Also, the spreads of the data in categories such as meat & fish represent that their sales values vary more than other categories such as bread which has the least variations in its sales price. 


### Set up

#### Installing and Configuring Python
* You will need Python 3.* installed on your computer. Go to [the Python website](https://www.python.org/downloads) and find the right download for your OS.

#### Download Anaconda
* Anaconda is a python distribution which includes pretty much everything you need for out-of-the-box data science work.
* Download and install Anaconda (for a Python 3.* version) from [https://www.anaconda.com/download](https://www.anaconda.com/download)

#### Getting the Extra Libraries
* There are a few extra packages you'll need for this . Run the lines below to get everything set up:

```
conda create -n name_of_my_env python==3.7 pandas numpy scipy matplotlib seaborn ipython jupyter

conda activate name_of_my_env
```

#### Downloading the code
You can download the repository zip file or clone the repository.

#### Running the notebooks
* Run the following from the root folder:
`jupyter notebook`
* Then, open the 'NoFoodWaste-Metronom Project' file.



### More Info about the Libraries
* Pandas - Provides data structures and data analysis tools
* SciPy - Ecosystem of libraries useful for math, science, engineering needs
* Numpy - Scientific computing tools
* Jupyter - Allows creation, sharing, and accessing of documents containing live code, text, etc.
* Seaborn - Data visualization
* Matplotlib - Data visualization
* iPython - Used for Python programming in Jupyter notebooks
