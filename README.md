# Project2 - "Flack - Online Chat" (JavaScript, Flask Socket.IO)
- Description: Basic Online Chat Application - Flack
- Video overview of the completed project: https://youtu.be/_x0MUs_HsFM
- Task specification: https://docs.cs50.net/ocw/web/projects/2/project2.html
- Course: CS50's Web Programming with Python and JavaScript


## Files and sections
1. application.py
    * Import libraries and other setup
    * Variables
    * Route events
    * Socketio events
    * New way of initialization
2. index.js
    * Variables
    * Page Settings On-Load
    * Client Event Handlers
    * Server WebSocket Event Handlers
    * Functions
3. index.html:
    * name and rooms
    * messages

## Requirements

- Display Name: When a user visits your web application for the first time, they should be prompted to type in a display name that will eventually be associated with every message the user sends. If a user closes the page and returns to your app later, the display name should still be remembered.
- Channel Creation: Any user should be able to create a new channel, so long as its name doesn’t conflict with the name of an existing channel.
- Channel List: Users should be able to see a list of all current channels, and selecting one should allow the user to view the channel. We leave it to you to decide how to display such a list.
- Messages View: Once a channel is selected, the user should see any messages that have already been sent in that channel, up to a maximum of 100 messages. Your app should only store the 100 most recent messages per channel in server-side memory.
- Sending Messages: Once in a channel, users should be able to send text messages to others the channel. When a user sends a message, their display name and the timestamp of the message should be associated with the message. All users in the channel should then see the new message (with display name and timestamp) appear on their channel page. Sending and receiving messages should NOT require reloading the page.
- Remembering the Channel: If a user is on a channel page, closes the web browser window, and goes back to your web application, your application should remember what channel the user was on previously and take the user back to that channel.
- Personal Touch: Add at least one additional feature to your chat application of your choosing! Feel free to be creative, but if you’re looking for ideas, possibilities include: supporting deleting one’s own messages, supporting use attachments (file uploads) as messages, or supporting private messaging between two users.
- In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project. Also, include a description of your personal touch and what you chose to add to the project.
- If you’ve added any Python packages that need to be installed in order to run your web application, be sure to add them to requirements.txt!
- Beyond these requirements, the design, look, and feel of the website are up to you! You’re also welcome to add additional features to your website, so long as you meet the requirements laid out in the above specification!
