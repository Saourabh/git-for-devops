# Git for Devops

This repository is for understanding Git for Devops concepts  



If you are seeing this is Github it means it was pushed form my local ubuntu ec2 instance to github using token method

Github > Account Settings > Developers Setting  > Personal access token > Tokens Classic > 

Copy that token from github and paste in place of password in local machine while pushing new git repository on github


If you are reading this line on GIt Hib it came using ssh method 
Local > cd .ssh > ssh-keygen this will generate public and private key > Cat pub >

Copy that public key go to github > Settings > SSH and GPG key > genrate new SSH key > paste that public key there

Go back to your resposiroty code > ssh > copy that github@githib.com > 

Go to local > inside the folder > git remote set-url origin paste that githib.com from previous step here
You have now se the git orogin to ssh  you can confirmthat using git remote -v 
