A simple pomedoro timer implemented in Python. Rings a bell when starting work periods, rest periods, and when
ending rest periods. Logs a simple csv format for convenient tracking. Allows the assignment of a topic name 
and custom schedule.

There is only one dependency: pygame (for cross platform audio). 
To install pygame: ``` python3 -m pip install -U pygame --user ```

To run: ``` python nightshade.py ```
or try ``` python nightshade.py -h ``` for help with usage.

I recommend setting up a bash alias or function for convenience

Something like: 
```
pomedoro() {
	cd ~/Desktop/code/nightshade-pomedoro
	python nightshade.py "$@"
}
```
