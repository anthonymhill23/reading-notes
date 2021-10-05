# Notes on Git Tutorial Reading

To understand why Git is such an important tool for software development , you first need to understand what version control is.
Version control in the simpliest manner is a way to have redundency in programs or projects, It allows you to save multiple version of a project, both on and off line of a project, as well as annonatioing who and when the changes were made. The reason this can be **VITAL** to a project is due to errors made by people and code being deleted. A very recent example of that would be  the error of facebook on 4 OCT 2021. Facebook lost a very large amount of code and didnt have a proper back up on its sloud, so all of it services were down. No company wants its infanstructure to be gone from just a simple accidental code loss. There are three forms of ways to back up codes. Here are the three ways

## Local Version Control
Many years ago, changes were stored on your hard drive. This isnt the most efficent manner due to minimal redundency. If that hard drive is destroyed or even lost, all the code is gone. This method is seldomly used. 

## Centralizied Version Control System
A more commonly used  method of redendency is Centralizied Version Control System or CVCS for short. CVCS is basicaly  storing  all things on a central server so that all members of a team can access the project, This can be helpful for assigning tasks and allowing revisions to be delagted to specific personal. It also allows programers to also have specific knowledge of team members activities in certain files. So A very capable amethod of workibng together on a project. It does have one flaw, and that is still no true back up if a server should happen to crash or fail.

## Distributed Version Control System
THe most efficent version of a  system with redundency is a Distributed Version Control System or DVCS for short. This allows you to add a perfect copy from the main server, make changes and then reupload them to the main server. Why is this important? Because the version you saved is also on your local computer, so that if something was to happen to the server, you have a back up on your local PC. This results in possibly minor down time, and increases connectivity across all aspects. 


## So what is Github?
GitHub is a DVCS that stores things in whats called a snapshot. Any time that you change a project and commit or save it (a commit is a save) It saves the file and snapshots a reference to it. It allows you to use certain commands to add, clone and push back to the server. There is also a command to PULL from the server in case you made changes on the server and not locally, although it can be hard to rectify that some times. Git mostly relies on local operations because most necessary information can be found in local resources also know as local computers. Every single thing that happens in GITHub is tracked, even locally, so if an error or corruption happens, GitHub can track and alert the user. 

# History of GitHub
[Here is the wiki page for GitHub if you wish to learn about the history](https://en.wikipedia.org/wiki/GitHub)







All together, GitHub is an amazing CVCS. Its user friendly  and great for backups!! 💪
