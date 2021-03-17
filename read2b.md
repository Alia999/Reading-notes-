Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. 
 A Local VCS entails one database on your hard disk that stores changes to files.
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.
Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.
Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.
In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.
Install as a package
Install via another installer
Download and compile the source code.
In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.
Almost every type of Version Control System incorporates branching. By creating branches of a central repository, collaborators are able to work on a project simultaneously via multiple branches, without affecting this main repository.

To list local branches, use the git branch command. The branch currently being worked on will have an asterisk next to its name