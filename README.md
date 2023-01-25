## Basketball API
This is an API for a simple basketball app. It persists data in memory. If you should down and restart the application the data will be reset.
The API supports both RESTful and graphql interfaces.

## Set Up
1. install [python](https://www.python.org/downloads/) 
   1. Choose the default options and to install pip
2. clone this repository
3. in the directory with the main.py run `pip install -r requirements.txt`
4. run the application with `uvicorn main:app`
   1. *all data is persisted in memory*
   2. *restarting/stopping the application will erase data*
5. The applicaiton will run on port `http://localhost:8000`
   1. ***You can access interactable documentation of endpoints at `http://localhost:8000/docs`***