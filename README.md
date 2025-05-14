My project involves a data analysis of a mousetracking project run by Karina Tachihara: https://escholarship.org/content/qt82x8c04s/qt82x8c04s_noSplash_58ab61cf9074d73a890585be5e003c37.pdf?t=sgiuiq

My analysis is outlined in a Jupyter notebook, and is composed of:
* A background section explaining the study
* Seven steps as follows:
     * Step 1: Amalgamate the data I need from 3 separate files (runInfo, clickData, trackAllData) and put it into a master spreadsheet with all particpants 
     * Step 2: Flip each mousetracking trajectory to be on the left side (to simplify analysis)
     * Step 3: For one participant: Create a plot of the x and y positions of the mouse during trial type 11 (target trial) and Blocks 2 and 7 (the testing phases) 
     * Step 4: For one participant: Create a plot of the average mouse trajectories during blocks 2 and 7 (the testing phases) using interpolation
     * Step 5: For one participant: Calculate the areas under the curve 
     * Step 6: For all participants: Calculate the areas under the curve 
     * Step 7: Determine the statistical significance of the average AUC difference result
* A conclusion section that interprets the final results and outlines possible future improvements for the project and the analysis


Instructions for running: 
* Clone the repository or download the notebook
* Download clickData, runInfo, trackAllData, and images folders by pasting their URLs into https://download-directory.github.io/
* Make sure that the clickData, runInfo, and trackAllData, and images folders are in the same directory as the jupyter notebook. Create a new empty folder called 'output' (to catch the spreadsheets) and put that in the same directory also.
* Open the notebook in your editor and run everything
* To install all the requirements at the same time, use this command in your terminal:
     ```bash
     pip install -r requirements.txt

