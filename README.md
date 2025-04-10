My (revised) program will be an analysis program for the data generated from a Psychopy experiment explained further below. I hope to analyze mousetracking data and response times as the main dependent variables. I plan to use a Jupyter notebook to organize everything and explain the context and motivations behind the original experiment. 
* Context summary: The AbberZip project is meant to examine the cognitive processes underlying language learning, more specifically, the           thought processes involving learning generalizations and exceptions. The researcher behind the project (Dr. Karina Tachihara) hypothesizes that generalizations become suppressed over time when presented with exceptions (cf. exceptions simply becoming more easily-retrieved and generalizations remaining at the same retrieval level).

In terms of functions & methods and their parameters, I'd ideally like to have multiple functions that will use pandas to create various dataframes and plots to model the data (similar to what we did in lab_15 and homework_15). However, my project will incorporate more complexity: 
* There will be more data and variables to organize
      * trialCt
      * rt (reaction times)
      * accuracy
      * pos_x
      * pos_y
      * score
* I will be analyzing mousetracking data with the goal of analyzing and plotting the mouse movements
* I will be formatting everything using a Jupyter notebook

This program is useful because it provides a way to both explain the context and motivations behind the experiment and analyze the findings--all in one organized space: the Jupyter notebook. I hope to reuse the code I write for this project in future research projects to present my conclusions.    

I will be using numerous .csv data files as input. As mentioned in the Zoom meeting, the data used will have been generated from the previous experimental runs of AbberZip. 
Each file will be formatted as such: 
     xxx
     yyy
     zzz
* descriptive field names and their required content formatting (e.g. strings, integers
* whether variable names must be included and/or whether fields must be in a specified order, etc.
