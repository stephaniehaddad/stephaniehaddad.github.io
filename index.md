#Assignment Questions
 
1.When should you use Git for a project?
Git is a useful method at keeping track of previous version of a project. If multiple collaborators are working on the same file, the project can be worked on simultaneously from different computers. Keeping track of codes used for any computing or statistical needs is easy because the changes are all tracked. This means, if a change is made that causes an error or conflict, or if the previous version is preferred but the script forgotten, you don't have to worry about remembering what the syntax changes were.

2.What kind of files/info should be saved in a Git repository? What types of files should not be saved? 
Codes and text files should be saved, whereas data files and confidential/case-sensitive information should *NOT* be included. This is because Git is online and accessible by anyone. 

3.What are the commands to undo a commit?
+ git commit - amend : allows you to add something to file if commit too early or edit the message
+ git reset HEAD <file> : to undo a commit from a single file 
+ git checkout -- <file> : to get the last version of the file (to undo a change)

4.One of your repositories is in a "detached HEAD" state. How do you fix this?
Since this can happen if you hit the command checkout without specifying where to go, to fix it involves using _ git checkout master_

5.Your boss has no idea what Git is or why you are using it. Explain the pros/cons of using Git for your research project. Explain the pros/cons for hosting your project in a public (or private) repository on Github/Bitbucket/Gitlab/etc.

Git for your research
Pro
+ remote access to resources
+ log tracking changes to project
+ easy collaboration 
+ free
+ good back up reservoir for work


Con
+ accessible to everyone
+ not very intuitive to learn (like a new language)
+ time intensive to master
+ file size minimum and maximum limits

Hosting project as private vs. public
Pro
+ Collaborative researchers easily contribute to public, open-source project
+ Employers can look at how often members are contributing to a project
+ Networking opportunities with other researchers/coders/developers

Con
+ Private repository cost money
+ Sensitive data files should not be stored as public
