+++
author = "Tom"
title = "Instalando Go no Windows"
date = "2021-07-29"
description = "Tutorial de instalação de Go no ambiente Windows"
images = ["gopher_home.jpg",]

tags = [
    "go",
]
+++

![gopher](/content/images/install-go/gopher_home.jpg)
{{<figure src="../content/images/install-go/gopher_home.png" width="65%">}}

#### :white_check_mark: Download do arquivo de instalação

  Acesse o [Link](https://golang.org/dl/) do site oficial para realiazar o download do arquivo de instalação para GoLang.

  <img src="/content/images/download-go.png" width="50%">\
  &nbsp;


#### :white_check_mark: Executando a instalação

  Após o download estar finalizado, clique duas vezes para executar o arquivo e seguir as etapas de instalação.


  <img src="/content/images/install-go/windows/install_next.png" width="42%" align="center">   &nbsp;

  :information_source: *Tela de início para a instalação.*

  &nbsp;
  &nbsp; 
  <img src="/content/images/install-go/windows/install_accept.png" width="42%" align="center"> <br>
  :information_source: *Clique em aceitar o contrato de licença, e em seguida next.*
  &nbsp;
  &nbsp;
  <img src="/content/images/install-go/windows/install_path.png" width="42%" align="center"> <br>
  *Selecione a pasta de instalação, e em seguida next.*
  &nbsp;
  &nbsp;
  <img src="/content/images/install-go/windows/install_installer.png" width="42%" align="center"> <br>
  :information_source: *Clique em install para inicializar a instalação, e em seguida next.*
  &nbsp;
  &nbsp;

  <img src="/content/images/install-go/windows/instal_running.png" width="42%" align="center"> <br>
  :information_source: *Processo de instalação em execução.*
  &nbsp;
  &nbsp;

  <img src="/content/images/install-go/windows/install_finish.png" width="42%" align="center"> <br>
  :information_source: *Instalação realizada com sucesso, clique em finish para encerrar.*
  &nbsp;
  &nbsp;

#### Checar a versão de Go instalada :trophy:

  Acesse o Executar do Windows com as teclas de atalhos ***Win + R***, e digite ***cmd*** para abrir a linha de comando. <br>
  &nbsp;
  <img src="/content/images/install-go/windows/win_R.png" width="32%" align="center">   &nbsp;

  
    
*Na linha de comando digite **go version** para visualizar a versão de Go instalada.*
```bash
    $ go version
  ```

  <img src="/content/images/install-go/windows/version.png" width="55%" align="center"> <br>
  Visualização da versão instalada através da linha de comando.
  &nbsp;



#### :white_check_mark: Configurar variável de ambiente 

Configure a variável de ambiente para GoLang

* ##### Pasta de workspace :heavy_check_mark:

  Crie uma pasta de workspace para os projetos Go.

  <img src="/content/images/install-go/windows/create_folder_go_workspace.png" width="55%" align="center"> <br>

* ##### Gerenciador de variável de ambiente :heavy_check_mark:

  *Abra o gerenciador de variáveis de ambiente, e clique em **variáveis de ambiente**.* <br>

  <img src="/content/images/install-go/windows/set_environment.png" width="42%" align="center"> <br>


* ##### Configure o workspace :heavy_check_mark:

  Em ***GOPATH*** altere para a pasta workspace que foi criada. :file_folder:

  <img src="/content/images/install-go/windows/go_workspace_path.png" width="55%" align="center"> <br>  

  
* ##### Listar ENV de Go :heavy_check_mark:

  Acesse o Executar do Windows com as teclas de atalhos Win + R, e digite cmd para abrir a linha de comando.
  Na linha de comando digite ***go env*** para listar as variáveis de Go.  
  &nbsp;
  <img src="/content/images/install-go/windows/go_workspace_env.png" width="55%" align="center"> <br>
  *E se estudo estiver corretamente a variável **GOPATH** estará com o workspace que criamos.*
  <br>

Assim concluímos a instalação de Go no ambiente Windows! :muscle::dart:
