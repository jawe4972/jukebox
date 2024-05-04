# Playlist Manager

This project implements a playlist manager using a doubly linked list data structure in Python. The playlist manager allows users to create multiple playlists, add songs to playlists, remove songs from playlists, and control playback.

## Data Structure

The project uses a doubly linked list to represent the playlist. Each song in the playlist is represented as a node in the linked list. The linked list allows for efficient insertion, deletion, and traversal of songs in the playlist.

The `Song` class represents a song with properties such as artist, title, and duration. The `Playlist` class represents a playlist and contains methods for adding songs, removing songs, and controlling playback.

## How to Run the Project

To run the playlist manager, follow these steps:

1. Make sure you have Python installed on your system.
2. Install the required dependencies by running the following command:
Markdown
pip install ipywidgets

3. Copy the provided code into a Jupyter Notebook or a Python script.
4. Run the code in the Jupyter Notebook or execute the Python script.
5. The playlist manager user interface will be displayed, allowing you to interact with the application.

## User Interface

The playlist manager provides a user-friendly interface for managing playlists and controlling playback. The interface includes the following components:

- **Create Playlist**: Enter a playlist name and click the "Create Playlist" button to create a new playlist.
- **Select Playlist**: Choose a playlist from the dropdown menu to view and manage its songs.
- **Current Playlist**: Displays the songs in the currently selected playlist.
- **Add Song**: Select a song from the predefined list and click the "Add Song" button to add it to the current playlist.
- **Remove Song**: Select a song from the current playlist and click the "Remove Song" button to remove it from the playlist.
- **Play/Pause**: Click the "Play/Pause" button to toggle playback of the current song.
- **Repeat**: Click the "Repeat" button to cycle through the repeat modes (No Repeat, Repeat Song, Repeat Playlist).
- **Next**: Click the "Next" button to play the next song in the playlist.
- **Previous**: Click the "Previous" button to play the previous song in the playlist.

The user interface also displays the currently playing song and its remaining duration.

## Functionality

The playlist manager provides the following functionality:

- Create multiple playlists with unique names.
- Add songs to a playlist from a predefined list of songs.
- Remove songs from a playlist.
- Play and pause the current song.
- Skip to the next or previous song in the playlist.
- Toggle repeat modes (No Repeat, Repeat Song, Repeat Playlist).
- Display the currently playing song and its remaining duration.


## Future Enhancements

Some potential enhancements for the playlist manager include:

- Ability to reorder songs within a playlist.
- Saving and loading playlists from files.
- Integration with music streaming services for a larger song library (I really would have liked to have added this functionality but I was struggling with its implementation. 
- Improved user interface with more advanced playback controls.
