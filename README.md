## 🧩 **Projeto desenvolvido para estudo pessoal.**

### 🎯 Desafio

Criar uma API em Node que consome a API da openAI, a fim de utilizar a funcionalidade de 'text completion' do **ChatGPT**.

### 🛸 Tecnologias

O código da aplicação foi desenvolvido com as seguintes tecnologias:

### ⚛️

- [Node.js](https://nodejs.org/en/)
- [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

### 📚 Bibliotecas e Dependências

- [openAI](https://npmjs.com/package/openai) - Integração com o algoritmo da openAI
- [express](https://.npmjs.com/package/express) 
- [cors](https://.npmjs.com/package/cors) - Controle de acesso da api para requests/resources
- [dotenv](https://.npmjs.com/package/dotenv) 
- [nodemon](https://.npmjs.com/package/nodemon) - Servidor de monitoramento Node para desenvolvimento

## :information_source: Passo-a-passo

Para clonar e rodar a aplicação, será necessário [Git](https://git-scm.com), [Node.js v14.16](https://nodejs.org/en/) ou versão mais recente + [NPM v8](https://nodejs.org/en/) ou mais recente instalados. 
Linhas de comando:

```bash
# Clonar o repositório
$ git clone https://github.com/guitotti/node-chatgpt-api

# Navegar até o repositório
$ cd node-chatgpt-api

# Instalar dependências
$ npm install

# Rodar o projeto em ambiente de desenvolvimento
$ npm run dev
```
* Observação:
```bash
Para utilizar a biblioteca da openAI será necessário configurar uma chave secreta ('secret key') para sua conta, disponível no site da openAI.
Feito isso, antes de rodar a aplicação será necessário setar a chave da API como uma variável de ambiente no arquivo .env.
```
