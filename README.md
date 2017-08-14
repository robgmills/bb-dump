# Bitbucket Scan

A CLI utility to recursively scan an clone all repositories in an Atlassian Bitbucket/Stash instance.

## Prerequisites

### Install [Stashy](https://github.com/RisingOak/stashy)
```sh
pip install stashy
```

### Install GitPython
```sh
pip install gitpython
```

## Usage
```sh
./bb-dump -h
```

## Roadmap
- Replace subprocess.call() with [GitPython](http://masnun.com/2012/01/22/fetching-remote-git-repo-with-python-in-a-few-lines-of-codes.html) [clone](http://stackoverflow.com/questions/2472552/python-way-to-clone-a-git-repository)
