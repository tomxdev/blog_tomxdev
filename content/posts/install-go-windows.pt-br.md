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

<!-- ![gopher](/img/gopher_home.jpg) -->
{{<figure src="/img/install-go/gopher_banner.jpg">}}

#### :white_check_mark: Download do arquivo de instalação

  Acesse o [Link](https://golang.org/dl/) do site oficial para realiazar o download do arquivo de instalação para GoLang.

<!-- ![gopher](/img/install-go/windows/download-go.png) -->
  {{<figure src="/img/install-go/windows/download-go.png" width="72%">}}
  &nbsp;


#### :white_check_mark: Executando a instalação

  Após o download estar finalizado, clique duas vezes para executar o arquivo e seguir as etapas de instalação.


  {{<figure src="/img/install-go/windows/install_next.png" width="62%">}}
  :information_source: *Tela de início para a instalação.* \
  &nbsp;
  &nbsp; 
  {{<figure src="/img/install-go/windows/install_accept.png" width="62%">}}
  :information_source: *Clique em aceitar o contrato de licença, e em seguida next.* \
  &nbsp;
  &nbsp;
  {{<figure src="/img/install-go/windows/install_path.png" width="62%">}}
  :information_source: *Selecione a pasta de instalação, e em seguida next.* \
  &nbsp;
  &nbsp;
  {{<figure src="/img/install-go/windows/install_installer.png" width="62%">}} <br>
  :information_source: *Clique em install para inicializar a instalação, e em seguida next.* \
  &nbsp;
  &nbsp;
  {{<figure src="/img/install-go/windows/instal_running.png" width="62%">}} <br>
  :information_source: *Processo de instalação em execução.*\
  &nbsp;
  &nbsp;
  {{<figure src="/img/install-go/windows/install_finish.png" width="62%">}} <br>
  :information_source: *Instalação realizada com sucesso, clique em finish para encerrar.* \
  &nbsp;
  &nbsp;

#### Checar a versão de Go instalada :trophy:

  Acesse o Executar do Windows com as teclas de atalhos ***Win + R***, e digite ***cmd*** para abrir a linha de comando. <br>
  &nbsp;
  {{<figure src="/img/install-go/windows/win_R.png" width="52%">}}   
  &nbsp;

  
    
*Na linha de comando digite **go version** para visualizar a versão de Go instalada.*
  ```bash
    $ go version
  ```

  {{<figure src="/img/install-go/windows/version.png">}}
  *Visualização da versão instalada através da linha de comando.* \
  &nbsp;



#### :white_check_mark: Configurar variável de ambiente 

Configure a variável de ambiente para GoLang

* ##### Pasta de workspace :heavy_check_mark:

  Crie uma pasta de workspace para os projetos Go.

  {{<figure src="/img/install-go/windows/create_folder_go_workspace.png">}} <br>

* ##### Gerenciador de variável de ambiente :heavy_check_mark:

  *Abra o gerenciador de variáveis de ambiente, e clique em **variáveis de ambiente**.* <br>

  {{<figure src="/img/install-go/windows/set_environment.png" width="62%">}} <br>


* ##### Configure o workspace :heavy_check_mark:

  Em ***GOPATH*** altere para a pasta workspace que foi criada. :file_folder:

  {{<figure src="/img/install-go/windows/go_workspace_path.png" width="72%">}} <br>  

  
* ##### Listar ENV de Go :heavy_check_mark:

  Acesse o Executar do Windows com as teclas de atalhos Win + R, e digite cmd para abrir a linha de comando.
  Na linha de comando digite ***go env*** para listar as variáveis de Go.  
  {{<figure src="/img/install-go/windows/go_workspace_env.png">}} <br>
  *E se estudo estiver corretamente configurado a variável **GOPATH** estará setado para o workspace.* \
  <br>

Assim concluímos a instalação de Go no ambiente Windows! :muscle::dart:
