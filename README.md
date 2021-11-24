# AppetizeExcersise


## Pre-conditions
1. Python 3 installed
2. Geolocation tracking permission allowed for https://the-internet.herokuapp.com/ (see misc details for more info)


## Framework set up
1. Open CMD console (or any other preferred terminal) as administrator
2. Navigate to the empty testing project folder (or create one)
3. Extract files from GitHub into newly created project folder (should be 3 objects - "tests" folder, "page_objects" folder and requirements.txt
3. While in folder, run "python -m venv env" to create a new virtual environment setup
4. Run "call env/Scripts/activate" to activate virtual environment
5. Run "python -m pip install -r requirements.txt" to install necessary modules (the only module used for this project is SeleniumBase)
6. Run "sbase install chromedriver latest" to install driver
7. Run "pytest -s" to run the test suite with print out to console. (see appendix for additional options)

## Misc details

### Author's software configuration
Project was completed using Python v3.10 with SeleniumBase framework.
OS: Windows 10
Text editor: PyCharm 2020.3.3

### Additional framework features
- run tests with -s attribute to print in console
- add -n=num attribute for several instances
- add --headless attribute to run without browser window
- for quick report add --dashboard attribute and open generated dashboard.HTML file
- for detailed report add --html=report.html and open generated report.HTML file
