1. Open Project in windows explorer.
1. Type "CMD" in address bar and press "enter"
1. Command Prompt will open with path of your project
1. Type command "NPM INSTALL -G FIREBASE-TOOLS"
1. Type command "FIREBASE LOGIN"
   - If already logged in then msg will show "you are logged in"
   - If you are not logged in then Browser will open with firebase login page
1. Type command "firebase init" (for initialize all things ready to upload)
   - Are you ready to proceed ? (Y/N) then you type "Y".
   - Which services you want to use like
      - Database, Firestore, Functions, Hosting, Storage, etc.
      - Select "Hosting" by up-down arrow keys and space bar key.
      - press "ENTER"
  - Please select an option (for new project / exist project or else)
      - select "exist project..."
  - Select a default firebase project for this directory. (exist project name)
      - selct desired project.
  - What do you want to use as your public directory? (public) 
      - type name of you build project folder name that contains files like "build"
		- No problem if you not build your project, after complete initializing and before deploy you can build help of these following steps.
		- go to project folder in cmd
		- type command "NPM RUN BUILD"
	- Configure as a single page app (rewrite all urls to /index.html)? (y/N) then we type "N"  
1. Type command "FIREBASE DEPLOY"
  - after deploy a link given by cmd 
  - help of this link we can see project running in chrome or other browser.
