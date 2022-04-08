# Mainframe Messenger for VS Code

Mainframe messenger is an easy way to send messages from Visual Studio Code to TSO users. Users must be connected to a specific mainframe connection that you configure in extension settings. Mainframe messenger has Zowe conformance and uses Zowe profile to connect to mainframe.

##Prerequisites

1. Java version 11
2. Zowe z/osmf profile with credentials defined

## Send a Message Using Mainframe Messenger

1. Open Visual Studio Code
2. Install the Mainframe messenger extension
3. In extension settings under "zowe profile", enter the name of your Zowe profile 
4. Enter your mainframe credentials
**Note:** To use a custom name on your messages, enter the name under "custom name"
5. Under "host", enter the URL of your mainframe connection in format http(s)://host(port)
8. Create a new file in your VS Code workspace with the extension .txt
9. Write your message in the file 
**Note:** Messages have an 80 characters
10. Save the file
11. In your workspace, right click .txt file and click "send using Mainframe Messenger"
12. A dialogue opens at the top of the screen
13. Enter the mainframe username of the recipient.
**Note:** The intended recipient must be logged in to the same mainframe server where you entered the extension settings
14. Press enter to send your message

## Disclaimer

This readme file exists for educational purposes only and does not describe a real extension.
