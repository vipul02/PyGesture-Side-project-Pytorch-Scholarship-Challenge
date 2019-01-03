# PyGesture-Side-project-Pytorch-Scholarship-Challenge
This is a python app associated with a flask web app for associating gestures to certain actions on your PC
# How to use it ?
## What to install ?
You need to have :
- Python 3.6 or Higher installed
- torch installed.
- Google Chrome install (if you want website opening actions)

## Python libraries
```
pip install flask
pip install keyboard
```

## How to run the program
- Go to the environment where you installed all the dependencies
- Go to the command line and run the command according to your OS :
        - Linux or Mac run : export FLASK_APP=index.py
        - Windows : set FLASK_APP=index.py
- Run this command in the command line : 
>flask run
- There are 2 available gesture : 
         - Fist
         - High five
- There are 3 available types of actions : 
         - Opening a website
         - Pressing a key
         - Typing a phrase
- Choose the actions according to what you want ! Make sure to type URLs correctly.
             - If you choose Pressing a key, i recommend testing with "space" on a video ;) (Pause/Unpause with a gesture)
- Click on `Save Settings`
- Close the web app

- The following program will need to access your webcam, you can go over the code and see that there is no harm on activating your webcam :p.
- In order for the program to be able to access your webcam, you need to authorize it or suspend your antivirus T_T.
- Go to the command line and run :
>python program.py

- The program is now running ! Try one of the gestures to trigger the actions ! :) 
- Have fun !
