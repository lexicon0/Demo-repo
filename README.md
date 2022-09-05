# Demo

## Clone to local machine
```
    git clone 
    cd ./Repository
    git status 
    git add. 
    git commit -m "title" -m "description"
    # modify existing file
    git commit -am
    git push origin main
    git pull origin main
```
## SSH Agent 
Run in PowerShell
```
    Get-Service ssh-agent | Set-Service -StartupType Automatic -PassThru | Start-Service
    start-ssh-agent.cmd
```

## SSH Keys
```
    ssh-keygen -t rsa -b 4096 -C "xligd@connect.ust.hk"
    ssh -i path/to/private/key -T git@github.com
    ssh-add path/to/private/key
```

## Git branching
```
    git branch
    git checkout -b new_branch_name
    git diff branch_name
    git merge 
    git branch -d 
    
```

## Reset
```
    git reset HEAD~1
```