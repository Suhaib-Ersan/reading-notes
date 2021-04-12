# Git, what is it? and what does it do?
![Git banner](https://miro.medium.com/max/800/0*XMMzxGh9or2Vbikv.png)
## What is Git?
Git started development around 2005, mainly because of dispute of a DVCS called "BitKeeper" and the devolopers of the project Linux kernal, which made those devolopers start their own open-source DVCS.
And then we got Git, Git is a DVCS that's mainly designed to make the life of software engineers easier while also being open-sourced, it's available on most of the major PC OS's, including _Linux_, _Windows_ and _Mac_.
So, what does DVCS mean? it's short for "distributed version control system", `distributed` because Git can work between different clients and servers, `version control sysyesystem ` because it can make sure the same files and folders exist on all of the devolopers machines.

## What are it's main features?
Git also uses some life-saver features, such as _snapshots, use of local operations, states, tracking of changes to the files_ and _minimizing loss of data._
### Snapshots
Everytime Git saves a file, it compares it to the previous version, for any new changes, it saves them, for anything that hasn't changed, it refernced them to the old version.
### Local operations
Lots of Gits operations are local, meaning they only happen on your machine, making it faster than having to ask a server for what you need, which allows you to work even if you don't have an access to the web.
### States
Files that Git has have three possible states: committed, modified and staged.
###### Commited: The data that's stored in the database.
###### Modified: Data that has been changed, but still waiting to be commited.
###### Staged: A files new version that have been choosen to be committed.
### Tracking of changes
Every change you (or your colleagues) make is tracked by Git, making it easy to backpedal when anything wrong happens.
### Minimizing loss of data
As some of the previous points suggest, Git is designed to make sure loss of data is an -extremely_ hard thing to do. 
## What about smaller features?
- Git is a big program, as such it does have a manual, can accessed though using the command `git help command` 
- You can import your older projects into Git.
- You can also clone a project from a different server.
- Being able to change many of the smaller settings in the program.
## Local Repository Structure
The local Database has three parts:
- Head, which is the latest version of the files.
- Index, which is the place for the staging.
- Working directory, your files are stored here.
## Commands
- `git status` tells you if what files you have currently are the same as the database or not.
- `git add .` stages files to be commited.
- `git commit -m "message"` command to send a message for why or what you changed.
- `git push origin main` commit the files.

<br/><br/> 
<br/><br/>

### [Home](https://suhaib-ersan.github.io/reading-notes/) &nbsp;&nbsp;&nbsp;&nbsp;   [read01](https://suhaib-ersan.github.io/reading-notes/read01)  &nbsp;&nbsp;&nbsp;&nbsp; **read02**
 