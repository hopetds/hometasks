## Hometasks for Python Devops 2017
# Codewars profile:
# ikhamiakou - https://www.codewars.com/users/hopetds
------------
# Final task: Creating python app to monitor my system.
### ik_mon.py - main python file
### config.ini - tiny configuration file
#### Create a simple, separate python app which would monitor the your system/server.
#### Output should be written to the plain text file or json file.(needs to be specified in configuration file)
#### For monitoring purposes use psutil module, see: https://pythonhosted.org/psutil/
#### It should create snapshots of the state of the system each 5 minutes (interval should be configurable):
#### 1. Overall system data
  ● Overall CPU load
  ● Overall memory usage
  ● Overall virtual memory usage
  ● IO information
  ● Network information
#### Example of the structure for output data is about as follows:
#### SNAPSHOT 1: TIMESTAMP : <columns for system wide data>
#### SNAPSHOT 2: TIMESTAMP : <columns for system wide data>
#### SNAPSHOT 3: TIMESTAMP : <columns for system wide data>
#### Config example
#### [common]
#### output = json
#### interval = 5
#### You can use any type of configs: ini files, yaml, json or even python settings.py.

