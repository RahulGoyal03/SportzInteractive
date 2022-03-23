# Sportz Interactive Assignment -:
 
* Fetch the Player details from this url
https://api.npoint.io/20c1afef1661881ddc9c

* Display the list of players as cards in a grid view
* Show the Image using the id from the images. /playerimages/{Id}.jpg
* Display players full name and Skill using PFName and
SkillDesc
* Display players value in $ using Value property.
*  Display players Upcoming match using first node from
UpComingMatchesList - CCode vs. VsCCode . Also

* Display next match time in DD-MM-YYYY h:mm:ss a
format. Display the date in users timezone. Provided date
is in UTC.
* By default listing should be in ascending order of Value.
* Add a search Input which will search through the list
based on TName and PFName

# Instructions for run the Assignment 

1. Download VS Code from https://code.visualstudio.com/download
2. Install NodeJs from https://nodejs.org/en/download/
3. write on terminal  "git clone https://github.com/RahulGoyal03/SportzInteractive.git"
4. write on terimal npm install
5. After that write npm start 

# Deploy Link -:
https://sportz-interactive.vercel.app/


# Prerequisites 
* VS Code


# Installation 
* Clone the repository
    ``` 
    git clone https://github.com/RahulGoyal03/SportzInteractive.git
    ```

# Tech Stack

* React
* Javascript
* Material UI
* CSS


# Approch To Solve -:
0. Understanding the Problem Statement.
1. First I fetch the data from the API.
2. Make a images folder and put all the images in that.
3. Take the ID of player and add this ID with the path of image, to find out which image is associated with which player.
4. Sort the data with values.(default is ascending)
5. Implement the search bar with proper search functionality with Player Name.
6. Display the Upcomming Matches Timing Below the Player Name.


# Final Output -:


![Screenshot (148)](https://user-images.githubusercontent.com/91531231/159796278-9ea21aae-cd63-4e06-a57e-2e9648e0ccf9.png)
