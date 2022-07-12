![EFV Logo](https://github.com/TheScruffyKat/EOSforVR/blob/main/github/EOSforVR_XS.png?raw=true)

**Easily Add Free Networking To Your VR Game Using EOS Relay Servers! (Not licensed or endorsed by Epic Games)**

[Want to easily use Photon in your game? Check out PhotonVR by fchb!](https://github.com/fchb1239/PhotonVR)

> ⚠️This package is not finished yet


## This package is not possible without these amazing packages!

[Mirror Networking](https://github.com/vis2k/Mirror)

[EpicOnlineTransport](https://github.com/FakeByte/EpicOnlineTransport)

## Documentation

# Joining Privates
To join a private, just run this code with the designated room name

```EOSforVR.JoinPrivate("MyRoomNameString");```

# Matchmaking / Publics
To matchmake and join a room automatically, run the following code

```EOSforVR.Matchmake();```

This will work out of the box, but to specify what kind of match should be joined, you can add a room parameter (string)

A queue can be any string you want, such as "infection". You will only matchmake with those who have the same queue. Obviously you can do multiple parameters, like this for example "infection:forest". The colon is optional and just a visual way to see the "separate" options

Example with queue: ```EOSforVR.Matchmake("mainRoom:hunt:competitive");```

# Leaving rooms
To leave a room, just run this code:

```EOSforVR.LeaveRoom();```
