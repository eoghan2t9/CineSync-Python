MORE IN DEPTH README TO COME BUT ALL YOU NEED ARE THE FOLLOWING:

PYTHON 3 INSTALLED 
THESE PYTHON MODULES INSTALLED: RICH, FABULOUS, IMDBPY AND GUESSIT

pip install guessit rich fabulous IMDbPY

THEN RUN THE SCRIPT LIKE

python3 Cinesync.py

THE SCRIPT CONTAINS A MAIN MENU FOR THE OPTIONS INCLUDED AND ALSO SWITCHES TO MANUALLY RUN CERTAIN PARTS

python3 Cinesync.py --watch #Run watcher mode
python3 Cinesync.py --setup #Run first-time setup
python3 Cinesync.py --service #Setup watcher to run at boot


WARNING THIS PROCESS WILL TAKE SOME TIME AS THIS SCRIPT NOT ONLY SYMLINKS THE FILES IT ALSO RENAMES THE FILE BETTER FOR THE LIKES OF PLEX AND ALSO APPENDS THE IMDB ID TO THE FOLDER THE SYMLINK IS STORED IN E.G. Batman Begins (2005) {imdb-tt0372784}