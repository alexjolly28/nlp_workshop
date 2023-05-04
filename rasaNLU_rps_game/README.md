
To run: 

* Install Python3.8 virtual env `python3.8 -m venv rasa_env`
* Activate virtual environment ` sounrce rasa_env/bin/activate`
* Clone repository
* install python packages `pip install -r requirments.txt`
* Run the action server: `rasa run actions`
* Talk to the assistant in the shell: `rasa shell`

Note that the markers *will not* work unless you set up a tracker store other than the default in-memory one, they are provided as a syntax example only.
