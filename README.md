# Basic - Initial setup for Git and GitHub.
Step-1: Download Git for Deskrop link: https://git-scm.com/downloads.
Step-2: Install Git Standalone Installer - Git for Windows/x64 Setup.
Step-3: It will install Git GUI, Git Bash and Git CMD.
Step-4: go to folder in which you want the git to be working and type command : git init > you will see the hidden folder Command : ls -lart.
Step-5: Create a GitHub Account : https://github.com/joelpmuni.
Step-6: Create a Repository "Example: Basic".
Step 7: Crate ssh Key to communicate with GitHub, use Git Bash on Local desktop - command : ssh-keygen.exe -t ed25519 -C m4j_joelpmuni@gmail.com > enter passphrase.
Step-8: Evaluate the key with command : eval "$(ssh-agent -s)" ssh-add ~/.ssh/id_ed25519 > Copy the Key /c/Users/joelp/.ssh/id_ed25519.
Step-9: Enter the Global infromation command: git config -- global user.name joel.m4j > git config -- global user.email joelpmuni@gmail.com.
Step-10: Add the ssh key in GitHub Settings > SSH and CPG Keys > Add Key.
Step-11: connect to GitHub via local Laptop git.
Step-12: command: Git Pull to get the repository from GitHub to git Laptop. to check command: git remote -v. 
Step-13: Update the File in Git Laptop > Git add "Filename" to Track the File > git commit -m "Message" to save > git push to update the file in GitHub. Command: git add && git commit -m "gg" && git push.
Step-14: Create a branch command: git checkout -b "branch name". Verify git cherry-pick, git merge and git rebase. git checkout "brancename" to move between the branches. git log > git log "branch name" to check invidual logs.



