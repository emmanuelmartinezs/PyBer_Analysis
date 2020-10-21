# PyBer Analysis
**Data Analyst at PyBer**
Create line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib. And determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.

## Overview of Project
PyBer CEO has given you and your manager a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. 

> Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

1. ***Deliverable 1***: A ride-sharing summary DataFrame by city type
2. ***Deliverable 2***: A multiple-line chart of total fares for each city type
3. ***Deliverable 3***: A written report for the PyBer analysis [`README.md`](https://github.com/emmanuelmartinezs/PyBer_Analysis). 

## Resources and Before Start Notes:

* Data Source: `PyBer_Challenge_starter_code.ipynb` named later as `PyBer_Challenge.ipynb`
* Data File: file.csv
* Software: Matplotli 3.2.2, Python 3.9, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas

For more information, read the [`Documentation on Python data typess`](https://docs.python.org/3.6/library/stdtypes.html#numeric-types-int-float-complex). 

## Check the Version of Matplotlib
Before we get started on any project, it's good practice to make sure we have the latest version of the software we'll be using. Because we'll be using Matplotlib, let's check to make sure we have version 3.1.0 or greater
Follow the instructions below for your operating system.

**Check the Version on the Command Line in macOS or Windows**
To begin, launch the command line and activate the PythonData environment.

To activate the **PythonData** environment on the command line, type `conda activate PythonData`.

**macOS look similar to this:**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/Pyvr1.PNG?raw=true)


**Windows look similar to this:**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/Pyvr2.PNG?raw=true)


At the Python prompt ( >>>), type import matplotlib and press Enter to import Matplotlib.

Next, to check the version of Matplotlib, type `matplotlib.__version__` (there are two underscores before and after "version") and press Enter
The output should be 3.1.0 or greater.

**Extra Note:** 

To update Matplotlib for your development environment; with your PythonData environment activated, type `conda install -c conda-forge matplotlib` at the command prompt and press Enter.

In Jupyter Notebook, create a new file if one hasn't been created. Add the following code to a new cell.

**From Anaconda Terminal:**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/jpvr1.PNG?raw=true)

**From Jupyter Notebook Data:**

![name-of-you-image](https://github.com/emmanuelmartinezs/PyBer_Analysis/blob/main/Resources/Images/jpvr2.PNG?raw=true)


For more information about the latest Matplotlib version, see the Matplotlib documentation [Links to an external site.](https://matplotlib.org/3.1.0/index.html). 


**Check the Version in Jupyter Notebook**
Alternatively, you can check the version of Matplotlib in Jupyter Notebook. To do that, follow these directions

To start Jupyter Notebook, navigate to the Class folder on your computer using the command line or Anaconda prompt.

Activate the PythonData environment if it's not activated. Type and run `jupyter notebook`.



## Analysis and Challenges
In this project, our final Python script will need to be able to deliver the following information when the script is run: 

1. Total number of votes cast
2. A complete list of candidates who received votes
3. Total number of votes each candidate received
4. Percentage of votes each candidate won
5. The winner of the election based on popular vote

#### Our Challenge Data Background
> After giving you an overview of the election audit tasks, we wants to go over the steps required in detail. Showing you a technique commonly used by programmers to write steps of their code, which is called `pseudocode`. Pseudocode will make the audit easier to present to nontechnical colleagues and stakeholders.

To facilitate the design process, programmers use `pseudocode` to create models or flowcharts for their programs. 
Pseudocode is like a roadmap of what you think your code will look like or the steps you'll take to complete the task at hand.

Pseudo means **"fake,"** so pseudocode is essentially fake code. Pseudocode is an informal language that has no syntax rules and is not meant to be executed. The point of using pseudocode is to focus on the overall design of the program.

> Here some **Python Arithmetic Operators**, **Data Types** and **Reserve Keys** to remember;

**Python Arithmetic Operators**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Python_Arithmetic_Operators.PNG?raw=true)

**Python Data Types**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Python_Data_Types.PNG?raw=true)


**Python Reserve Keys**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Python_Reserve_Keys.PNG?raw=true)

## Deliverable 1a: Candidate Results
### Deliverable Requirements:

1. Total Votes in the election are printed to the terminal.
2. Each candidate’s total votes and percentage of votes are printed to the terminal.
3. The winner of the election, winning vote count, and winning percentage of votes are printed to the terminal.
 
### Results with detail analysis:

**1. Total Votes in the election are printed to the terminal**

> Image with `Python` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Total-Votes-in-the-election-are-printed-to-the-terminal.PNG?raw=true)


**2. Each candidate’s total votes and percentage of votes are printed to the terminal.**

> Image with `Python` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Each-candidates-total-votes-and-percentage-of-votes-are-printed-to-the-terminal.PNG?raw=true)


**3. The winner of the election, winning vote count, and winning percentage of votes are printed to the terminal.**

> Image with `Python` Code below.


**Code and Image - The winner of the election**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/The-winner-of-the-election.PNG?raw=true)


**Code and Image - The winning vote count**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/The-winning-vote-count.PNG?raw=true)


**Code and Image - The winning percentage of votes**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/The-winning-percentage-of-votes-are-printed-to-the-terminal.PNG?raw=true)


### Deliverable 1b: County Results
### Deliverable Requirements:

1. Each county and its total vote count are printed to the terminal.
2. Each county and its percentage of the total votes are printed to the terminal.
3. The county with the largest number of voters is printed to the terminal.

### Results with detail analysis:

**1. Each county and its total vote count are printed to the terminal.**

> Image with `Python` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Each-county-and-its-total-vote-count-are-printed-to-the-terminal.PNG?raw=true)


