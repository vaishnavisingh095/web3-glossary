git init - use when you are starting a new project locallly.
git clone https://github.com/username/project-name.git- use this when someone already made a repo on github and now you want to clone , download or work on it .
git add filename
# or add everything 
git add .
git commit -m "Added intro section to README" -Save what I just added, and here’s a note on what I did.
git push-Push uploads your commits to GitHub so they’re saved in the cloud.

## For a new project:
bash
Copy
Edit
mkdir web3-glossary
cd web3-glossary
git init
touch glossary.md  # or create a file manually
git add .
git commit -m "Initial commit with glossary"
git remote add origin https://github.com/YOUR-USERNAME/web3-glossary.git
git push -u origin main

## For an existing GitHub repo:
bash
Copy
Edit
git clone https://github.com/YOUR-USERNAME/web3-glossary.git
cd web3-glossary
git add .
git commit -m "Updated glossary with new terms"
git push

Stage the Changes
"Telling Git which files you want to save.


