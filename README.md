# JB4-PYTHON-PROJECT
## Exploring Price Dynamics: Vegetable Prices in 2023 and 2024
![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![fresh-organic-vegetables](https://github.com/ZweeteeM/JB4-PYTHON-PROJECT/assets/167215461/9a66422c-fcf2-4fd6-8934-91d4b5147318)
## Table of contents
* [1. Overview](#project-description)
* [2. Setting Up the Coding Environment](#environment-and-packages)
* [3. Creating a branch](#cloning-and_editing)
* [4. Datasets](#dataset)
* [5.Team Members](#contributers)

## 1. Overview
Welcome to the Vegetable Price Analysis project! This report presents an analysis of vegetable prices focusing on the years 2023 and 2024. The study aims to uncover trends, fluctuations, and factors influencing vegetable prices during this two-year period. By examining price dynamics within this specific timeframe, the report provides insights into short-term trends and their implications for stakeholders in the vegetable market.
The purpose of this project is to:
- Delves into the analysis of vegetable prices specifically for the years 2023 and 2024.
- Collecting and examining data on vegetable prices during these two years
- Identify any notable trends or fluctuations, and investigating potential factors driving these price dynamics.
- Analyze price data for a limited timeframe in oreder to focus on the  exploration of short-term trends and insights into the factors influencing vegetable prices within this specific period.
- Provide insights for consumers, retailers, and policymakers regarding vegetable pricing dynamics.
- Enable stakeholders to make informed decisions related to buying, selling, and policy-making in the vegetable market.
## 2. Setting Up the Coding Environment

1. Clone the Repository: Clone the project repository from GitHub using the following command:
bash

git clone https://github.com/ZweeteeM/JB4-PYTHON-PROJECT.git

2. Install Dependencies: Navigate to the project directory and install the necessary dependencies using pip:
bash

cd price_df
pip install -r requirements.txt

3. Activate the environment for which you want to export the package list using the conda activate <environment_name> command.

4. Run the following command to generate a text file containing the list of installed packages:
conda list --export > environment.txt

5. Then add this environment.txt file to your GitHub repository and commit the changes. This will allow others to see the list of packages and recreate the environment using the conda create --name <env_name> --file environment.txt command.
## 3. Creating a branch

- *Push New Branch to Remote Repository*: Use the git push command followed by the name of the remote repository (origin by convention) and the name of the local branch you want to push. If the branch doesn't exist on the remote repository yet, Git will create it for you:
   
   git push origin feature-branch
   
-  *Authenticate (if prompted)*: If this is the first time pushing to the remote repository or if you haven't authenticated previously, Git may prompt you to enter your credentials (username and password) for the remote repository.

- *Verify on Remote Repository*: After pushing the branch, you can verify that it has been created on the remote repository by visiting the repository's page on the hosting platform (e.g., GitHub) in a web browser

- *Make Changes to Your Project Files*: Using jupyter notebook

- *Check Status*: use the git status command to see which files have been modified:
   
   git status
   
- *Add and Commit Changes*: If you're happy with the changes you've made, you can add them to the staging area and commit them using the following commands:
   
   git add .
   git commit -m "Your commit message here"

- *Repeat as Needed*:  repea this process as many times as necessary until you're satisfied with your changes and ready to push them to the remote repository.

- *Push Changes (if necessary)*:push the changes to the remote repository using the git push command:
   
   git push origin <branch_name>
## 4. Datasets
Accessing Data: The project may require access to historical vegetable price datasets. Ensure that you have the required datasets stored in a directory accessible to the project.
Run the Code: Once dependencies are installed and data is accessible, you can run the main script to perform data analysis and generate insights:
css

python main.py

Explore Results: After running the code, explore the generated results, including visualizations and analysis reports, to gain insights into vegetable pricing trends.

Contributors:
Zwiitwaho Mugodo (mugodozwiitwaho@gmail.com)
Keneilwe 	Rangwaga (patricia001105@gmail.com)
Seneme	Mpungose (leebunny1623@gmail.com)
Tumelo Matamela (tumelomatamane1@gmail.com)

Thank you for your interest in the Vegetable Price Analysis project! We hope you find it informative and useful. Happy analyzing!
