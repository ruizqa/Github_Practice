<h1>
   This is a demo on how to use the <strong> command line and .git </strong>
</h1>

ls  - Shows everything under the current section we are on <br>
cd  - Change to another directory <br>
cd .. - Go up one directory <br>
mkdir - Creates a new folder <br>
touch - Creates a new file <br>
rm  -  Removes a folder or file <br>


Git commands <br>
// Initializes the local directory as a repository <br>
1) git init  <br>

// Start tracking files <br>
2) git add "NameOfFile.ext" <br>

// Save point (commit) <br>
3) git commit -m "Adding README with some commands" <br>

// Link the repositories together <br>
4) git remote add origin url-to-github-here <br>

// Uploads every change to github <br>
5) git push -u origin master <br>
   git push -u origin main <br>

// To save a new change we need to run steps 2, 3, and 5

// Show the current file tracking status 
git status 

rm -rf .git <br>
