# Proctoring-AI

Project to create an automated proctoring system where the user can be monitored automatically through the webcam and microphone. The project is divided into two parts: vision and audio based functionalities. An explanation of some functionalities of the project can be found on my [medium article](https://towardsdatascience.com/automating-online-proctoring-using-ai-e429086743c8?source=friends_link&sk=fbc385d1a8c55628a916dc714747f276).

### Prerequisites
To run the programs in this repo, do the following:
- create a virtual environment using the command:
  - `python -m venv venv`
- activate the virtual environment
  - `cd ./venv/Scripts/activate` (windows users)
  - `source ./venv/bin/activate` (mac and linux users)
- install the requirements
  - `pip install --upgrade pip` (to upgrade pip)
  - `pip install -r requirements.txt`

Once the requirements have been installed, The programs will run successfully.
Except for the `person_and_phone.py` script which requires a model to be downloaded.

More on that later.


For vision:
```
Tensorflow>2
OpenCV
sklearn=0.19.1 # for face spoofing. 


