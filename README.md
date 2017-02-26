# Vagga for GoLang

This repo contains the vagga.yaml for having a golang development environment.

# Requirement
You need to have Vagga installed.

If you are on ubuntu:
```bash
$ echo 'deb [arch=amd64 trusted=yes] https://ubuntu.zerogw.com vagga main' | sudo tee /etc/apt/sources.list.d/vagga.list
$ sudo apt-get update
$ sudo apt-get install vagga
```

# Usage

To run GO command
```bash
$ vagga go
```

To run glide command
```bash
$ vagga glide
```
