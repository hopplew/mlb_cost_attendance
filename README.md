Summary:

This project is an analysis of Major League Baseball statistics from 2021-2023.
The statistics used for analysis are team total payroll, wins, and attendance over the 3 year period. The goal is to analyze the data and find the most efficient teams in of cost efficient success.
The project will make use of Jupyter notebooks to run the python files and for code annotation and explanation.

Instructions:
1. Clone the repo to your machine.
2. Create and activate a virtual environment and install the packages listed in the requirements.txt file. (instructions for virtual environment below)
3. Run Jupyter files in order 
    1. a_import_payroll_1st
    2. b_import_attendance_2nd
    3. c_import_wins_3rd
    4. d_wins_attendnce_4th
    5. e_mlb_plots_5th
4. This will create new files for use in plotting
5. Notations for code are in Jupyter notebook

Virtual Environment Instructions for Windows
1. Once repo is cloned, navigate to it's folder in terminal
2. Create virtual environment on Windows by entering: (for other operating systems refer to https://docs.python.org/3/library/venv.html)
    python -m venv venv
3. Activate by entering:
    venv\Scripts\activate
4. Run requirements.txt to install needed libraries:
    pip install -r requirements.txt
5. When done in venv, deactivate by entering:
    deactivate

Features:
1. Read in two or more data files (CSV)
2. Clean data and perfrom pandas merge. Calculate new values based on new dataset.
3. Make 3 matplotlib visualizations of data.
4. Use virtual environemt and include set up instructions in README. 
5. Annotate and clean code in Jupyter Notebook.

Sources:
MLB Team Payrolls: https://www.stevetheump.com/Payrolls.htm   
MLB Team Wins: https://www.baseball-reference.com/leagues/majors/index.shtml 
Attendance: https://www.espn.com/mlb/attendance


