# Capstone-LOL

# Overview:

League of Legends is a free-to-play, multiplayer online battle arena (MOBA) game consisting of over 160 different champions. Each champion has their own unique abilities within the game. Each champion has different skill sets ranging from beginner to expert. The main objective to the game is for your team of five to fight the other team of five until towers have been destroyed and then the base (Nexus). 

This program will help you to identify champions from the different lanes (top, middle, jungle, bottom/adc, support) and make an informed decision on which champs work best for you based on difficulty levels, cost (blue essense or RP), lanes, and KDA (Kill, Death, Assist ratio). While this analysis will not win you the game it will give you a better understanding on which champs kill, die or assist more throughtout the game based off the various dataframes and visualization within the program. 

# Primary Files:

Champions-2024.xlsx - Gives Champion Details

lol_match_data.csv - Match Data
 
LOL-Notebook.ipynb - Main Program w/ Visualizations 

# Download file and place within Data-Sets folder:

Match Data Set (Kaggle) - lol_match_data.csv

https://www.kaggle.com/datasets/mldatastudent/league-of-legends-match-data

# How to run the program:

1) Fork the repository https://github.com/L8onii/Capstone-LOL
2) Clone the repository to your Github account
3) Access the repository from your command line or Gitbash
4) Install a virtual environment(Windows). The command within Gitbash is "python -m venv .venv" *skip to 5 if you have Apple*
5) Install a virtual environment(Apple). The command within Gitbash is "python3 -m venv .venv" *only for Apple users skip if you have Windows*
6) Activate the virtual environment. The command in Gitbash is "source venv/Scripts/activate"
7) Install the requirements.txt file to install necessary packages by running pip install requirements.txt "pip install -r requirements.txt" within Gitbash
8) (Apple Only) If requirements.txt file did not install openpyxl then use the following code : "sudo pip install openpyxl" within gitbash in the project(Capstone-LOL) directory
9) Run LOL-Notebook.ipynb (includes visualizations within Jupyter Notebook)
10) Close Virtual Enviroment "deactivate" with Gitbash

# Sources:

https://www.kaggle.com/datasets/gabkgonzales/league-of-legends-dataset (Champion Details)

https://www.kaggle.com/datasets/mldatastudent/league-of-legends-match-data (Match Details) *must download seperately due to big file >~700MB*

# Features:

Loading Data - Loading CSV and XLSX files

Cleaning Data - Various edits, drops, column changes, merges

Visualize Data - Various charts from most champion difficulty, most picked champs, most banned champs, champion costs(Blue Essense & RP), top 25 champs averages (kills, deaths, assists), and top 10 champs for each lane by KDA(Kill, Death, Assist ratio)

Best Practices - Instructions on creating virtual environment, notation on Code cells

Interpretation - Able to determine which champs get picked and/or banned more frequently. Also which champs best perform within they respective lanes by dismissing champs with less than 200 game lane presence. 
