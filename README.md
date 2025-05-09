Check-In #3 (4-21-25) -- Pseudo Rubric

Concept 
* Although I am not finished, I am able to complete my project in code. I am interested in my data analysis task because I will be able to reuse it in the future. 

File Structure 
* I have my documentation file (README.md), an unfinished required packages file (requirements.md), my references (works_cited.md), my unfinished test file (test.py), and my main script (main.py). My repository describes my project well: "bcog-final-abberzip-data-analysis." I definitely have room for improvement in my file organization, but the bare bones are at least there.

Project Description 
* My project descriptions are contained both in this markdown file and in markdown cells in the Jupyter notebook itself. 

Approach 
* I use libraries such as numpy and pandas, which are relevant tools discussed in class.
* I create functions and properly implement them

Project Code 

* I use appropriate variable types
* I use appropraite code constructs
* I organize my code into functions (there will be at least 3)
* Although currently unfinished, I will ensure my code will execute
* I use a modular organization (i.e. I use a main function to run everything)

Code Style 
* I use blank lines to separate code elements and logical structure
* I use good indentation andn spacing
* Although currently unimplemented, I will use idiomatic Python (e.g., list comprehensions where appropriate, etc.)
* I use descriptive names
* I follow Pythonic naming conventions

Code Documentation
* Although currently unimplemented, I will be sure to include user documentation, such as docstrings and/or type hinting for custom classes, functions, and methods
* I include appropriate comments within the code

Code Tests
* I will organize my functions into a test file and then into a test folder, and use pytest to make sure the code executes. 


My (revised) program will be an analysis program for the data generated from a Psychopy experiment explained further below. I hope to analyze mousetracking data and response times as the main dependent variables. I plan to use a Jupyter notebook to organize everything and explain the context and motivations behind the original experiment. 
* Context summary: The AbberZip project is meant to examine the cognitive processes underlying language learning, more specifically, the           thought processes involving learning generalizations and exceptions. The researcher behind the project (Dr. Karina Tachihara) hypothesizes that generalizations become suppressed over time when presented with exceptions (cf. exceptions simply becoming more easily-retrieved and generalizations remaining at the same retrieval level). For example, the Spanish word "el mapa" is an exception, because Spanish words ending in "a" are usually feminine, and would typically carry the article "la." 
* Mousetracking is used specifically to investigate the effect of lures. If an (incorrect, generalized) stimuli attracts the user before they move their mouse towards the correct stimuli, we can assume that generalizations are still playing an effect on the user's psyche. As the attraction towards the lure decreases, it can be assumed that the exception retrieval rate is beating out that of the generalization. The image below will present a visual example of the calculations I will be making to analyze the lure stimuli's effect.

<img width="186" alt="Screenshot 2025-04-11 at 15 03 06" src="https://github.com/user-attachments/assets/1dcf8f3c-ea7a-4d46-95aa-176b738a7740" />

* Please visit this link for more information about the original project: https://escholarship.org/content/qt82x8c04s/qt82x8c04s_noSplash_58ab61cf9074d73a890585be5e003c37.pdf?t=sgiuiq 

In terms of functions & methods and their parameters, I'd ideally like to have multiple functions that will use pandas and numpy to create various dataframes and plots to model the data (similar to what we did in lab_15 and homework_15). However, my project will incorporate more complexity: 
* There will be more data and variables to organize (trial count, reaction times, accuracy, x and y positions, scores, etc.)
* I will be examining the mousetracking data with the goal of analyzing and plotting the mouse movements
* I will be formatting everything using a Jupyter notebook

This program is useful because it provides a way to both explain the context and motivations behind the experiment and analyze the findings--all in one organized space: the Jupyter notebook. I hope to reuse the code I write for this project in future research projects to present my conclusions.    

I will be using numerous .csv data files as input. As mentioned in the Zoom meeting, the data used will have been generated from the previous experimental runs of AbberZip.  

There are 3 main collections of data I will be using: 
* clickData (used to collect accuracy)
* trackAllData (used to collect all mousetracking data)
* runInfo (used to collect specific trial information, such as block, trialCt, etc.)

The column headings will appear in the data sheets in the orders listed below. 

Each ClickData file will be formatted as such: 
     
     trialCt = int
     rt1 = float
     accuracy = bool 
     rt2 = float 
     pos_x = float 
     pos_y = float 
     rt3 = float
     pos_x = float 
     pos_y = float 
     score = int

Each trackAllData file will be formatted as such: 

     trialCt = int
     rt = float 
     pos_x = float
     pos_y = float

Each runInfo file will be formatted as such: 

     blockNum = int
     trialNum = int
     whichLeft = bool
     
