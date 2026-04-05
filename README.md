# Nautica-Web-Music-Player-for-Jellyfin

## Problem:
While creating my Jellyfin media server on my homelab, i figured that there is no service or Application, even anything near a good and well made Service to play my music from Jellyfin that fullfilled all my needs. Most services are pretty solid and useable but bring many Problems, first of all using a Application from any App Store brings the Risk of using Code and Software that isnt safe or Private. Second the design is mostly boring and uncustomizable. Especially soon you relize that most Developers cant be using their own Software because its so boring and brings only the most basic Features. 

## Solution:
Building a Standalone Web Client that can be hosted on any Media Server that has Jellyfin running. Any Device that is in the Network is able to connect to the Webserver and has access to all Music and all Features while having the same design on all the different Devices. No need for installation, any specific OS or Software. Any Device with a Browser can access the Music. 

## Design:

I personally love underwhelming and slim designs, because that shifts the Focus on the Album Art. Thats why, as seen in the Screenshots the design is in a clean Black-white Aesthetic. High Contrasts allow the Interface to just be a Interface and not too much. No flashy Animations, no flashy Typography. Just Features that do their damn Job. Thats why it is extremely Important that every Song and Music File has a High Quality Cover Art. Well Maintained Metadata is a requirement for the best Experience. 

!Look at the Bottom for Screenshots!

## Technical Requirments: 

As said before Metadata is very Important for the Design Language of this Music Player. 

I recommmend the following Tools for all your Music Files

- Musicbrains Picard
- MP3TAG

These 2 are pretty much the best, to fing all relevant info about your Music. 

Privacy 

This is a Stateless Client. Any Type of Passwort that is typed into the Webclient is safed locally in your Browsers Storage, i do not have access to any Type of Token of Login Credentials. No data is send Thrid Party, your Data is safe. The Code communicates directly with your Own Server. 

## As of Last - Contact: 

If you have any type of Feedback or recommendations, please open an Issue, submit a Pull Req. or message me on truth_adam01@proton.me 

## Screenshots:

The Start Menu looks like that: 
<img width="1013" height="718" alt="PRJ 4" src="https://github.com/user-attachments/assets/8b7f73ce-7c48-4f07-acef-bbe2aded0cc8" />

The Albumoverview looks like that: 
<img width="995" height="754" alt="PRJ 3" src="https://github.com/user-attachments/assets/2e91078e-e2ee-4448-8c2f-7a6d986bb016" />

The Album Menu looks like this: 
<img width="986" height="830" alt="PRJ 2" src="https://github.com/user-attachments/assets/8dea4de1-179c-4a6f-aede-e0353450a06e" />

The Song Overview looks like that: 
<img width="1004" height="808" alt="PRJ 5" src="https://github.com/user-attachments/assets/c761e72a-56d9-428b-9f15-b6d27701478e" />

The Player looks like this: 
<img width="968" height="818" alt="PRJ 1" src="https://github.com/user-attachments/assets/7633110e-f741-4c0b-a66c-4e1d3cd851b4" />

This Screenshots are from a Laptop Screen, obv. the Website scales to any Tab Size and looks a bit different in any Device. \

legal: i do not own this images and pictures that are shown for demonstration, these are strictly placeholders for your own Media and they do not come with the code. 
