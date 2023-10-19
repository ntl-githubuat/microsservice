# Step-1
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/ntl-githubuat
ssh -T git@github.com
