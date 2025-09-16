
# zeep
**Z**sh **E**nhanced **E**rror **P**rinting 

A modest Zsh plugin that makes errors impossible to miss — failed commands are shown in a clean, bordered box.

## Quick Installation 

```bash
#clone the repo 
git clone https://github.com/beaualbritton/zeep.git 
#source zeep individually:
source .zeep
#or pipe it into your zsh config:
echo 'source ~/.zeep' >> ~/.zshrc
source ~/.zshrc
```

## Features

- Auto-captures and formats stderr
- Amendable build tool config *e.g.,* (`make`, `cmake`)
- Skips interactive apps (vim, ssh, htop, etc.)

