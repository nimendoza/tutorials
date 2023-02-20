# tutorials

A repository of my undertaken endeavors when it comes to learning new technologies.

## Getting Started

Note: I used WSL as my chosen environment, so I could only give directions with regard to Unix-based systems.

Ensure that you have your ssh-agent running in the background.

```shell
$ eval $(ssh-agent -s)
Agent pid _
```

Add your github ssh-key to the ssh-agent

```shell
$ ssh-add <path_to_your_ssh_key>
Identity added: <path_to_your_ssh_key> (<your_email>)
```

Clone the repository

```shell
$ git clone git@github.com:nimendoza/tutorials.git <path_to_store_repository>
Cloning into '<path_to_store_repository>'...
remote: Enumerating objects: _, done.
remote: Counting objects: 100% (_/_), done.
remote: Compressing objects: 100% (_/_), done.
remote: Total _ (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (_/_), done.
```

Move to the directory of the repository (`cd <path_to_store_repository>`)

Feel free to browse each folder! Each folder contains a `README.md` that showcases the flow of the tutorial as well as the implementation of it.
