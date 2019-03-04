# remsens_bib
bibtex file for RemSens pdf library

# Initialize your local repo:
  1. Open a console and cd to your desired folder where you want to store the files on your local machine (e.g.: under ../Documents/)
  2. Clone the repo via: git clone https://github.com/KarlJohnsonnn/remsens_bib.git
     OR download the zip file: https://github.com/KarlJohnsonnn/remsens_bib/archive/master.zip
 
# Update the bib file:
  1. In the console, fetch the latest changes from the remote branch: git fetch
  2. Pull the latest changes to your local branch: git pull
  3. Update the file as you like.
  4. Add changes to the stash, again with console: git add remsens.bib
  5. Commit the changes: git commit -m ‘commit message’
     The commit message should include something like “added paper(s) XY”
  6. Safety pull, if someone pushed updates while you were editing.
  7. Push the updates to the remote branch, so everyone can pull the latest version: git push
  8. You can undo a commit by git revert <commit_hash> (the commit hash is the number and letter ID displayed on github.com when clicking on the respective commit) 

# How to edit:
  1. Please use JabRef or a plain text editor to edit the file. **Other editors such as KBibTeX mess the file up**
  2. Always add the abstract, and some key words (separated by comma, not semicolon) would be good as well. Example key words would be radar, lidar, retrieval, dust, microphysics, CDNC, Arctic,...
  3. The key is FirstAuthorYYYY, and if several papers fulfill this requirement, please use a,b,c
  4. Use journal abbreviations. JabRef has a button to "toggle abbreviation" next to the journal name field.
  5. For JabRef to recognize more journals, set it up to use "additional_journal_abbreviations.txt" as external file in Options --> manage journal abbreviations 
