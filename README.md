Bash Bunny Payload: WiFi Password Stealer

This Bash Bunny payload steals saved WiFi passwords from a Windows computer and saves them in the Bash Bunny's loot directory. It works by using PowerShell to run netsh wlan show profiles and then retrieving the saved passwords for each network using the key=clear command.
Requirements

    Bash Bunny
    Windows operating system

Usage

    Connect the Bash Bunny to the target Windows computer and wait for the LED to turn green.
    The payload will automatically run and steal saved WiFi passwords, which will be saved in the Bash Bunny's loot directory (/root/udisk/loot/WifiPass/).
    Once the payload is complete, safely eject the Bash Bunny and remove it from the computer.

Files

    payload.txt: This is the Bash Bunny payload script that runs on the target computer.
    README.md: This file.
    LICENSE: The license under which this software is released.

License

This software is released under the MIT License. See LICENSE for details.
Acknowledgements

This payload was inspired by a similar payload created by Hak5
