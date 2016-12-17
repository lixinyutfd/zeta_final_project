# zeta_final_project

_This package addresses the final project: Make the Baxter robot Merry sort blocks._

The project was created as part of Team Zeta.

Member Name | Case ID
:---:|:---:
Leah Platt | lrp39
Andrew Lonsberry | agl10
Xinyu Li | xxl594
Darshan G. Parikh | dgp34

## How to Run

_Make absolutely certain that the version of learning_ros repository being used is the repository clone located inside this package!_

0. In all terminals used, make sure to identify Merry's roscore.
1. From the command line, run `roslaunch zeta_object_finder zeta.launch`. Wait for this to complete before moving to the next step.
2. In a new terminal tab/window, run `rosrun zeta_object_finder zeta_coordinator`. Make certain the table is properly aligned in front of Merry.
3. Once the coordinator has loaded, it will ask the user if they are ready to detect blocks. Place a block on the table and enter `1`.
4. When Merry has completed her motions, the user will be prompted to return Merry to her starting pose by entering `1`. From here, the user can repeat step 3 or end the program in step 5.
5. Press `0` to end the coordinator. End all other processes and close all terminals when finished.

Enjoy!
