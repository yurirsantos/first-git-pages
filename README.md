# Git Pages com React

Neste repositório você vai aprender passo-a-passo de como enviar seu projeto criado com React, no git pages e ter uma página web acessível para outras pessoas!

## passo-a-passo

## 1 Primeiramente verificamos se está instalado

Em seu terminal verifique as versões dos seguintes requisitos:

<ul> 
  <li> <code> npm -v </code> </li>
  <li> <code> yarn -v </code> </li>
  <li> <code> node -v </code> </li>
</ul>

Se caso não tenha instalado em seu computador, segue link abaixo:

<ul> 
  <li> <a href="https://nodejs.org/en/download/"> Node </a> </li>
  <li> <a href="https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable"> Yarn </a> </li>
</ul>

## 2 Criando seu app react

Em seu terminal rode o seguinte comando:

<code> npx create-react-app NOME-DO-SEU-PROJETO </code>

## 3 Teste seu projeto

Em seu terminal rode o seguinte comando:

<code> yarn start </code>

Você será redirecionado para o seguinte local 

<link> http://localhost:3000 </link>

![image](https://user-images.githubusercontent.com/91801482/179429612-524697c5-0fdd-4db4-bac3-fe30c041f9bd.png)

## 4 Criando repositório do GitHub

Em seu GitHub crie seu repositório, após isso clone sem sua máquina com o seguinte comando pelo terminal:

## 1 Primeiro comando
<code> git remote add main https://github.com/SEU-NOME-NO-GITHUB/NOME-DO-SEU-REPOSITORIO </code>
## 2 Segundo comando
<code>  git push --set-upstream main </code>

## 5 Instalação do gh-pages

Em seu terminal rode o seguinte comando:

<code> yarn add gh-pages </code>

## 6 Package.json

No arquivo <strong> package.json </strong> em seu projeto insira os seguinte comandos:

<li> <code> "predeploy": "npm run build", </code> </li>
<li> <code> "deploy": "gh-pages -d build", </code> </li>

Desta forma:
![image](https://user-images.githubusercontent.com/91801482/179429867-e5e7a019-2f7b-4e8c-8893-da724a03b917.png)

Após isso, precisamos indicar para nosso projeto, qual caminho deve ser seguindo para a página principal, para isso utilizando o seguinte comando:

<code> "homepage": "https://SEU-NOME-NO-GITHUB.github.io/NOME-DO-SEU-REPOSITORIO/", </code>

Desta forma:
![image](https://user-images.githubusercontent.com/91801482/179430024-a6b02bd3-9d72-495d-a870-e97bfd1b31fe.png)

## 7 Deploy

Em seu terminal rode o seguinte comando:

<code> npm run deploy </code>

## 8 Git pages

Em seu github, vá até seu repositório, configurações e pages:

![image](https://user-images.githubusercontent.com/91801482/179430162-98889bed-2c49-4171-a03f-37bbbef56e75.png)

Em branch selecionea opção <strong> gh-pages </strong> conforme abaixo:

![image](https://user-images.githubusercontent.com/91801482/179430221-5df7b86f-b1a7-4aae-bdee-06c44ed2fbf6.png)

# <strong> PRONTO!! </strong> seu repositório agora tem uma página na web criada com React!
