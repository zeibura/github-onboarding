# Mainframe Messenger for VS Code

Mainframe messenger is easy way how you can send message from Visual Studio Code to another user on TSO on green screen. User you send message to must be connected to a specific mainframe It uses Zowe profile to connect to mainframe. Mainframe messenger have Zowe conformance.

## How to use Mainframe Messenger

1. Make sure you have Java version 11 on you computer
2. Make sure you have Zowe zosmf profile with credentials defined
3. Open Visual Studio Code and install Mainframe messenger extension
4. In extension settings, write name of your Zowe profile in box "zowe profile"
5. Write your mainframe username and password in "username" and "password"
6. If you want use custom name on your messages, write name in box "custom name"
7. In box "host" write URL of your mainframe connection in format http(s)://host(port)
8. Create new file in your VS Code workspace with extension .txt
9. Write your message in the file 

***NOTE!!!!*** You must not write more that 80 characters in file
9. Save the file
10. In your workspace, right click .txt file and click on "send using Mainframe Messenger"
11. At top of screen show box
12. Write the mainframe username of the person you want to send message to in box

**NOTE** Person you send message to must be logged in to same mainframe server what you put in extension settings
13. Press enter to send message
