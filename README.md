# Salary Predictor
This team project was completed at Intuit's 2nd annual hackathon "Hack Into It" at UC Berkeley, co-hosted by Machine Learning @ Berkeley and Phi Sigma Rho. Contributers to the project were: Sayan Ray Chaudhuri, Lawrence Yan, Mong Ng, and Jonathon Lin

Salary predictor is a command line tool helps college graduates determine their expected job salary based on their prospective career field and geographical location. By comparing expected job salaries, the user should be able to determine the career field and job location that meet their salary interests.

First, the user is asked to input their career field of interest and the state where they want to live by entering numbers from list menus. Then, based on the inputs, we access US Census data for the given career field and state, which returns the median salary of employees working in the career field and state.

We output the median salary to the user as their expected salary and also output the crime rate for the chosen state (using data from WorldAtlas.com) as an additional factor for the user to consider.

To use this tool, first install Python3. Then run "python3 main.py" in the commmand line in this current directory.
