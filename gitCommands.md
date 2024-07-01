# G i t &nbsp;&nbsp; C o m m a n d s

These commands can be used in:-

<ul><li>cmd - Windows command line (comes with Windows )</li><li>powershell	- Windows Powershell (comes with Windows )</li><li>gitbash	- Git's BASH (downloadable)</li></ul>

# B A S I C &nbsp;&nbsp; C O M M A N D S

<pre>
help                  - list all commands
help &lt;command&gt;  - show help for selected command

exit                  - exit command window

echo 'hello'              - display 'hello' to the screen (useful for script file messages
echo 'hello' >> hello.txt	- write 'hello' to a new text file

dir           - show files and directories in current directory
dir -a        - show all files, including hidden files and folders
dir --color   - show directories and files in different colours
dir -Q        - show directory and file names in double-quotes
dir -s        - show size in bytes of each directory and folder
dir -R        - list all files in all directories in current directory
dir -1        - show list as 1 file and folder per line

cd [drive]<dir>    - Change current directory
cd ..         - change directory, go up one level

</pre>

## Common Git Commands

<code>git init -b main</code>
- initialise the curent folder for Git tracking, using 'main' branch 
- this creates a hidden folder named '.git', conataing config files

<code>git --version</code>
- display the current version of Git, if installed on your PC

<code>git config --global user.name "your-github-name"</code>
- configure your default gitHub user id

<code>git config --global user.email "your-email"</code>
- configure your default gitHub email address

<code>git branch -M main</code>
- link to main branch NB: 'M' not 'm'

<code>git remote add origin 'url'</code>
- link folder to your GitHub repo e.g. url is https://github.com/komal-karir/PASCAL.git

<code>git remote -v</code>
- check you have the correct remote URL in your .git/config file

<code>git clone <github URL></code>	
- clone a remote GitHUb repo to local folder


## Sending files to an existing GitHub repo

(assume you are in the correct folder on your PC, AND a repo has been created in your GitHub

<code>git status</code>
- show amended files and those waiting to be committed to remote repository

<code>git add <fileName></code>
- add the specified file(s) ready to be committed

<code>git add *</code>
- add all amended files in to a 'container' for committing

<code>git restore --staged <filename></code>
- remove file from 'container' 

<code>git commit -m 'commit message'</code>
- close the 'container' ready for sending to GitHub

<code>git push -u origin main</code>
- finally, push to GitHUb repo
- check your GitHub repo, amended files should be there now


# O T H E R   S T U F F  
git config --global --add safe.directory '//KomNAS/NAS_DevZone/CODE-101'

to run HTML, CSS and JS			python3 -m http.server
to run a py				python3	xxx.py
