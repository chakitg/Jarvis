
# JARVIS (Just a Rather Very Intelligent System)

This was my attempt to make a voice assistant similar to JARVIS (in iron man movie)
Let's be honest, it's not as intelligent as in the movie, but it can do a lot of cool things and automate your daily tasks you do on your personal computers/laptops.


## Features

- Greet user
- Tell current time and date
- Launch applications/softwares
- Open any website
- Tells about weather of any city
- Open location of any place plus tells the distance between your place and queried place
- Tells your current system status (RAM Usage, battery health, CPU usage)
- Tells about your upcoming events (Google Calendar)
- Tells about any person (via Wikipedia)
- Can search anything on Google
- Can play any song on YouTube
- Tells top headlines (via Times of India)
- Plays music
- Send email (with subject and content)
- Calculate any mathematical expression (example: Jarvis, calculate x + 135 - 234 = 345)
- Answer any generic question (via Wolframalpha)
- Take important note in notepad
- Tells a random joke
- Tells your IP address

## Installation

- First clone the repo
- Make a new python environment If you are using anaconda just type conda create -n jarvis python==3.8.5`  in anaconda prompt
- To activate the environment conda activate jarvis
- Navigate to the directory of your project
- Install all the requirements by just hitting `pip install -r requirements.txt`
- Install PyAudio
- Run the program
- Enjoy !!!!
## Installation

- First clone the repo
- Make a new python environment If you are using anaconda just type `conda create -n jarvis python==3.8.5`  in anaconda prompt
- To activate the environment conda activate jarvis
- Navigate to the directory of your project
- Install all the requirements by just hitting `pip install -r requirements.txt`
- Install PyAudio
- Run the program
- Enjoy !!!!
## Code Structure

├── driver

├── Jarvis              > Main folder for features 

│   ├── config          > Contains all secret API Keys

│   └── features        > All functionalities of JARVIS 

├── requirements.txt    > all dependencies of the program

- The code structure if pretty simple. The code is completely modularized and is highly customizable

- To add a new feature:
    - Make a new file in features folder, write the feature's function you want to include
    - Add the function's definition to init.py
    - Add the voice commands through which you want to invoke the function
## Future Improvements

- Generalized conversations can be made possible by incorporating Natural Language Processing
- GUI can be made more nicer to look at and functional
- More functionalities can be added
