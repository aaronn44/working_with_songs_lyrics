

# working_with_songs_lyrics
![Linux Support](https://img.shields.io/badge/Linux-Support-brightgreen.svg)
![Windows Support](https://img.shields.io/badge/Windows-Support-brightgreen.svg)


> :construction: Work in progress!
These scripts are for dealing with lyrics of songs. Automatically adding lyrics to songs, editing lyrics, reading lyrics and more. 


## Features
- Using Genius API, you can add lyrics to your songs and albums easily.
- But there is no need for a Genius access token.
- You can add lyrics to musics in nested folders at once.
- You can have lyrics of albums in a text file.
- You can search through all of your lyrics files.
- Also, you can read lyrics of a song in a text file, edit it and then save it back to the song file.
- Support for MP3 and M4A formats.


## Requirements and Run
It's written in python 3.6, but maybe with some modifications you can run it on python 2.  
First you need to install required packages.
```
pip install -r requirements.txt
```
And then you can run it.
```
python add_lyrics.py
```


## Instructions
After running the main script, you will need to enter a path to a folder. If you want to work with some songs, enter the root path to all of the songs you want to do something with. But if you want to search among lyrics files, enter the path to the folder that contains all .txt lyrics files.  

After that, you will see a menu to choose a function from:
 1. Set lyrics: Adds lyrics to all songs in the folder and all folders inside it.
 2. Create lyrics file: Generates a text lyrics file for each folder. If you leave the lyrics path empty, lyrics files will be placed next to the songs in the folder.
 3. Edit lyrics: Writes lyrics of songs in the lyrics_editor.txt file and you can edit them from there; Just save the file after editing and then hit enter on terminal.
 4. Search in lyrics: Asks for a search query and then looks for it in all .txt files in the entered path. It only works with text files that are generated by option 2 (the read_lyrics function).



