# Cybersee: Immersive VR Meetings

A multiplayer VR meeting app built in Unity. Instead of a grid of video tiles, participants join a shared virtual room as avatars. They can move around, talk with voice chat, and gesture naturally, so online meetings feel closer to being in the same room.

## Features

- **Shared meeting rooms:** multiple users join the same virtual room in real time
- **Voice chat:** talk with everyone in the room
- **Hand presence and gestures:** avatars follow each user's head and controller movements, with animated hands, so people can point, wave and gesticulate naturally
- **Free movement:** walk around the room and join conversations
- **Menus:** main menu, avatar selection, name entry, create/join meeting and settings screens

## Tech stack

- Unity 2022.3 (LTS), C#
- XR Interaction Toolkit, OpenXR
- Photon PUN 2 (multiplayer networking)
- Photon Voice 2 (voice chat)
- Universal Render Pipeline (URP)

## My role

This was a team project. I was responsible for:

- **Movement:** VR locomotion, so users can move around the meeting room and join conversations naturally
- **Scenery setup:** building and laying out the meeting room environment
- **Voice chat:** real-time voice communication between participants using Photon Voice

## Running it

1. Clone the repository
2. Open the project in Unity 2022.3
3. Open the `MainMenu` scene
4. Build to a VR headset, or press Play with a connected headset
