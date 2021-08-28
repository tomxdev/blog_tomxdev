+++
author = "Tom"
title = "Install Go in MacOS"
date = "2021-08-28"
description = "MacOS Go Installation Tutorial"
images = ["gopher_home.jpg",]

tags = [
    "go",
]
+++

{{<figure src="/img/install-go/gopher_banner.jpg">}}

#### :white_check_mark: What is Go?

Go is an open-source programming language developed by a team at Google. It provides easy to build simple, reliable, and efficient software. This language is designed for writing servers, that’s why it is using widely these days. At the update time of this tutorial Go 1.17 is the latest version available. This tutorial will help you to install Go 1.17 on your macOS operating system.
  &nbsp;


#### :white_check_mark: Running the installation

  We will perform all Go installation processes in 4 steps.

#### :white_check_mark: Step 1 - Download Go

To download the latest Go release visit https://golang.org/dl/. You will see the download link for Apple macOS. The current version of Go 1.17 support macOS 10.10 or later versions with 64-bit support only.


  {{<figure src="/img/install-go/windows/download-go.png" width="72%">}}
  &nbsp;

Como alternativa, você pode baixar o Go 1.17 usando a linha de comando curl.
``` bash
  $ curl -o golang.pkg https://dl.google.com/go/go1.16.4.darwin-amd64.pkg 
```

#### :white_check_mark: Step 2 - Install Go in MacOS

You have downloaded the Go package on your macOS system. To install it simply double click on the downloaded file to start the installation wizard.

Command-line users can execute the below command to start the installation.

```bash
   $ sudo open golang.pkg 
```

Follow the installation wizard and complete the installation process.

  {{<figure src="/img/install-go/mac/install-go-on-macos.png" width="72%">}}
  &nbsp;


#### :white_check_mark: Step 3 - Setup Go Workspace
EditEdit the ~/.bash_profile or ~/.profile file (or its equivalent) to set environment variables. Commonly you need to set 3 environment variables as **GOROOT**, **GOPATH** and **PATH**.

**GOROOT** is the location where Go package is installed on your system.

```bash
$ export GOROOT=/usr/local/go 
```

**GOPATH** is the location of your work directory. For example my project directory is ~/Projects/Proj1 .
```bash
$ export GOPATH=$HOME/Projects/Proj1 
```

Now set the **PATH** variable to access go binary system wide.

```bash
$ export PATH=$GOPATH/bin:$GOROOT/bin:$PATH 
```

#### Step 4 - Test Go Version :trophy:

Finally, you have successfully installed and configured go language on your system. First, use the following command to check the installed Go version.
    
```bash
$ go version

go version go1.17 darwin/amd64
```

#### :white_check_mark: Conclusão

This completes the installation of Go in the MacOS environment! :muscle: :dart:
