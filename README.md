# Nautica-Web-Music-Player-for-Jellyfin

## Problem:
While creating my Jellyfin media server on my homelab, I discovered that there's no good, well-made music player that fulfills all my needs. Most services have these common roblems:
- App Store applications often contain unsafe or non private code
- Designs are boring and uncustomizable
- Developers clearly don't use their own software it lacks basic features and usability, feels boring

## Solution:
Building a Standalone Web Client that can be hosted on any Media Server that has Jellyfin running. Any Device that is in the Network is able to connect to the Webserver and has access to all Music and all Features while having the same design on all the different Devices. No need for installation, any specific OS or Software. Any Device with a Browser can access the Music. 

## Design Philosophy

I love underwhelming, slim designs because they shift focus to the album art. The interface uses a clean black-and-white aesthetic with high contrast, no flashy animations or typography. Features should just work.

!Look at the Bottom for Screenshots!

## Technical Requirments: 

As said before Metadata is very Important for the Design Language of this Music Player. 

Metadata quality is crucial for this design language. Recommended tools:

- **MusicBrainz Picard** — Automatic metadata fetching
- **MP3Tag** — Manual metadata editing

These are the best tools for finding and maintaining music information.

## Privacy

Nautica is a stateless client. Any passwords you enter are saved locally in your browser's storage — I have no access to tokens or login credentials. No data is sent to third parties. The code communicates directly with your own server.

## As of Last - Contact: 

If you have any type of Feedback or recommendations, please open an Issue, submit a Pull Req. or message me on truth_adam01@proton.me 

## Installation

See [README.md](README.md) for detailed setup instructions.

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

## License

GPL-3.0 — see [LICENSE](LICENSE)
