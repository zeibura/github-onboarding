# Mainframe Messenger for VS Code

Mainframe messenger is an easy way how you can send messages from Visual Studio Code to another user on TSO on green screen. The user you send messages to must be connected to a specific mainframe connection what you configure in extension settings. Mainframe messenger has Zowe conformance and uses Zowe profile to connect to mainframe.

## How to use Mainframe Messenger

1. Make sure you have Java version 11 on your computer
2. Make sure you have a Zowe zosmf profile with credentials defined
3. Open Visual Studio Code and install the Mainframe messenger extension
4. In extension settings, write the name of your Zowe profile under "zowe profile"
5. Write your mainframe username and password in "username" and "password"
6. If you want use a custom name on your messages, write the name under "custom name"
7. Under "host" write the URL of your mainframe connection in format http(s)://host(port)
8. Create a new file in your VS Code workspace with the extension .txt
9. Write your message in the file 

***NOTE!!!!*** Your message cannot be longer than 80 characters

9. Save the file
10. In your workspace, right click .txt file and click on "send using Mainframe Messenger"
11. A box displays at the top of the screen
12. Write the mainframe username of the person you want to send the message to in the box

**NOTE** The person you send the message to must be logged in to the same mainframe server you put in extension settings

13. Press enter to send your message

## Disclaimer

This readme file exists for educational purposes only and does not describe a real extension.
