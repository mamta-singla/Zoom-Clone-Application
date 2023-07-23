# Zoom Clone Application
The video meeting website is designed to facilitate online video conferences with real-time video streaming and a chat menu for text-based communication among participants. The website aims to provide a seamless and user-friendly experience for starting and joining meetings, as well as managing audio and video settings during the meetings.

# Features:

## Start New Meetings: 
Users can initiate new video meetings by clicking on the "Start New Meeting" button. This will generate a unique meeting room or ID that can be shared with others to join the meeting.

## Join Meetings:
Participants can join a meeting by entering the unique meeting room or ID provided by the meeting host.

## Audio Control (Mute/Unmute): 
During the meeting, each participant will have the option to mute or unmute their audio, allowing them to control their own microphone.

## Video Control (Enable/Disable): 
Participants can enable or disable their video feed, giving them the flexibility to choose when to display their video during the meeting.

## Real-Time Chat Menu: 
The website will feature a chat menu that enables participants to send text messages to all other joined members. This allows for instant communication and information sharing during the meeting.

# Tech Stack and Skills Used:

## HTML: 
HTML will be used for structuring the website's layout and content.

## CSS: 
CSS will be utilized for styling the website, ensuring an attractive and user-friendly interface.

## Node.js: 
Node.js will serve as the server-side runtime environment. It provides the ability to handle asynchronous tasks and real-time interactions efficiently.

## WebRTC (Web Real-Time Communication): 
WebRTC is a key technology for enabling real-time audio and video communication directly within the web browser, allowing seamless video conferencing without the need for external plugins or software.

## Socket.io:
Socket.io is a JavaScript library that enables real-time, bidirectional communication between the web browser and the server. It will be used to manage real-time chat functionality, ensuring that messages are sent and received instantly.

# Project Flow:

## Meeting Initiation:

When a user clicks on the "Start New Meeting" button, the server will generate a unique meeting ID and set up a new meeting room.
The host will be directed to the video meeting interface with their video and audio enabled by default.
Joining a Meeting:

## Participants can enter the unique meeting ID on the website's homepage to join an existing meeting.
Upon joining, participants will be directed to the video meeting interface with their video and audio settings enabled.

## Audio and Video Control:

Participants can toggle their audio and video settings on the video meeting interface.
These settings will be communicated to the server using WebRTC, which will update the streams accordingly.

## Real-Time Chat:

The chat menu on the meeting interface will allow participants to type and send messages.
Socket.io will be used to send these messages to the server and broadcast them to all other participants in the same meeting room in real time.

## Ending the Meeting:

The host can choose to end the meeting, which will close the meeting room and disconnect all participants.
Participants can also leave the meeting voluntarily, which will update the meeting room accordingly.
