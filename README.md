# Financial Retirement Planning


This code was created with the purpose of building two analysis tools with Jupyter notebook. Within this code I developed a financial planner  for  emergencies and a financial planner for retirement. The calculations made in the financial planner for emergencies used monthly income data to determine if an emergency fund has enough money or how much money is missing in order for the fund to be successful.  The calculations made in the  financial planner for retirement were based on 10 year returns and 30 year returns, and predicted how much money the members of a portfolio would receive by varying the bonds and stocks in this portoflio with the help of the Monte Carlo simulation. 

## Technologies

os

requests

json

pandas as pd

dotenv

alpaca_trade_api

MCForecastTools

%matplotlib inline

## Installation Guide


In order to open and run this program you have to follow these steps:


Go to my repository in GitHub and open the repository called "financial_retirement_planning"

![ssh_financial_jpeg](https://user-images.githubusercontent.com/80844686/116802500-2b34e500-aac8-11eb-957a-6fa69b014ff3.jpg)

Copy the repository's link

Open Git Bash in your computer 

![git_bash](https://user-images.githubusercontent.com/80844686/115638940-40d82c80-a2c8-11eb-816a-e991b245cd88.jpg)

clone the repository by typing "git clone" and paste the link "git@github.com:nestor39/financial_retirement_planning.git"

![git_clone_financial_pneg](https://user-images.githubusercontent.com/80844686/116802563-86ff6e00-aac8-11eb-871a-e12a069040f0.png)


After cloning the repository, activate the Conda development environment and then run the following code:

conda install -c anaconda requests

conda install -c jmcmurray json

pip install python-dotenv

pip install alpaca-trade-api

After installing the tools above 

Type "jupyter lab" in your Git Bash(it will open a tab in your explorer)

![jupyter_lab](https://user-images.githubusercontent.com/80844686/115638854-09698000-a2c8-11eb-9986-16b409546753.png)

Open the file "financial_planning_ipynb" and you are going to see the code.

But before running the code you should open a new tab in your browser and paste this link https://app.alpaca.markets/signup and create your account with alpaca

![image](https://user-images.githubusercontent.com/80844686/116803342-6389f280-aacb-11eb-8fb0-be917fc26184.png)

Get the alpaca API and secret keys

![image](https://user-images.githubusercontent.com/80844686/116803343-6dabf100-aacb-11eb-8b57-07005d47ff5b.png)

Go back to jupyter lab, create a file and rename it as ".env" inside this file copy and paste:
  
  ALPACA_API_KEY = “Your Alpaca API Key Here”
  
  ALPACA_SECRET_KEY = “Your Alpaca Secret Key Here”

Save it

Push play

## Results


Financial Planner for Emergencies

![Value of the member's portfolio](https://user-images.githubusercontent.com/80844686/116804120-26c0fa00-aad1-11eb-8326-b90f1c841f18.png)

We can see depending on how much money we have in our portfolio, if we have enough for emergencies or if we don't, it will also tell us how much money we are missing.


Financial Planner for Retirement
This forecasts cumulative retruns in a 10 year scenario and a 30 year scenario:

![MC_ten_years_dis_plot](https://user-images.githubusercontent.com/80844686/116803399-296d2080-aacc-11eb-84bb-4c924cc4c280.png)

![MC_ten_years_sim_plot](https://user-images.githubusercontent.com/80844686/116803401-2b36e400-aacc-11eb-8645-7d6a76f740bb.png)


![MC_thirty_years_dis_plot](https://user-images.githubusercontent.com/80844686/116803405-2f630180-aacc-11eb-9bb1-0b7d5716eb85.png)

![MC_thirty_years_sim_plot](https://user-images.githubusercontent.com/80844686/116803406-312cc500-aacc-11eb-96a7-eff067554eac.png)



## Examples
The following image shows a diagram of the financial retirment planning file:

![financial_retirement_pllaning_jpeg](https://user-images.githubusercontent.com/80844686/116802060-9d0b2f80-aac4-11eb-9aad-be846821735d.jpg)



## Contributors

This project was made with helpful contribuitions from Berkeley Fintech Bootcamp members; Siege and Joel Gonzales. Joel Gonzales was of particular assistence when it came to improving the code.

I also utilized the AskBCS Learning Assistent in order to fine-tune my project.


This code was written by Nestor Ramirez.

email: nestorramirez3994@gmail.com

Linkedin: (https://www.linkedin.com/in/nestor-ramirez-cuadro-375654209/)

## License
MIT
