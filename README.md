# EECS496_A1_demo
# How to generate an ssh-key on Linux system?

## Motivation: you need ssh-key to log into remote server!
## Background: You use a Linux system, and are famaliar with basic bash commands. 

## Procedure: 
+ ### Open a bash terminal
+ ### Generate a key
        
        ssh-keygen -t ed25519 -C "example@example.edu" -f ~/.ssh/id_ed_new
    First argument: encryption type

    Second argument: your email address

    Third argument: file to store the key, must be in `~/.ssh` folder
+ ### Go to `~/.ssh/`, new publich key is in `id_ed_new.pub` 
