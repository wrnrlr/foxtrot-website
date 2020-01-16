---
title: Installation Guide
---

# Installation Guide

## Install from Source
The quickest way to install Foxtrot is from it's source code. \
[Git](https://git-lfs.github.com/) and the [Large File Storage](https://git-lfs.github.com/) are needed to download the source-code.

The [Go Programming Language](https://golang.org/doc/install) is needed to build the software.

Execute the following steps 

```bash
# Clone Foxtrot repository and its submodules.
git clone --recurse-submodules https://github.com/wrnrlr/foxtrot

# Generate builtin rules that come with the expreduce submodule.
cd foxtrot/expreduce
go generate ./...

cd ..

# Install Foxtrot
go install cmd/foxtrot
```

After installing, the `foxtrot` command should be available on the `PATH` of your command line program.

### Test Installation
Verify that the installation is correct by trying the `foxtrot` command in a terminal.

```bash
foxtrot version
```

## Read Next

* [User Manual](/guide/user)
* [Keyboard Shortcuts](/guide/keyboard-shortcuts)
