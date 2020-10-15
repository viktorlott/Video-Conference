# Video-conference web and server

This project was build and sold to a company that wanted a video-conference solution for peer2peer (mesh) with STUN and TURN. It also scales over to a SFU when more than 2 participants are connected. It uses a MCU for audio. The backend is built with docker, so everything is containerized and scalable.

#### Back-end
  - Nodejs
    - Socket IO is used for signaling when doing p2p, messaging or moderating room.
  - Reddis
  - TURN
  - STUN
  - Docker
  - RethingDB
  - Janus WEBRTC - Creating rooms etc
    - Custom module was built to connect to janus-server


#### Fron-end
  - React
  - WebRTC
  - Socket IO
  - Janus WEBRTC - Connecting to rooms etc
    - Custom module was built to connect to janus-server


#### Suppors
  - Room creation
  - Moderator tools 
    - kicking/inviting.
    - mute/unmute.
    - Whitelisting/blacklisting users.
  - Password protection
  - Messaging and sending files over p2p or signalserver.
  - Videos autoscales to fit window with a 4:3 minimum ratio 
  - Debug interface

#### Demo 3
![Alt Text](https://github.com/nexriz/video-conference/blob/master/video-conference3.gif)


## This project was built by me alone in my spare time.
#### Everything is created from scratch.