# Pokédex

This is a web app version similar to Pokédex(a device for getting details about a pokemon found in the Pokémon cartoon series), built and deployed with [streamlit](https://www.streamlit.io/).

You can upload pokemon images and play with the app [here](share.streamlit.io/bipinkrishnan/pokemon/main).

#### I. Running the app locally
1. Clone the repo by running the below command and change directory to the cloned repo

       git clone https://github.com/bipinKrishnan/pokemon.git
  
1. Make sure that you have installed all the libraries specified in the [requirements.txt](https://github.com/bipinKrishnan/pokemon/blob/main/requirements.txt) file by running the following command

       pip install -r requirements.txt

2. Now run the following command to launch the app

       streamlit run streamlit_app.py 
       
#### II. Code structure
1. [model.py](https://github.com/bipinKrishnan/pokemon/blob/main/model.py) - This file contains the code to make changes to the EfficientNet model to suit our problem set.

2. [helper_func.py](https://github.com/bipinKrishnan/pokemon/blob/main/helper_func.py) - This file contains helper functions to load and preprocess the image, to make predictions, get details about the predicted pokemon and so on.

3. [streamlit_app.py](https://github.com/bipinKrishnan/pokemon/blob/main/streamlit_app.py) - This file contains all the details on how to display the front-end of the streamlit app.

4. [targets.py](https://github.com/bipinKrishnan/pokemon/blob/main/targets.py) - This file contains all the 166 pokemon names stored in a variable called target in the form of a python list.


