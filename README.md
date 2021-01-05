# Spotify API
A Jupyter Notebook for sending requests to the Spotify Web API using Python

### Motivation
The aim of this small project was to initialise a relatively simple Spotify API client and use it to pull useful data about tracks (such as tempo, and song key).
You can copy and paste the SpotifyAPI class into your own projects; just remember to set your own client_id and client_secret (details below).

### Dependencies
* Python3
* Jupyter Notebooks
* Requests

### Executing program 
##### As iPython/Jupyter Notebook:
* Download and install Jupyter Notebook [here](https://jupyter.org/install) if 	not already installed.
* Open Terminal, cd into desired directory and run
```
git clone https://github.com/AlexGidman/SpotifyAPI_nb
```
* Open Terminal window, cd into correct directory, and run:
```
jupyter notebook
```
* If browser does not launch automatically, copy and paste localhost URL into browser.
* Go into notebooks folder, and use the "SpotifyAPI Class.ipynb". The other notebooks show development steps taken to create API client.
* Set a client_id & client_secret.
###### Within an existing project:
* Copy and paste code snippet into existing python project.

### Obtaining client_id / client_secret
* Register a Spotify account and login to the developer site [here](https://developer.spotify.com/)
* Go to the Dashboard, and "Create An App".
* Copy and paste client_id & client_secret into notebook.

### Authors

* Alex Gidman

### Version History

* Initial Release
