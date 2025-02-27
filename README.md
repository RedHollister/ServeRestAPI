# Bootcamp 01 Qualiters Club
Testes de API Rest do Manual a CI/CD

## O que é
Este repositório foi criado para o Bootcamp de testes de API REST

## Tecnologias Utilizadas
- Postman versão Web
- node version v22.13.1.
- newman v6.2.1
- newman-reporter-html

## Documentações
Doc da API: [Consulte Swagger](https://serverest.dev/)

## Como instalar o ambiente
- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
- Segundo: realize a instalação do newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: realize a instalação da dependência dos relatórios (opcional)[newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
```
npm install -g newman-reporter-html
```


## Como rodar os testes

### Pelo Postman Web/Desktop
- Import a collection e o environment
- Execute os testes de forma manual ou automatizada

### Pelo newman

- Abra o seu console de preferência
- Execute a seguinte linha de comando para rodar os testes
  ```
  newman run ServeRest.postman_collection.json -e ServeRest_env.postman_environment.json -r cli
  ```
- Execute os testes com relatório
  ```
  newman run ServeRest.postman_collection.json -e ServeRest_env.postman_environment.json -r cli,htmlextra
  ```

### Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.

## Entre em contato
email: elton.guilherme@hotmail.com

Redes sociais: https://www.linkedin.com/in/elton-guilherme-ferreira-619b6a1a4/

