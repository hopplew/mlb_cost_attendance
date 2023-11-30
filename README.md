# MLB Team Cost Efficiencies

## Summary:
One of the unique aspects of MLB compared to other major league sports is lack of a salary cap. Essentially MLB teams can spend as much as they would like player salaries, as opposed to other sports that limit the amount of total player salaries. This can potentially lead to a lack of parity between smaller and larger market teams as they there can a large disparity between the money spent on players, leading to talent being acquired mostly by teams with the most money to spend on payroll.

This project is an analysis of selected Major League Baseball statistics from 2021-2023. The goal of this analysis is to try to find if there is a relationship bewteen the amount of money spent on team payroll, and the success of a team. The success will be determined by the win total and attendance averages from a chosen period, and compare those to the payroll of the teams from that same period to most value per dollar spent on player salary. To accomplish this, I have taken 3 data points for each team (total wins, total payroll, total attendance) for the past 3 years (2021-2023). I have then cleaned the indiviaul pieces data into a format so they could be merged together for analysis.

The project will make use of Jupyter notebooks to run the python files and for code annotation and explanation.

## Instructions:
1. Clone the mlb_cost_attendance repo to your machine.
2. Create and activate a virtual environment and install the packages listed in the requirements.txt file. (instructions for virtual environment below)
3. Run Jupyter files in order 
    1. a_import_payroll_1st
        - creates team payroll file 
    2. b_import_attendance_2nd
        - creates team attendance file
    3. c_import_wins_3rd
        - creates team wins file
    4. d_wins_attendance_payroll_4th
        - merges previously created files into one for plotting
    5. e_mlb_plots_5th
        - Plots and analysis from created file
4. Notations for code are in Jupyter notebook

## Virtual Environment Instructions
1. Once repo is cloned, navigate to it's folder in Terminal/GitBash
2. Create virtual environment on Windows by entering:

    Windows (GitBash): python -m venv venv

    Linux/Mac (Terminal): python3 -m venv venv
3. Activate venv by entering:

    Windows (GitBash): venv/Scripts/activate

    Linux/Mac (Terminal): source venv/bin/activate
4. Run requirements.txt to install needed libraries:

    Windows (GitBash): pip install -r requirements.txt

    Linux/Mac (Terminal): pip install -r requirements.txt
5. When done in venv, deactivate by entering:

    Windows (GitBash): deactivate

    Linux/Mac (Terminal): deactivate

## Features:
1. Read in two or more data files (CSV)
2. Clean data and perfrom pandas merge. Calculate new values based on new dataset.
3. Make 3 matplotlib visualizations of data.
4. Use virtual environment and include set up instructions in README. 
5. Annotate and clean code in Jupyter Notebook.

## Sources:
Attendance: https://www.espn.com/mlb/attendance

MLB Team Payrolls: https://www.stevetheump.com/Payrolls.htm   

MLB Team Wins: https://www.baseball-reference.com/leagues/majors/index.shtml


