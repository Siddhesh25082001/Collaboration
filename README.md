# Collaboration

## Normal Git Commands
'''
git clone <'git repo'>
'''
'''
touch <fileName.type>
'''
'''
code <fileName>
'''
'''
- git add .
'''
'''
git commit -m "message"
'''
'''
git push (in case of main)
'''
'''
git push origin <branchName> (in case of subBranches)
'''
  
If anything has been added in the staging area and we dont want to commit it and also not delete it, then we save it in the stack 
- git stash (makes the staged changes to unstaged and saves in the stack therby making working tree clean)
- git stash pop (bring back the changes from the stack)
  
## Branching
- git branch <branchName>
- git checkout <branchName> (to switch to different branch)
  - git branch (to check the current and other branches)
  
## Merging
- git checkout <branchName> (jisme merge karna hai)
- git merge <branchName> (jisko merge karna hai)
- git pull (yeh jo bhi pull karega woh current branch mein karega)
- git push 
  
- To pull content from one branch to another 
- git pull origin <branchName>
  
## Delete the Branch
- Locally delete
- git branch -d <branchName>
  
- Github delete
git push origin --delete <remote-branch-name>
  
Fork and Pull from Github 
- Fork a repo
- Change the required changes
- Send a pull request
