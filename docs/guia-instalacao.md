# Guia de instalação

## 1. Pré-requisitos

### Java
JDK 1.6.0_21
### JBoss
JBoss 4.0.2
### Maven
Maven 3.0.4

## 2. Adicionar variaveis ambientes
Para adicionar as variaveis de ambiente acesse

### Maven
Acesse a pasta onde o Maven está instalado e copie o path.
Adicione o path á variavel de ambiente `PATH`
### Java Home
Acesse a pasta onde o Java está instalado e copie o path.
Crie uma variavel de ambiente chamada `JAVA_HOME` e adicione o path copiado a ela.
### ClassPath
Crie uma variavel de ambiente chamada `CLASSPATH` e adicione `%JAVA_HOME%/lib` a ela.

## 3. Configurar Maven
### Transformar em Maven project
Clique com o botão direito no projeto e clique em converter para projeto Maven
### Modificar configurações do Maven
Entre na pasta do Maven
Entre na pasta conf
Abra o arquivo `settings.xml`
### Update Maven
Clique com o botão direito no projeto e navege até Maven -> Update Project
### Adicionar as variaveis


## 4. JBoss

### Criar server
Para adiconar um novo servidor JBoss, navegue até Window -> Show -> Views -> Server.
Na visualização inferior que surge, clicar com o botão direito e selecionar a opção `New Server`.

### Runtime Enviroment
Eclipse:
Para adicionar o Runtime Enviroment navege até Window -> Preferences -> Server -> Runtime Enviroment.
Clique em `Add` e selecione o JBoss 4.0 e a opção `create a new local server`.
Selecione o diretório onde se encontra o JBoss na sua maquina.
Modifique a versão do Runtime JRE para `Alternate JRE`.
Clique em `Installed JREs` e adicione a versão do JDK 6.
Selecione a versão do JDK 6 e confirme.

### Adicionar projeto ao servidor
Clicar com o botão direito no server, clicar em `Add and Remove` e adicionar o portalatendimento.

###
