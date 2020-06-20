# Udemy_Premium_Course_Grabber
Script to add all udemy paid/free courses having coupons automatically to your udemy account

## ***Requirements***

- Python (2 or 3)
- Python `pip`
- Python module `requests`
- Python module `colorama`
- Python module `bs4`
- Python module `browser_cookie3`

## ***Module Installation***

	pip install -r requirements.txt

## ***Features***

- Automatic login through browser using `browser_cookie3`
- One click to add all courses available with coupons to your udemy account.
- You can add any specific course to your account from the list of courses available.
- Many popular sites added to grab fresh/new courses (coupons).
- Many more features

## ***Usage***

***Add all/specific course***

    python udemy.py

***Or with cookie***

    python udemy.py -c cookie.txt

***To schedule with cron jobs***

    python udemy.py --cron

***Guide to create cookie.txt file***
- Firstly go to udemy.com, then login 

- Then Press CTRL+SHIFT+I 

- Go To Application Tab

- Select COOKIES Then Udemy

- Locate Access Token And Client ID 

- Replace It With The text on cookie.txt 

- Then RUN Python File 

<img src='images/1.png' width='600' height='400'>


<img src='images/2.png' width='600' height='400'>


<img src='images/3.png' width='600' height='400'>


<img src='images/4.png' width='600' height='400'>


<img src='images/5.png' width='600' height='400'>


