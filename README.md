My (revised) program will be an analysis program for the data generated from a Psychopy experiment explained further below. I hope to analyze mousetracking data and response times as the main dependent variables. I plan to use a Jupyter notebook to organize everything and explain the context and motivations behind the original experiment. 
* Context summary: The AbberZip project is meant to examine the cognitive processes underlying language learning, more specifically, the           thought processes involving learning generalizations and exceptions. The researcher behind the project (Dr. Karina Tachihara) hypothesizes that generalizations become suppressed over time when presented with exceptions (cf. exceptions simply becoming more easily-retrieved and generalizations remaining at the same retrieval level).
* Mousetracking is used specifically to investigate the effect of lures. If an (incorrect, generalized) stimuli attracts the user before they move their mouse towards the correct stimuli, we can assume that generalizations are still playing an effect on the user's psyche. As the attraction towards the lure decreases, it can be assumed that the exception retrieval rate is beating out that of the generalization.

In terms of functions & methods and their parameters, I'd ideally like to have multiple functions that will use pandas to create various dataframes and plots to model the data (similar to what we did in lab_15 and homework_15). However, my project will incorporate more complexity: 
* There will be more data and variables to organize (trial count, reaction times, accuracy, x and y positions, scores, etc.)
* I will be using the pandas and numpy libraries
* I will be examining the mousetracking data with the goal of analyzing and plotting the mouse movements
* I will be formatting everything using a Jupyter notebook

This program is useful because it provides a way to both explain the context and motivations behind the experiment and analyze the findings--all in one organized space: the Jupyter notebook. I hope to reuse the code I write for this project in future research projects to present my conclusions.    

I will be using numerous .csv data files as input. As mentioned in the Zoom meeting, the data used will have been generated from the previous experimental runs of AbberZip.  

There are 5 collections of data: 
* clickData
* itemTest
* trackData
* studyPhase
* trackAllData

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

Each itemTest file will be formatted as such: 

     blockNum = int
     testItemNum = int
     testRt = float
     testResp = int
     testAcc = bool

Each trackData file will be formatted as such:

     trialCt = int
     rt = float 
     pos_x = float
     pos_y = float

Each studyPhase file will be formatted as such: 

     matchInfoNum = int
     partWordID = int
     group type = int
     prefix = int
     imCat = int
     imID = int
     trialCt = int
     eachBlock = int
     rt = float
     thisResp = int
     acc = bool 

Each trackAllData file will be formatted as such: 

     trialCt = int
     rt = float 
     pos_x = float
     pos_y = float
     
