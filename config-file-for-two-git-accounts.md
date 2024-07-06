
Personal account - default config

```
Host github.com-personal
   HostName github.com
   User git
   IdentityFile ~/.ssh/id_rsa_personal

Host github.com-work
   HostName github.com
   User git
   IdentityFile ~/.ssh/id_rsa
```

```
[core]
        repositoryformatversion = 0
        filemode = true
        bare = false
        logallrefupdates = true
        ignorecase = true
        precomposeunicode = true
[remote "origin"]
        url = git@github.com-personal:pawan1210/LLD.git
        fetch = +refs/heads/*:refs/remotes/origin/*
[user]
    name = username
    email = email
~                                      
```
# using this tutorial -> https://gist.github.com/Jonalogy/54091c98946cfe4f8cdab2bea79430f9
