#Experiment5
ssh-keygen -t rsa -b 4096 -C "kolliharshavardhan.aids24@cmrit.ac.in"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub
