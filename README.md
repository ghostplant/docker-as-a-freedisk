# Docker as a Free Disk

- Brief: the utitlity to wrap Docker Hub as a free block chain storage to store large blob data.

--------------------------------------------------------

*Dependencies on Ubuntu*:

-	sudo apt install curl coreutils

--------------------------------------------------------

### Usage Example:

Step-1: Create a DockerHub Account in *https://hub.docker.com*, and remember your username and password;

Step-2: Use command tool to operate items in K/V store;

```sh
# set the value of a certain key:

DOCKER_ACCOUNT='username:passwd' ./dockerdisk put key1 hello-world

# get the value of a certain key:

DOCKER_ACCOUNT='username:passwd' ./dockerdisk get key1
```

Step-3: (Optional) You can make your data store private in *https://hub.docker.com/r/__username__/repo/~/settings/*
