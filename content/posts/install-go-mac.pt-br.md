+++
author = "Tom"
title = "Instalando Go no MacOS"
date = "2021-08-28"
description = "Tutorial de instalação de Go no MacOS"
images = ["gopher_home.jpg",]

tags = [
    "go",
]
+++

{{<figure src="/img/install-go/gopher_banner.jpg">}}

#### :white_check_mark: O que é Go?

Go é uma linguagem de programação de código aberto desenvolvida por uma equipe do Google. Ele fornece software fácil de construir, simples, confiável e eficiente. Esta linguagem é projetada para escrever servidores, é por isso que é amplamente usada atualmente. No momento da atualização deste tutorial, o Go 1.17 é a versão mais recente disponível. Este tutorial ajudará você a instalar o Go 1.17 em seu sistema operacional macOS.
  &nbsp;


#### :white_check_mark: Executando a instalação

  Iremos realizar todas os processos de instalação de Go em 4 passos.

#### :white_check_mark: Step 1 - Baixando Go

Para baixar a versão mais recente do Go, visite https://golang.org/dl/. Você verá o link de download do Apple macOS. A versão atual do Go 1.17 é compatível com macOS 10.10 ou versões posteriores apenas com suporte de 64 bits.


  {{<figure src="/img/install-go/windows/download-go.png" width="72%">}}
  &nbsp;

Como alternativa, você pode baixar o Go 1.17 usando a linha de comando curl.
``` bash
  $ curl -o golang.pkg https://dl.google.com/go/go1.16.4.darwin-amd64.pkg 
```

#### :white_check_mark: Step 2 - Instalar Go no MacOS

Você baixou o pacote Go em seu sistema macOS. Para instalá-lo, basta clicar duas vezes no arquivo baixado para iniciar o assistente de instalação.

Os usuários da linha de comando podem executar o comando abaixo para iniciar a instalação.

```bash
   $ sudo open golang.pkg 
```

Siga o assistente de instalação e conclua o processo de instalação.

  {{<figure src="/img/install-go/mac/install-go-on-macos.png" width="72%">}}
  &nbsp;


#### :white_check_mark: Step 3 - Configurar Workspace para Go
Edite o arquivo ~ / .bash_profile ou ~ / .profile (ou seu equivalente) para definir as variáveis de ambiente. Normalmente você precisa definir 3 variáveis de ambiente como **GOROOT**, **GOPATH** e **PATH**.

**GOROOT** is the location where Go package is installed on your system.

```bash
$ export GOROOT=/usr/local/go 
```

**GOPATH** é a localização do seu diretório de trabalho. Por exemplo, meu diretório de projeto é ~ / Projects / Proj1
```bash
$ export GOPATH=$HOME/Projects/Proj1 
```

Agora defina a variável **PATH** para acessar todo o sistema binário.

```bash
$ export PATH=$GOPATH/bin:$GOROOT/bin:$PATH 
```

#### :white_check_mark: Step 4 - Checar a versão de Go instalada :trophy:

Finalmente, você instalou e configurou com sucesso o idioma em seu sistema. Primeiro, use o seguinte comando para verificar a versão Go instalada.
    
```bash
$ go version

go version go1.17 darwin/amd64
```

#### :white_check_mark: Conclusão

Assim concluímos a instalação de Go no ambiente MacOS! :muscle: :dart:
