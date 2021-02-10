# TADS

Para instalar as ferramentas necessárias para a nossa disciplina siga as instruções dos links a seguir:

## Git

[https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Docker

[https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)

## Hosts

Após a instalação abra o PowerShell (ou outro terminal) como administrador e execute o comando a seguir:

     notepad.exe C:\Windows\System32\Drivers\etc\hosts

No arquivo de hosts descomente a linha

    #	127.0.0.1       localhost

e acrescente

    	127.0.0.1	tads.local
o arquivo final deve ficar similar a:

    # localhost name resolution is handled within DNS itself.
	127.0.0.1   localhost
	127.0.0.1	tads.local

após a edição salve e feche o arquivo.

## Clonando o repositório 

Agora, ainda no terminal, vá até uma pasta onde você irá armazenar seu projeto, por exemplo:`D:`
e clone o repositório

    git clone https://github.com/gleonel/docker-2021-1.git

## Iniciando o Docker

Depois de clonar entre na pasta docker-2021-1
 

    cd docker-2021-1\

e inicie os containers

    docker-compose up -d
    
## Testando
Para verificar acesse o endereço a seguir no navegador: [http://localhost/](http://localhost/)
