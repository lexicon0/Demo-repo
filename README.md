# Demo

## Clone to local machine
```
    git clone 
    cd ./Repository
    git status 
    git add. 
    git commit -m "title" -m "status"
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

