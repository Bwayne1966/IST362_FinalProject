# IST362_FinalProject
# Great North's Saga Weaver

Concept: An app where users can create mythology-inspired stories or sagas.

Features: A selection of characters, settings, and plot elements based on Norse 
myths. Users can mix and match to create their narrative.

Community Engagement: Allow users to share their sagas and vote on their favorite ones.

Goal: Stimulate a desire to read and research Norse History.

# This application uses Python3.12 and this inclides PIP, to validate you have Python:

First, ensure that Python is installed on your system. You can check this by running python --version or python3 --version in your terminal. 
If Python is installed, it should return the version number.

# Install or Update Python:

If Python is not installed, download and install it from the official Python website. During installation, make sure to select the option to add Python to your PATH.
If you have Python installed, but it's an older version, consider updating it. Newer versions of Python come with pip included.

# Check if pip is Installed:

After ensuring Python is installed, check if pip is installed by running pip --version or pip3 --version. If it returns a version number, pip is installed.

Install pip Manually if it is not loaded automatically:
TO INSTALL PIP (Python3.12)
	Type the following in terminal: "curl -sSL https://bootstrap.pypa.io/get-pip.py -o get-pip.py
	python3 get-pip.py"
 Make sure the latest version of PIP is being used by typing the following in your terminal: "pip install --upgrade pip"

# HOW TO LOAD THE APPLICATION
This application will use an OpenAI API - you will need an OpenAI account to obtain an API Key 
    Type export OPENAI_API_KEY="your_api_key_here" in your terminal
    
# FILE LOCATION
Type "cd file_path" press enter. (Insert the file_path to IST362_PROJ. This should end in "\IST362_PROJ")

# DOWNLOAD APPLICATION AS IST362_PROJ
  Type "git clone https://github.com/Bwayne1966/IST362_FinalProject/tree/main/IST362_PROJ"
    
# VIRTUAL ENVIRONEMENT @ IST362_PROJ 
    A Virtual Environment should be established at IST362_PROJ - Create a virtual environment using the venv module.
        Type "python -m venv .env". This creates a virtual environment where you can input the Flask App
    Activate the virtual environment.
        Type ".env\Scripts\activate" (for Mac users, use the following "source .env/bin/activate")

# INSTALL THE NECESSARY PACKAGES IN VIRTUAL ENVIRONMENT
The following should be typed into your terminal (your input line item should begin with (.env) to insure the virtual environment is being used.)

# Setup the Flask Environment
1. type the following in terminal: "pip install Flask"
2. type the following in terminal: "pip install -r requirements.txt"
3. type the following in terminal: "export FLASK_APP=App_Code.py"
4. type the following in terminal: "export FLASK_APP=App_Code"
5. type the following in terminal: "flask run"

# OUTPUT
You should see the following:
 * Serving Flask app 'App_Code'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
# Navigate your browser to "http://127.0.0.1:5000" in the URL bar
# Enjoy the Great North's Saga Weaver!!!! 

NOTE YOU CAN ALSO ACCESS A TEXT AND IMAGE GENERATOR AT THE FOLLOWING (you will need an OpenAI account):
https://chat.openai.com/g/g-thKx3GAww-great-north-s-saga-weaver



