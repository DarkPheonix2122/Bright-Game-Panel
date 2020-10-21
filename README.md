# Bright Game Panel - PHP Game Control Panel
===================================================================
			  by warhawk3407 (warhawk3407@gmail.com)
		And Continued again by DarkPheonix2122 (jcplayz111@gmail.com)

===================================================================

http://www.bgpanel.net/
Version 0.4.5 (Release 0 DEVELOPER BETA 8)
November 23rd, 2013

===================================================================
			WEB SERVER REQUIREMENTS
===================================================================

1. Linux OS
2. PHP Version 5.3.4 or Greater
3. PHP Safe Mode Disabled
4. MySQL Database
5. Curl Extension
6. FSOCKOPEN Function
7. MAIL Function
8. MBSTRING Extension
9. BZIP2 Extension
10. ZLIB Extension
11. GD Extension
12. FreeType Extension
13. SimpleXML Extension

===================================================================
			INSTALLATION INSTRUCTIONS
===================================================================

1. Unzip the contents of the .zip file to a folder on your computer.

2. Edit the SQL settings in the file 'configuration.php' (The file must be in UNIX format - I recommend to use Notepad++). It is located in the '/upload_me' folder.

3. Upload the entire contents of the folder '/upload_me' to your website in binary mode. It is recommended to change the name of the '/admin' folder.

4. CHMOD file '/.ssh/passphrase' to 0777.

5. Run the installation script at http://www.yourdomain.com/install/index.php

6. Once complete, delete the install folder from your web server.

7. CHMOD file '/.ssh/passphrase' to 0644.

8. Do not forget to schedule the cron job.

Enjoy BrightGamePanel !

===================================================================
			UPDATE INSTRUCTIONS
===================================================================

0. READ SPECIFIC INFORMATION RELATIVE TO A VERSION UPGRADE. IT IS WRITTEN IN THE 'README UPDATE' FILE ( IF THIS FILE DOESN'T EXIST, IGNORE THIS STEP ).
	|-> Filename syntax: 'README-version-UPDATE.txt'

1. Remove all files (including the configuration.php file) from your website, both client and admin sides.
	*** IMPORTANT ***
	- YOU HAVE TO KEEP INTACT '/.ssh' DIRECTORY AT THE ROOT OF THE BRIGHT GAME PANEL INSTALL IF YOU ARE UPDATING TO A NEWER VERSION !

2. Unzip the contents of the .zip file to a folder on your computer.

3. Edit the SQL settings in the file '/upload_me/configuration.php'.

4. Delete the folder '.ssh' located in '/upload_me'.

5. Upload the entire contents of the folder '/upload_me'.
	*** IMPORTANT ***
	- DO NOT UPLOAD '.ssh' FOLDER ( IT SHOULD HAS BEEN DELETED AT STEP 4 ), OTHERWISE IT WILL OVERWRITE YOUR PASSPHRASE, MAKING BGP UNUSABLE !
	- DO NOT FORGET TO UPLOAD '.version' FOLDER IN ORDER TO OVERWRITE THE FILE '/.version/version.xml' !

6. CHMOD file '/.ssh/passphrase' to 0777.

7. Run the installation script at http://www.yourdomain.com/install/index.php
	|-> During the installation select "Update to the Last Version".

8. Once complete, delete the install folder from your web server.

9. CHMOD file '/.ssh/passphrase' to 0644.

Enjoy your updated version of Bright Game Panel !
