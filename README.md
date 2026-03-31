# Customizable-Web-Music-Player-for-Jellyfin
First of all: 

Problem:
While creating my Jellyfin media server on my homelab, i figured that there is no service or Application, even anything near a good and well made Service to play my music from Jellyfin that fullfilled all my needs. Most services are pretty solid and useable but bring many Problems, first of all using a Application from any App Store brings the Risk of using Code and Software that isnt safe or Private. Second the design is mostly boring and uncustomizable. Especially soon you relize that most Developers cant be using their own Software because its so boring and brings only the most basic Features. 

Solution:
Building a Standalone Web Client that can be hosted on any Media Server that has Jellyfin running. Any Device that is in the Network is able to connect to the Webserver and has access to all Music and all Features while having the same design on all the different Devices. No need for installation, any specific OS or Software. Any Device with a Browser can access the Music. 

Design:

I personally love underwhelming and slim designs, because that shifts the Focus on the Album Art. Thats why, as seen in the Screenshots the design is in a clean Black-white Aesthetic. High Contrasts allow the Interface to just be a Interface and not too much. No flashy Animations, no flashy Typography. Just Features that do their damn Job. Thats why it is extremely Important that every Song and Music File has a High Quality Cover Art. Well Maintained Metadata is a requirement for the best Experience. 

Installation: 

As said before, to use this Music Player you need to host the HTML on your Jellyfin Server to avoid connection issues (CORS) 

1. Locate your Jellyfin Web Folder

Linux: /usr/share/jellyfin/web/

Windows: C:\Program Files\Jellyfin\Server\jellyfin-web\

2. Upload the HTML from this Post into this folder.

3. hurray - The Server is now available at http://YOUR_IP:8096/Webserver.html (If Your Jellyfin IP looks like this http://YOUR_IP:8096/web/#/home (Standart))

Anything like logging in with your own Data should be working completely fine as of now. 

Technical Requirments: 

As said before Metadata is very Important for the Design Language of this Music Player. 

I recommmend the following Tools for all your Music Files

- Musicbrains Picard
- MP3TAG

These 2 are pretty much the best, to fing all relevant info about your Music. 

Privacy 

This is a Stateless Client. Any Type of Passwort that is typed into the Webclient is safed locally in your Browsers Storage, i do not have access to any Type of Token of Login Credentials. No data is send Thrid Party, your Data is safe. The Code communicates directly with your Own Server. 

As of Last - Contact: 

If you have any type of Feedback or recommendations, please open an Issue, submit a Pull Req. or message me on truth_adam01@proton.me 
