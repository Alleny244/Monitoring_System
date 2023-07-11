# i C u - Automated Proctoring System
<p align="justify">
  An innovative solution to the issue of remote exam proctoring is the development of
AI-based monitoring systems that utilize machine learning algorithms. These systems have
the ability to automatically identify and flag potential cheating behaviors, such as irregular
eye movements, head gestures, and keyboard activity, and alert the proctor in real-time. To
this end, we plan to create an AI monitoring system using Python that can monitor students
via their laptop’s webcam and microphone, enabling teachers to observe multiple students
simultaneously. The AI monitoring system will incorporate four vision-based capabilities -
gaze tracking, mouth open or close detection, person counting, and mobile phone detection
 that are integrated using multi-threading to operate cohesively.
 </p>

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


#### For vision:
```
Tensorflow>2
OpenCV
sklearn=0.19.1 # for face spoofing.

```


### Demo

| <img src="https://github.com/Alleny244/Monitoring_System/assets/56961826/50438f25-8187-474e-80c4-fefe4ec69e5b"  width="300" height="300"> | <img src="https://github.com/Alleny244/Monitoring_System/assets/56961826/43d905e0-9d83-4e47-a95f-25cdf8a23181"  width="300" height="300">                        |
| ----------------------------------- | ----------------------------------- |
| <img src="https://github.com/Alleny244/Monitoring_System/assets/56961826/43d905e0-9d83-4e47-a95f-25cdf8a23181"  width="300" height="300"> | <img src="https://github.com/Alleny244/Monitoring_System/assets/56961826/abfacc94-acb3-4f42-af8c-750f7073f86e"  width="300" height="300">  |

  
## Collaborators
  | |  |  |  |  |
  | ------------- | ------------- | ------------- | ------------- | ------------- |
  | Allen Y| [GitHub](https://github.com/Alleny244) | 
  |      Divina Josy | [Github](https://github.com/diina7) |
  |    Elsa Maria Joseph   | [GitHub](https://github.com/Lza-etc) | 
