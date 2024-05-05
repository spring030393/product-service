ssh-keygen -t ed25519          // generate ssh
ssh-add -l                     // list ssh
ssh-add ~/.ssh/id_techtara     // add ssh
ssh-add -d ~/.ssh/id_techhara  // remove ssh


or 

# github account
Host github.com
HostName github.com
PreferredAuthentications publickey
IdentityFile ~/.ssh/id_rsa_myaccount_github

# gitlab account
Host gitlab.com
HostName gitlab.com
PreferredAuthentications publickey
IdentityFile ~/.ssh/id_rsa_myaccount_gitlab

# gitlab company account
Host gitlab.my_company.com
HostName gitlab.my_company.com
PreferredAuthentications publickey
IdentityFile ~/.ssh/id_rsa_mycompanyaccount_gitlab