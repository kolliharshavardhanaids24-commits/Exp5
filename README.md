#Experiment5
ssh-keygen -t rsa -b 4096 -C "kolliharshavardhan.aids24@cmrit.ac.in"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub
git push -u origin main
git remote -v 
git branch feature-branch
git checkout feature-branch
git branch
git add .
git commit -m"Add changes to feature branch"
git checkout main
git branch
git merge feature-branch
git fetch origin
git rebase origin/main
git origin push main
