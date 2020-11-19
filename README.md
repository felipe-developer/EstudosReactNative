# EstudosReactNative

  Preparando o Ambiente:
  
  Execute o comando abaixo para verificar se você possui permissões para instalar dependências com o terminal: 
    Comando: Get-ExecutionPolicy
    
  Caso o retorno desse comando seja diferente de “Restricted”, pule para o próximo passo. Porém, se o retorno for “Restricted”, execute o seguinte comando em seu          terminal:  
    Comando: Set-ExecutionPolicy AllSigned
  
  Agora, execute o seguinte comando para instalar o Chocolatey:
     Comando: Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
     
  Agora vamos instalar o Node.js, Yarn 1, Python2 e a JDK 8 (Java Development Kit 8).
      Comando: choco install -y nodejs-lts yarn python2 jdk8
  
  Instalando o Expo-Cli:
      Comando: yarn global add expo-cli
      
  Iniciando o Projeto:
    Baixe o Projeto no Git ou utilize o github desktop para clonar o projeto nesse momento voce irar abrir a pasta do projeto e irar aperta a tecla Shift+Direito do Mouse e abrir com powershell quando o powershell abrir voce irar digita o comando "code ." esse comando irar abrir o projeto no VSCODE em seguinda no proprio powershell irar usar o comando "yarn install" esse comando serve para baixar todas as dependencia do projeto sem esse comando o projeto irar da erro o proximo comando é para iniciar o builder do projeto o comando é "expo start --web" e pronto o projeto vai inicia com seu dispositivo android voce irar instalar pela play store o App Expo quando voce abrir o app pelo teu celular voce tem que estar na mesma rede que a sua maquina nisso voce irar ler pelo o App o codigo QRCODE que irar abrir no navegador e pronto voce ja pode começa a fazer seu projeto 
   
