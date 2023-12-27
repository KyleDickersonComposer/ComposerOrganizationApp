Composer Organization App
---
This is an app that will automatically set up project structure that will suit media composition.
Maybe this could help with organization by automatically updating some spreadsheets and pushing changes to a git repo or maybe do some backup things like a background service.
Your wav files should be in the bWAV format which embeds timecode data in the metadata. The file name should be formatted thus: TCL_3m07_v2_10163203 (Three letter project id, cue number, version number, SMPTE dd:hh:mm:ss:ff). 
If you are delivering stems add _StemName.

Or, Something like:
- ABC/S1_E10_1m01

A glorious image from this git repo!
![Alt A picture of a spread sheet](images/Screen%20Shot%202023-12-26%20at%2010.54.52%20PM.png)
This is a sample spreadsheet for a tv show gig showing:
- cue number
- cue name
- timecode start
- timecode end
- timecode duration
- demo uploaded
- Feedback notes?
- Revision Uploaded
- Executive Approved?
- Sent to Orchestrator?
- LA Guitar (musician)
- Air1 Drums (musician)
- PC Percussion (musician)
- Bass (musician)
- Air 1 String (recording session)
- Stemmed?
- In Tools?
- Mixed? 
- Mix Good? 
- Delivered? 
- Tempo
- TC running total

When giving cue numbers the right side of the m should continue iterating and the left side should reflect the reel number.

Going to look at what those books have to say about project management. (LOL, nothing...)

Here is a mock folder structure that Gippity generated.
---
Project_Name/
|-- Assets/
|   |-- Audio/
|   |   |-- Music/
|   |   |   |-- Level_1/
|   |   |   |   |-- Track_1/
|   |   |   |   |   |-- Version_1/
|   |   |   |   |   |   |-- Track_1_Main.wav
|   |   |   |   |   |   |-- Track_1_Instrumental.wav
|   |   |   |   |   |   |-- ...
|   |   |   |   |-- Track_2/
|   |   |   |   |-- ...
|   |   |   |-- Level_2/
|   |   |   |-- ...
|   |   |-- Sound_Effects/
|   |   |   |-- Environment/
|   |   |   |   |-- Footsteps.wav
|   |   |   |   |-- Door_Open.wav
|   |   |   |   |-- ...
|   |   |   |-- Characters/
|   |   |   |-- ...
|   |-- Images/
|   |   |-- Cover_Art/
|   |   |-- Level_1_Screenshots/
|   |   |-- Level_2_Screenshots/
|   |   |-- ...
|   |-- Videos/
|   |   |-- Trailers/
|   |   |-- Behind_the_Scenes/
|   |   |-- ...
|
|-- Documents/
|   |-- Project_Plan/
|   |-- Creative_Brief/
|   |-- Track_List/
|   |-- Licensing/
|   |-- ...
|
|-- Project_Files/
|   |-- DAW_Projects/
|   |   |-- Level_1/
|   |   |   |-- Track_1/
|   |   |   |-- Track_2/
|   |   |   |-- ...
|   |   |-- Level_2/
|   |   |-- ...
|   |-- MIDI_Files/
|   |-- Sheet_Music/
|   |-- ...
|
|-- Exports/
|   |-- Final_Mixes/
|   |   |-- Level_1/
|   |   |   |-- Track_1/
|   |   |   |-- Track_2/
|   |   |   |-- ...
|   |   |-- Level_2/
|   |   |-- ...
|   |-- Stem_Mixes/
|   |-- Mastered_Tracks/
|   |-- ...
|
|-- Backups/
|   |-- Version_1/
|   |-- Version_2/
|   |-- ...
|
|-- Tools/
|   |-- Sample_Libraries/
|   |-- Virtual_Instruments/
|   |-- Plugins/
|   |-- ...
|
|-- README.md
|-- LICENSE.txt
|-- CHANGELOG.md
|-- CONTRIBUTORS.md
|-- .gitignore
|-- .editorconfig
|-- ...

