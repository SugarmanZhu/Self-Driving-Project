# Self-Driving Project

I programmed a controller to provide longitudinal speed control (throttle and break) and lateral steering control.

The controller successfully direct the vehicle to complete a race track in CARLA simulator.

CarlaUE4Windows.zip and CarlaUE4Ubuntu.tar.gz can be downloaded from https://drive.google.com/drive/folders/101f_7jeTivCd6d38idCvvZD0b5TD6sxV?usp=sharing ~~https://zhuxiaotan.xyz/self-driving-project/~~

## Installation and Run:

### Windows:

1. Download the CarlaUE4Windows.zip file

2. Unzip the file to a working directory e.g. Path\Project\CarlaSimulator

3. Install dependencies

   `pip install -r Path\Project\CarlaSimulator\requirements.txt --user`

4. Test Installation

    `cd Path\Project\CarlaSimulator`

   `CarlaUE4.exe -windowed -carla-no-networking`

   This should load the CARLA simulator

5. Download the Project.zip file

6. Unzip the file into Path\Project\CarlaSimulator\PythonClient

7. Start a CARLA server 

   `CarlaUE4.exe /Game/Maps/RaceTrack -windowed -carla-server -benchmark -fps=30`

8. Start a CARLA client in another terminal

    `python module_7.py`



### Ubuntu:

1. Download the CarlaUE4Ubuntu.tar.gz file

2. Unzip the file to a working directory e.g. Path/Project/CarlaSimulator

3. Install dependencies

   `pip install -r Path/Project/CarlaSimulator/requirements.txt --user`

4. Test Installation

    `cd Path/Project/CarlaSimulator`

   `./CarlaUE4.sh  -windowed -carla-no-networking` 

   This should load the CARLA simulator

5. Download the Project.zip file

6. Unzip the file into  Path/Project/CarlaSimulator/PythonClient

7. Start a CARLA server 

   `./CarlaUE4.sh /Game/Maps/RaceTrack -windowed -carla-server -benchmark -fps=30`

8. Start a CARLA client in another terminal

    `python module_7.py`



### MacOS:

CARLA simulator is not recommend to be run on MacOS.



