# CCGL
cosmology and gravitational lensing in BNU

To add our collaboration, just follow the steps (for linux and mac):

1. $ git config --global user.name "xiaogang"
2. $ git config --global user.email "xiaogang@gmail.com"
#(option) cd ~/.ssh  # check whether the SSH key exists, if it does, delete it.
3. $ ssh-keygen -t rsa -C “xiaogang@gmail.com”
4. press 3 ENTER, then $ cd ~/.ssh/ 
5. $ vi id_rsa.pub, copy the content in "id_rsa.pub" to the GITHUB website: setting-SSH key
6. $ ssh git@github.com #test it and press "yes" to be authenticated
7. $ git clone "the HTTPS clone URL in our website"
8. $ cd CCGL
9. $ git status  #check the difference between your local files and the website
10. add or modified the local files.
11. $ git add .
12. $ git commit -m "description"
13. $ git push
14. to delete files, use $ git rm 


joygang test

