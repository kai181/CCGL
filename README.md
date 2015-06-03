# CCGL
cosmology and gravitational lensing in BNU

To add our collaboration, just follow the steps (for linux and mac):

1. $ git config --global user.name "xiaogang"
2. $ git config --global user.email "xiaogang@gmail.com"
(option) cd ~/.ssh  # check whether the SSH key exists, if it does, delete it.
3. $ ssh-keygen -t rsa -C “xiaogang@gmail.com”
4. press 3 ENTER, and you can find "id_rsa" and "id_rsa.pub"
5. copy the content in "id_rsa.pub" to the GITHUB website
6. Test it with "ssh git@github.com"
