
1. git config --global user.name "thapa-in"
2. git config --global user.email "mail@thapa.in"
3. touch .gitignore : For ignore some files not to upload in git repo.
node_modules/
3.1. By npm install we can create node_modules files
4. git init
5. git add .
6. git commit -m "Initial Commit"
7.Goto repo and convert HTTPS to SSH for provide access to system to upload project in gitub-repo.
8. Copy SSH address
	git@github.com:thapa-in/mysampleapp.git
9. git remote add origin git@github.com:thapa-in/mysampleapp.git
10. git push origin master : but failed (no authenticate) then make SSH key
10.1 Account Settings -> SSH and GPG keys -> New SSH Keys
10.2 Fill Title then Generate key by,
10.2.1 ssh-keygen -t rsa -b 4096 -C "mail@thapa.in"
	then asks location, you can press enter for same location .
	then press enter enter
10.2.2 copy path like "/c/Users/lenovo/.ssh/id_rsa.pub" 
10.2.3 cat /c/Users/lenovo/.ssh/id_rsa.pub then key will be show.
10.2.4 copy the key and paste it git.
11. git push origin master and Now your project pushed in github repo.
