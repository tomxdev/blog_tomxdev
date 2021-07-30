+++
author = "Tom"
title = "Installing Go in Windows 10"
date = "2021-07-29"
description = "Go installation tutorial in Windows environment"
images = ["gopher_home.jpg",]

tags = [
    "go",
]
+++

{{<figure src="/img/install-go/gopher_banner.jpg">}}

#### :white_check_mark: Download installation file

  Access the [Link](https://golang.org/dl/) of the official website to download the installation file for GoLang.

  {{<figure src="/img/install-go/windows/download-go.png" width="72%">}}
  &nbsp;


#### :white_check_mark: Running the installation

  After the download is complete, double click to run the file and follow the installation steps.


  {{<figure src="/img/install-go/windows/install_next.png" width="62%">}}
  :information_source: *Start screen for installation.* \
  &nbsp;
  &nbsp; 
  {{<figure src="/img/install-go/windows/install_accept.png" width="62%">}}
  :information_source: *Click on accept the license agreement, then next.* \
  &nbsp;
  &nbsp;
  {{<figure src="/img/install-go/windows/install_path.png" width="62%">}}
  :information_source: *Select the installation folder, then next.* \
  &nbsp;
  &nbsp;
  {{<figure src="/img/install-go/windows/install_installer.png" width="62%">}} <br>
  :information_source: *Click install to start the installation, then next.* \
  &nbsp;
  &nbsp;
  {{<figure src="/img/install-go/windows/instal_running.png" width="62%">}} <br>
  :information_source: *Installation process running.*\
  &nbsp;
  &nbsp;
  {{<figure src="/img/install-go/windows/install_finish.png" width="62%">}} <br>
  :information_source: *Installation successful, click finish.* \
  &nbsp;
  &nbsp;

#### Check installed version of Go :trophy:

  Access Windows Run with the shortcut keys ***Win + R***, and type ***cmd*** to open the command line. <br>
  &nbsp;
  {{<figure src="/img/install-go/windows/win_R.png" width="52%">}}   
  &nbsp;

  
    
*At the command line type **go version** to view the installed Go version.*
  ```bash
    $ go version
  ```

  {{<figure src="/img/install-go/windows/version.png">}}
  *Viewing the installed version via the command line.* \
  &nbsp;



#### :white_check_mark: Set environment variable

Set the environment variable to GoLang

* ##### Workspace folder :heavy_check_mark:

  Create a workspace folder for Go projects.
  {{<figure src="/img/install-go/windows/create_folder_go_workspace.png">}} <br>

* ##### Environment Variable Manager :heavy_check_mark:

  *Open the environment variables manager, and click **environment variables**.* <br>

  {{<figure src="/img/install-go/windows/set_environment.png" width="62%">}} <br>


* ##### Configure the workspace :heavy_check_mark:

  In ***GOPATH*** change to the workspace folder that was created. :file_folder:

  {{<figure src="/img/install-go/windows/go_workspace_path.png" width="72%">}} <br>  

  
* ##### List ENV of Go :heavy_check_mark:

  Access Windows Run with the shortcut keys Win + R, and type cmd to open the command line.
  At the command line type ***go env*** to list the Go variables. 
  {{<figure src="/img/install-go/windows/go_workspace_env.png">}} <br>
  *And if the study is correctly configured the variable **GOPATH** will be set to the workspace.* \
  <br>

This completes the installation of Go in the Windows environment! :muscle::dart:
