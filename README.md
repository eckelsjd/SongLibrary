# song_library
## Motivation
The idea for this project was motivated by the desire to categorize music quickly and easily to user-customizable preferences. Personally, I have many different ideas of how music can be categorized, such as by genre, time period, emotion level, artist, the occasion, the physical setting, the task at hand, the group of people, etc. These categories are not mutually-exclusive, and they have many subcategories; one song might fit into multiple categories and subcategories at the same time, as determined by user preferences. A system should be in place allowing users to quickly and efficiently make and track playlists according to their preferences.
## Project description and scope
The goal of this project is to utilize the Spotify API in tandem with Excel to create an auto-playlist-generating system from an Excel spreadsheet. In order to provide maximum clarity, organization, and ease in creating and editing multiple Spotify playlists, the user would simply add their desired songs into an Excel spreadsheet, tag them with all desired metadata (including genre, emotion level, release date, music setting, etc.), and auto-generate any number of Spotify playlists based on their indicated preferences.

The system should also work the opposite direction, such that a user could add any number of songs to their Spotify library, and the Excel spreadsheet would be auto-populated with these new entries, including all desired metadata.

The system would be user-customizable, allowing a user to add any new music-categorization labels they desire and be able to populate new playlists based off these labels. 

## Project status
Currently, the `song_library.xlsm` Excel spreadsheet has a list of over 800 Spotify songs that are tagged and categorized by various metadata labels. The spreadsheet utilizes VBA code and Excel macros to visually display and organize the master song list. The third sheet in the file includes detailed instructions for usage of the Excel workbook for playlist categorization and creation. 

Auto-playlist-generation functionality and integration with the Spotify API, as expressed in the project scope, has not yet been implemented. Spotify playlists were created by hand from the categories defined on the Excel workbook `song_library.xlsm`; a task quite obviously inefficient and in need of a system as described in the project description.