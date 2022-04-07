# githelper
all git usages is one place!

## create ssh key

* If the ssh key not created do it with keygen command. <br>
`$ ssh-keygen -t ed25519 -C "your_email@example.com"`
* Adding your SSH key to the ssh-agent <br>
`$ eval "$(ssh-agent -s)"`
* Add your SSH private key to the ssh-agent. If you created your key with a different name, or if you are adding an existing key that has a different name, replace id_ed25519 in the command with the name of your private key file. <br>
`ssh-add ~/.ssh/id_ed25519`
* refer this link for detailed guide <br>
`https://docs.github.com/en/authentication/connecting-to-github-with-ssh`
## create a repository from command line
`echo "# test" >> README.md`

`git init`

`git add README.md`

`git commit -m "first commit"`

`git branch -M main`

`git remote add origin git@github.com:shadirvan/test.git`

`git push -u origin main`


## after making changes
* check status of git using <br> `$ git status`
* stage the changes with <br>
`$ git add .`
* commit it with <br>
`$ git commit -m "message here" -m "description"`
* push it to github with this command
`$ git push`
## push an existing repository from the command line
`git remote add origin git@github.com:shadirvan/hello.git`

`git branch -M main`

`git push -u origin main`