**2. Each county and its percentage of the total votes are printed to the terminal.**

> Image with `Python` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Each-county-and-its-percentage-of-the-total-votes-are-printed-to-the-terminal.PNG?raw=true)


**3. The county with the largest number of voters is printed to the terminal.**

> Image with `Python` Code below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/The-county-with-the-largest-number-of-voters-is-printed-to-the-terminal.PNG?raw=true)

## Deliverable 2: Election Candidate Results Saved to a Text File
### Candidate Results Deliverable Requirements:
You will earn a perfect score for Deliverable 2 by completing all requirements below:

1. Total Votes in the election are saved in the `election_results.txt` file.
2. Each candidate’s total votes and percentage of votes are saved in the `election_results.txt` file. 
3. The winner of the election, winning vote count, and winning percentage of votes are saved in the `election_results.txt` file. 
 
### Results with detail analysis:
> Using your knowledge of writing data to a text file, write the winning candidate results and the county election results to the `election_results.txt` file.

**1. Total Votes in the election are saved in the `election_results.txt` file.**

> Image over `election_results.txt` print below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Total-Votes-in-the-election-are-saved-in-the-election_results-txt-file.PNG?raw=true)


**2. Each candidate’s total votes and percentage of votes are saved in the `election_results.txt` file.**

> Image over `election_results.txt` print below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Each-candidates-total-votes-and-percentage-of-votes-are-saved-in-the-election_results.txt-file.PNG?raw=true)


**3. The winner of the election, winning vote count, and winning percentage of votes are saved in the `election_results.txt` file.**

> Image over `election_results.txt` print below.


**Code and Image - The winner of the election on txt file**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/The-winner-of-the-election-saved-in-the-election_results.txt-file.PNG?raw=true)

**Code and Image - The winning vote count on txt file**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/The-winner-vote-count-saved-in-the-election_results.txt-file.PNG?raw=true)

**Code and Image - The winning percentage of votes on txt file**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/The-winning-percentage-of-votes-saved-in-the-election_results.txt-file.PNG?raw=true)


## Election County Results Saved to a Text File
### County Results Deliverable Requirements:
You will earn a perfect score for Deliverable 2 by completing all requirements below:

1. Each county and its total vote count are saved in the `election_results.txt` file.
2. Each county and its percentage of the total votes are saved in the `election_results.txt` file.  
3. The county with the largest number of voters is saved in the `election_results.tx`t` file. 
 
### Results with detail analysis:
> Using your knowledge of writing data to a text file, write the winning candidate results and the county election results to the `election_results.txt` file.

**1. Each county and its total vote count are saved in the `election_results.txt` file.**

> Image over `election_results.txt` print below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Each-county-and-its-total-vote-count-are-saved-in-the-election_results.txt-file.PNG?raw=true)


**2. Each county and its percentage of the total votes are saved in the `election_results.txt` file.**

> Image over `election_results.txt` print below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/Each-county-and-its-percentage-of-the-total-votes-are-saved-in-the-election_results.txt-file.PNG?raw=true)


**3. The county with the largest number of voters is saved in the `election_results.tx` file.**

> Image over `election_results.txt` print below.


**Code and Image**

![name-of-you-image](https://github.com/emmanuelmartinezs/Election_Analysis/blob/main/Resources/The-county-with-the-largest-number-of-voters-is-saved-in-the-election_results.txt-file.PNG?raw=true)


## Deliverable 3: Analysis of the Election Audit
### 1) Overview of Election Audit:
> Explain the purpose of this election audit analysis:

A Colorado Board of Elections employee has given you the following task to complete the election audit of a recent local congressional election.

* Calculate the total number of votes cast.
* Get a complete list of candidates who received votes.
* Calculatae the total number of votes each candidate received.
* Calculate the percentage of votes each candidate won.
* Determine the winner of the election based on popular vote.

After giving you an overview of the election audit tasks, we wants to go over the steps required in detail. Showing you a technique commonly used by programmers to write steps of their code, which is called `pseudocode`. Pseudocode will make the audit easier to present to nontechnical colleagues and stakeholders.

In this project, our final Python script will need to be able to deliver the following information when the script is run:

* Total number of votes cast
* A complete list of candidates who received votes
* Total number of votes each candidate received
* Percentage of votes each candidate won
* The winner of the election based on popular vote


### 2) Election-Audit Results:
> Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

* How many votes were cast in this congressional election?

> - **Total Votes Cast** in this congressional election was **369,711** 

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
> ***County Votes:***
> - **Jefferson** county has `10.5%` total percentage with a total votes of **38,855**
> - **Denver** county has the `82.8%` total percentage with a total votes of **306,055**
> - **Arapahoe** county has `6.7%` total percentage with a total votes of **24,801**

* Which county had the largest number of votes?
> ***County with Largest Number of Votes:***
> - **Denver** county has the largest number total of **306,055**
> - In addition, **Denver** county has the total votes percentage of `82.8%`  
> - **Denver** county is the Largest County Turnout

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
> ***Candidate Percentage of Votes:***
> - **Charles Casper Stockham** candidate has `23.0%` total percentage with a total votes of **85,213**
> - **Diana DeGette** candidate has the `73.8` total percentage with a total votes of **272,892**
> - **Raymon Anthony Doane** candidate has `3.1%` total percentage with a total votes of **11,606**

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
> ***Election Results:***
> - **Diana DeGette** won the election, with a total votes of **272,892**
> - In addition, **Diana DeGette** has the total percentage votes of `73.8%`  
> - **Diana DeGette** is the Winner!
