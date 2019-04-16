# Report for homework 3. In this exercise I am learning to use Git. 

I begin the exercise by creating an account on github and installing git on my guest os (xubuntu). Command for installing git on xubuntu was sudo apt install git.
After creating an github account and installing git, I wanted to clone my repository which I have just made, so I could access it with xubuntu.

Before cloning the repository, I added my name and email information on git by using command git config. Now my teammates could look me up on git log.

Now I wanted to clone my repository. On my github account under that repository which I want to clone, is a button "clone or download" which gives and url address.
Then simply I gave command "git clone <my.repo.url>" now I could acces all my github files on xubuntu.

Then some explanation of commands. "git log" command shows commit logs. This means that I can find dates and times for all commits made in this repository, which user made them and the comments for commits. In my case there were only four events on that log, because I haven't done many commits yet. 

Im not sure what command "git diff" supposed to do...

With "git blame" command it is possible to check what revision and author last modified each line of a file. I checked this file with git blame: git blame --show-stats Raportti.md. It shows details of the author and modifying date and time for each line of code. Since I made first changed to that file using my github account, it shows two different names as authors. I gave different name when using command git config.  

Then I made some stupid modifications to this report. I typed couple of lines "asdadasdasd". I didn't make the commit yet, and I used git blame command to check how does it look. Modifications were listed there, but after I typed "git reset --hard" the stupid modifications on the report were gone. 







