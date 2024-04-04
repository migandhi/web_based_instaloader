Application for web scraping instagram public profiles
No login required

This code is subject to test

Also instagram will be quick to detect anomaly

Hence the try is to implement proxy for scraping

I have not tested the code well

git clone https://github.com/migandhi/web_based_instaloader.git

cd web_based_instaloader

pip install -r requirements.txt

Run the following command to start the Flask development server:

python app.py

Open a web browser and visit http://localhost:5000 to view the app

Enter the instagram profile id

Percentage of Posts to Download  , this is the percentage of most liked posts , it is not advisable to download 100 percent profile, desired value is 10 percent to 20 percent

Finally if scraping is successful a zipped file is available to download

The proxy list in the app.py 

is taken from

https://github.com/clarketm/proxy-list/blob/master/proxy-list-raw.txt

Also the web based instaloader is derived from the original python code

found at https://instaloader.github.io/codesnippets.html#top-x-posts-of-user

Basically https://instaloader.github.io is the documentation repository and instaloader can be used as command line for scraping instagram profiles

instaloader can be installed as command line as described at https://instaloader.github.io/installation.html

Also basic usage as command line can be found at https://instaloader.github.io/basic-usage.html
