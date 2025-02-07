---
layout: project
title: Flatroom
subtitle: An IRC-style chat application using sockets
---

Flatroom is a basic chat application made using flask and socket-io, with some javascript, html and css.

It lets users communicate with each other in specific channels with each other.

 - **Display Name:** When a user visits the web application for the first time, he/she is be prompted to type in a display name that will eventually be associated with every message he/she sends. If he/she closes the page and returns to the app later, the display name is still remembered.

 - **Channel Creation:** The user can create a new channel, so long as its name doesn’t conflict with the name of an existing channel.

 - **Channel List:** Users can see a list of all current channels, and selecting one allows the user to view the channel.

 - **Messages View:** Once a channel is selected, the user can see any messages that have already been sent in that channel, up to a maximum of 100 messages. The application only stores the 100 most recent messages per channel in server-side memory.

 - **Sending Messages:** Once in a channel, users can send text messages to others the channel. When a user sends a message, their display name and the timestamp of the message is associated with the message. All users in the channel then see the new message (with display name and timestamp) appear on their channel page. Sending and receiving messages happens in real time, i.e, it does not require reloading the page. 

 - **Remembering the Channel:** If a user is on a channel page, closes the web browser window, and goes back to your web application, the application remembers what channel the user was on previously and takes the user back to that channel. 


#### Implementation:

[GitHub Repository](https://github.com/shrey27tri01/Flatroom)   
[Live Demo](https://flatroom.herokuapp.com/)




