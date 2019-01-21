# reddit-wallpaper-bot
Fetches ten hot wallpapers from r/wallpaper and downloads them to a folder

# Walkthrough/Explanation
The code does the following, in the same order:
1. Fetches 256 'hot' posts from r/wallpapers 
2. Deletes ALL .jpg files in the working directory 
3. Checks that the posted pictures are at least 1080p and then puts their URLs in a list
4. Downloads all pictures from their URLs in the list

# Installation:
1. Download this file and put it in a NEW directory that you want to put 10 wallpapers into

2. Create a praw.ini file with your reddit developer crudentials (Visit https://praw.readthedocs.io/en/latest/getting_started/configuration/prawini.html#praw-ini 
for more information)

-Set your wallpaper to be a slideshow of pictures from your directory and run the script!
