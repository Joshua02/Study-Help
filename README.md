# Study Help

Study help is an app made to help me study with variety and perzonlization

## Prerequisites:

* [python 3.3+](https://www.python.org/)
* [pip (latest)](https://pip.pypa.io/en/stable/installing/)

## Windows:
### How to open the terminal in the folder with README.txt:
1. have the folder open that has the README.txt 
2. press 'shift + right click' anyhwere in the folder
3. select "Open PowerShell window here"

### Installing the app:
1. ```set-executionpolicy remotesigned current user``` this is to make it so you can apply these scripts
2. open the terminal in the folder with README.txt
3. ```py -m venv env```
4. ```.\env\Scripts\activate```
5. ```pip3 install -r requirements.txt```

### Start the app:
1. ```set-executionpolicy remotesigned current user``` this is to make it so you can apply these scripts
2. open the terminal in the folder with README.txt
3. ```.\env\Scripts\activate```
4. ```python website.py```


## macOS/Linux:

### How to open the terminal in the folder with README.txt:
1. open a seperate terminal
2. click and drag folder named "study_help-master" into the terminal (the folder should have README.md in the folder)

### Installing:
1. open the terminal in the folder with README.txt
2. ```python3 -m venv env```
3. ```source env/bin/activate```
4. ```pip3 install -r requirements.txt```

### Start the app:
1. ```pipenv shell```
2. ```python3 website.py```
