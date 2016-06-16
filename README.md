#Centralized Workflow
Create a central repository (it should be a bare repository) which can be created using the command
Git - - bare init
How it works: - everyone clones the central repository 
Git clone (SSH or HTTPS)
A shortcut is created named as origin which connects with the parent repository.
The local repository is created for every developer, so that they can made changes and later on merge the changes into the central repository.
Developers can edit, stage and commit.
If one developer publishes his/her changes into the central repository, then the other developer can pull the changes of central repository and integrate with his/her changes, then only the other developer can publish his/her changes.
Changes can be posted into the central repository using: - 
Git push origin master
Changes can be pulled using: - 
Git pull –rebase origin master
