+++
author = "Tom"
title = "Installing Go in Windows"
date = "2021-07-29"
description = "Go installation tutorial in Windows environment"
images = ["gopher_home.jpg",]
tags = [
    "go",
]
+++
{{<figure src="/content/images/install-go/gopher_home.png" width="65%">}}

#### :white_check_mark: Download installation file

  Access the [Link](https://golang.org/dl/) from the official website to download the installation file for GoLang.

  <img src="/content/images/download-go.png" width="50%">\
  &nbsp;


#### :white_check_mark: Running the installation

  After the download is complete, double click to run the file and follow the installation steps.


  <img src="/content/images/install-go/windows/install_next.png" width="42%">   &nbsp;

  :information_source: *Start screen for installation.*

  &nbsp;
  &nbsp; 
  <img src="/content/images/install-go/windows/install_accept.png" width="42%"> <br>
  :information_source: *Click on accept the license agreement, then next.*
  &nbsp;
  &nbsp;
  <img src="/content/images/install-go/windows/install_path.png" width="42%"> <br>
  *Select the installation folder, then next.*
  &nbsp;
  &nbsp;
  <img src="/content/images/install-go/windows/install_installer.png" width="42%"> <br>
  :information_source: *Click install to start the installation, then next.*
  &nbsp;
  &nbsp;

  <img src="/content/images/install-go/windows/instal_running.png" width="42%"> <br>
  :information_source: *Installation process running.*
  &nbsp;
  &nbsp;

  <img src="/content/images/install-go/windows/install_finish.png" width="42%"> <br>
  :information_source: *Installation successful, click finish.*
  &nbsp;
  &nbsp;

#### Check installed version of Go :trophy:

  Access Windows Run with the shortcut keys ***Win + R***, and type ***cmd*** to open the command line. <br>
  &nbsp;
  <img src="/content/images/install-go/windows/win_R.png" width="32%">   &nbsp;

  
    
*At the command line type **go version** to view the installed Go version.*
```bash
    $ go version
  ```

  <img src="/content/images/install-go/windows/version.png" width="55%"> <br>
  Viewing the installed version via the command line.
  &nbsp;



#### :white_check_mark: Set environment variable

Set the environment variable to GoLang.

* ##### Workspace folder :heavy_check_mark:

  Create a workspace folder for Go projects.

  <img src="/content/images/install-go/windows/create_folder_go_workspace.png" width="55%"> <br>

* ##### Environment Variable Manager :heavy_check_mark:

  *Open the environment variables manager, and click **environment variables**.* <br>

  <img src="/content/images/install-go/windows/set_environment.png" width="42%"> <br>


* ##### Configure the workspace :heavy_check_mark:

  In ***GOPATH*** change to the workspace folder that was created. :file_folder:

  <img src="/content/images/install-go/windows/go_workspace_path.png" width="55%"> <br>  

  
* ##### List ENV of Go :heavy_check_mark:

  Access Windows Run with the shortcut keys Win + R, and type cmd to open the command line.
  At the command line type ***go env*** to list the Go variables.  
  &nbsp;
  <img src="/content/images/install-go/windows/go_workspace_env.png" width="55%"> <br>
  *And if I study correctly, the variable **GOPATH** will have the workspace we created.*
  <br>

This completes the installation of Go in the Windows environment! :muscle::dart:
