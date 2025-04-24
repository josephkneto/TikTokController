
# Embedded Systems Project

Developing a remote control interface.

## First Delivery

### Concept

The main idea is to integrate a joystick control with TikTok, allowing users to navigate the interface. By moving the joystick in one of four directions, the user can: like a video; skip to the next video; return to the previous video; or mute/unmute the audio. Additionally, a potentiometer will be used to increase or decrease the video volume based on its rotation.

### Name

JoyStiktok.

### Target Users

Potential users include people interested in a unique or alternative way to use TikTok.

### Software/Game

The controller will be used to interact with the TikTok Web interface on Desktop.

### User Journey (3 pts)

#### User Journey 1:

- A user is watching a TikTok video, but it's too loud.
- They pick up the joystick and rotate the potentiometer to decrease the volume.
- They move the joystick downward to see new videos, but accidentally skip a video they liked. So, they move the joystick upward to go back to the previous video.
- They then move the joystick to the right to like the video.
- The user continues browsing TikTok, controlling the interface with the joystick.

#### User Journey 2:

- A user is watching a TikTok video and finds the volume too low.
- They rotate the potentiometer clockwise to increase the volume.
- After the video ends, they move the joystick down to go to the next video.
- However, the new video has very loud audio, so they quickly move the joystick to the left to mute it.
- They move the joystick down again to skip the video, and to the left once more to unmute the next one.

### Commands/Feedback (2 pts)

#### Commands

**Joystick:**
- Up: go back to the previous video
- Down: skip to the next video
- Left: mute/unmute the video
- Right: like the video

**Potentiometer:**
- Manual adjustment of video volume

#### Feedback

**Joystick:**  
Haptic feedback such as vibration could be used when moving the joystick to indicate that an action has been triggered. Visual feedback could include an on-screen animation showing which action is being executed (e.g., video skipping, muting, liking).

**Potentiometer:**  
Tactile feedback could be provided through physical resistance while rotating it. Visual feedback might be a volume bar on the screen showing the current volume level.

## Inputs/Outputs (3 pts)

Each time the joystick mutes a video (left movement), the green LED will turn off. When the audio is unmuted, the green LED will turn back on.

For any joystick movement, the board's LED will blink briefly, indicating the reception of a user command.

### Design (2 pts)

<!--
Create a rough sketch of how the controller would look (this will be required in a later stage).
-->

![image](https://user-images.githubusercontent.com/79852830/226080812-e1710b83-4bfc-4d33-988c-df9c6994a957.png)
