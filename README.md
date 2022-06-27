# Algorithmic Trading ML



# Technologies

This program leverages python 3.7+

To ensure all dependencies are installed and up-to-date, please run the following commands in your terminal once you have cloned the repository to your local machine.
run pip install -r requirements.txt

---

## Installation Guide

1. Copy this repository via the URL (SSH or HTTP)
<img width="907" alt="Screen Shot 2022-04-03 at 3 35 27 PM" src="https://user-images.githubusercontent.com/98444459/161445246-d4eecac4-44ae-452f-8e0c-ebaa9e523908.png">

2. Run a git clone command in your terminal or git bash under the desired local directory
<img width="766" alt="Screen Shot 2022-06-18 at 5 09 13 PM" src="https://user-images.githubusercontent.com/98444459/174460708-4206527c-585d-4148-bde4-454fc78f6e16.png">

3. If you receive errors, please review the dependencies above, install them and try again. 

---

## Usage

1. Navigate to the directory in either the Terminal or GitBash. 

2. From the top folder (Challenge_14), launch jupyter lab by typing 'jupyter lab' into Terminal or Gitbash and pressing 'Enter'
<img width="570" alt="Screen Shot 2022-05-08 at 1 56 51 PM" src="https://user-images.githubusercontent.com/98444459/167309092-db3b1a32-49bf-4a3c-a7d7-cc9674d32d38.png">

3. Open the 'machine_learning_trading_bot.ipynb' notebook and follow the instructions therein.  
<img width="395" alt="Screen Shot 2022-06-26 at 7 37 53 PM" src="https://user-images.githubusercontent.com/98444459/175849666-b8b3d528-577a-4cd3-b700-ddba8d2b0b9d.png">

---

# Analysis

## Baseline Performance
Actual vs Strategy Returns:
<img width="810" alt="Screen Shot 2022-06-26 at 7 35 13 PM" src="https://user-images.githubusercontent.com/98444459/175849683-cfcdc2fa-0d51-4893-afcf-ce2c75386508.png">
As we can see with the above image, the baseline strategy already outperforms actual returns so it is a strong baseline. 

## Tuning the Baseline
<img width="806" alt="Screen Shot 2022-06-26 at 8 19 24 PM" src="https://user-images.githubusercontent.com/98444459/175853694-5ce607c2-182d-4f24-b723-9efeea0cd303.png">
What impact resulted from increasing or decreasing the training window?
By increasing the trading window from 3 to 6 months, the strategy returns actually performed worse that the actual returns.

<img width="806" alt="Screen Shot 2022-06-26 at 8 09 17 PM" src="https://user-images.githubusercontent.com/98444459/175852764-6a8472d4-54c2-41f6-b204-40a71fb8caac.png">
What impact resulted from increasing or decreasing either or both of the SMA windows?
By adjusting the windows up to 16 and 120 respectively, the strategy returns mimic the actual returns trends more closely but, but it still ultimately finishes down when compared the the actual returns. 

As per the above photos, increasing the trading window appears to allow better predictions and a more accurate model, which retults in better strategy returns. 

## New Machine Learning Classifier
<img width="808" alt="Screen Shot 2022-06-26 at 8 22 19 PM" src="https://user-images.githubusercontent.com/98444459/175854023-e70b33ae-ced5-43e8-a165-9c55115d96b1.png">
Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?
As you can see by the above image, the Decision Tree Classifier does a much poorer job than the baseline model and my tuned trading algorithm since the cumulative returns are much much worse. 
--- 

## Contributors

Made by:
Ryan Anderson
  Email: m.anderson.ryan@gmail.com
  LinkedIn: https://www.linkedin.com/in/ryan-anderson-57b2b173

---

## License

No licenses are required to run this application
