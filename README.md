# Install-MySql-Server-in-Mac-M1

Step by step process on how to install MySql Server in Macbook M1

Step 1: Open any browser (Chrome, Firefox, Safari) and go to
        https://dev.mysql.com/downloads/mysql/

Step 2: Find the suitable version and download the ".dmg" file from "Arm 64 DMG Installer".

Step 3: After it has been downloaded, open the file and install it.

To setup path
SPECIFICALLY FOR /zsh shell

Step 4: Check if .zprofile is present or not. To check, type "ls -a".

Step 5: If not present, type "touch .zprofile".

Step 6: After creating, type "open -t .zprofile". It'll open notepad.

Step 7: To copy path, go to Search -> /usr folder -> local -> mysql-8.0.31-macos12-arm64 -> bin (right-click and hold option-key and copy pathname)

Step 8: Paste the path in notepad.
        export PATH=${PATH}:path

Step 9: Save the file and close notepad and quit terminal.

Step 10: Open terminal and type "mysql -u root -p" and enter the password you created while installing mysql-server.
