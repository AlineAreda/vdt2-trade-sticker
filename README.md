## Trade Sticker


### Testando um sistema de troca de figurinhas da copa do mundo com outros colecionadores cadastrados na plataforma. Possui integração com a API do WhatsApp para iniciar a negociação das figurinhas.


### 🚀 Tecnologias

- [Node.js] - plataforma de desenvolvimento
- [Pynthon] - linguagem de programação
- [Robot Framework] - framework de testes automatizados



### Pré-requisitos para a execução do projeto:

    Python: https://www.python.org/downloads/
    
    Observações importantes sobre a instalação do Python: 
        Selecionar a opção para adicionar o Python ao PATH do S.O.
        Escolher a instalação customizada.
        Selecionar para instalar para todos os usuários. 
        Altere o caminho da instalação para C:\Python310

    Node.js 16: https://nodejs.org/en/

  
    
    Comandos necessários:

        pip install robotframework

        pip install -U pip

        pip install -U robotframework-browser

        rfbrowser init

### Executando o projeto:

    Abrir o Git Bash ou qualquer outro terminal integrado ao Git.

    Escolha uma pasta no seu S.O e entre nela para realizar o comando abaixo:

    git clone https://github.com/thinogueiras/VDT-Season02-RobotFramework.git    

    cd VDT-Season02-RobotFramework
    
    Rodar a suíte de testes no Firefox:

        robot -d ./logs -v BROWSER:firefox -v HEADLESS:False tests/

    Rodar a suíte de testes no Chromium:
    
        robot -d ./logs -v BROWSER:chromium -v HEADLESS:False tests/
        

Feito com 💜 &nbsp;por Aline Areda 👋 &nbsp;[Meu linkedin](https://www.linkedin.com/in/aline-areda/)
