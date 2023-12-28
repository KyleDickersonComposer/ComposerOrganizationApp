Composer Organization App
---
This is an app that will automatically set up project structure that will suit media composition.
Maybe this could help with organization by automatically updating some spreadsheets and pushing changes to a git repo or maybe do some backup things like a background service.

Maybe we could put a simple Maui wrapper on this console app or something. 
Or, maybe a website or something.

Structuring the Spreadsheet
---
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
![Alt a file structure](images/Screen%20Shot%202023-12-27%20at%201.52.07%20PM.png)

Here are some links to relevant APIs:
---
- [Google Docs API](https://developers.google.com/docs/api/how-tos/overview)

- [Google Sheets API](https://developers.google.com/sheets/api/guides/concepts)

- [Dropbox API](https://www.dropbox.com/developers/documentation/http/overview)


I guess you have to make a google cloud account to manage the Google APIs...
This is pretty inconvenient if you want other people to use this app. I would either have to host all the cloud stuff myself or they would have to manage the cloud stuff themselves(bad!).

I'm just make a google workplace with a bunch of javascript stuff to generate the files. Not that crazy.