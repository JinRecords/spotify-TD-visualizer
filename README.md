# spotify-TD-visualizer
TouchDesigner music visualizer with Spotify integration  
  
This project utilizes the [Banana_CurrentlyPlaying](https://github.com/jetXS/Banana_CurrentlyPlaying) Libary.  
An audio virtual cable program such as [vb-cable](https://vb-audio.com/Cable/) is recommended.  
TD version 2021.10330 and above is required.

# Instructions
1. Create a appliction in the [spotify developer dashboard](https://developer.spotify.com/dashboard/applications).  
2. Grab the Client ID and Client Secret from the application created.  
3. Head to TD, locate a COMP named Spotify_API at "/project1/container1/Spotify_API" and insert the Client ID and Client Secret into the text fields.  
4. Locate the "Audio Device in/out: CHOPs at "/project1" (image below) and change the in/output.  
![image](https://user-images.githubusercontent.com/45748971/150684478-7a9cbdd0-35ba-4e11-b1f9-187e8d69297f.png)  
6. ENJOY!
