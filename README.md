# githelper
all git usages is one place!

## create ssh key

* If the ssh key not created do it with keygen command. <br>
`$ ssh-keygen -t ed25519 -C "your_email@example.com"`
* Adding your SSH key to the ssh-agent <br>
`$ eval "$(ssh-agent -s)"`
* Add your SSH private key to the ssh-agent. If you created your key with a different name, or if you are adding an existing key that has a different name, replace id_ed25519 in the command with the name of your private key file. <br>
`ssh-add ~/.ssh/id_ed25519`
## create a repository
easy way to create a repository is by going to github and create one. and follow the instructions

## after making changes
* check status of git using <br> `$ git status`
* stage the changes with <br>
`$ git add .`
* commit it with <br>
`$ git commit -m "message here" -m "description"`
* push it to github with this command
`$ git push`

