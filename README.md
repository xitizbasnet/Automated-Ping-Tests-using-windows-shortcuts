# Automated-Ping-Tests-using-windows-shortcuts
Automated Ping Tests using windows shortcuts 

Start

These tools are invaluable for assessing network reachability between devices, especially when direct access to those devices isn’t possible and on-site staff may not be technically proficient.

While you could instruct the user over the phone to navigate through their system to open a command prompt—clicking the Windows icon, entering commands, etc.—there’s a more efficient solution. 

By creating a couple of shortcuts and placing them on the desktop in advance, you can simply ask the user to double-click the shortcut whenever they encounter an issue and then report back the output.

To create these shortcuts, right-click on the desktop or in the desired folder and select "Create Shortcut." From there, you can easily configure the shortcuts to run specific network diagnostic commands.

Then, in the Create Shortcut pop-up window, where it is asking for a path, type "C:\Windows\System32\cmd.exe" /k ping 8.8.8.8",
(or whatever destination you want that workstation to ping). Then click next.

![image](https://github.com/user-attachments/assets/0aea0391-880b-4d0b-b680-913a8008a390)

Now give the shortcut a descriptive name that the user will understand. for example i will name it as Google Ping Request. 

![image](https://github.com/user-attachments/assets/49c61d21-07ab-46bb-bd97-5c2a5fa514ac)


Now we have the shortcut, with the descriptive name and all the user has to do is bouble click it to get it run.

![image](https://github.com/user-attachments/assets/4da5815d-4c60-42d0-bab6-4bbf1a13716d)

Done.

Finish



