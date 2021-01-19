<p align="center">
  <a href="https://dsdelivery-biel.netlify.app/">
    <img src=".github/logo.svg" height="150" width="175" alt="Logo da DS Delivery" />
  </a>
</p>

<h1 align="center">DS Delivery</h1>
<p align="center">Projeto realizado durante a Semana DevSuperior 2.0</p>

<p align="center">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/gabrielvieira1/dsdeliver-sds2">

  <a href="https://github.com/gabrielvieira1/dsdeliver-sds2/blob/master/LICENSE" target="_blank">
    <img alt="GitHub license" src="https://img.shields.io/github/license/gabrielvieira1/dsdeliver-sds2?color=blue">
  </a>
   
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/gabrielvieira1/dsdeliver-sds2">
  
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/gabrielvieira1/dsdeliver-sds2">
  
  <a href="https://www.linkedin.com/in/bielvieira/">
        <img 
            alt="Gabriel Vieira" 
            src="https://img.shields.io/badge/-Gabriel%20Vieira-%230077b5?style=flat-square&logo=linkedin">
    </a>
    <a href="mailto:gabrielvieira4102@gmail.com">
        <img 
            alt="gmail Gabriel Vieia" 
            src="https://img.shields.io/badge/Gmail-%23c14438?style=flat-square&logo=gmail&logoColor=white">
    </a>
    <a href="https://twitter.com/bielvieir4">
        <img 
            alt="Twitter Gabriel Vieira" 
            src="https://img.shields.io/twitter/follow/bielvieir4?label=Seguir&style=social">
    </a>
</p>

<p align="center">
  <a href="#-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-install">How to install</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

# 📖 About the project
<p>O DS Delivery tem por objetivo criar um sistema capaz de realizar pedidos em uma pizzaria fictícia. Durante o desenvolvimento foi criada uma 
API com quatros métodos:</p>

- GET /orders: retorna todos os pedidos do sistema de banco de dados que ainda estão pendentes;
- GET /products: retorna todos os produtos disponíveis para a compra;
- POST /orders: envia todas as informações do pedido que o cliente fez para o banco de dados;
- PUT /orders/{id}/delivered: atualiza o status do pedido para entregue.

<p>A landing page é composta por uma frase de efeito, uma imagem e um botão que levará o usuário à tela responsável pelo pedido do cliente, que, por sua vez, é uma
página que possui as orientações para o cliente, a lista de produtos, um mapa para obter a localização do usuário e o botão para confirmar o pedido.</p>

# 🔖 Layout

<h1 align="center">
    <img alt="DsDelivery" title="#dsdelivery" src=".github/dsdeliverypc.gif" />
</h1>

<h1 align="center">
    <img alt="DsDelivery" title="#dsdelivery" src=".github/dsdeliverymobile.gif" />
</h1>

# 🛠 Technologies

This project was developed with the following technologies:

<h4>Front-end e mobile:</h4>

- [HTML](https://www.w3schools.com/html/)
- [CSS](https://www.w3schools.com/css/)
- [JavaScript](https://www.javascript.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [ReactJS](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)

<h4>Back-end:</h4>

- [Java](https://www.java.com/pt-BR/)
- [Springboot](https://spring.io/projects/spring-boot)
- [PostgreeSQL](https://www.postgresql.org/)


# 👨‍💻 How to install

```bash
# Clone this repository
$ git clone https://github.com/gabrielvieira1/dsdeliver-sds2.git

# Go into the repository folder and install dependencies
$ cd dsdeliver

# Run
$ npm install

$ npm start
```

## 🤔 How to contribute

- Make a fork;
- Create a branck with your feature: `git checkout -b my-feature`;
- Commit changes: `git commit -m 'feat: My new feature'`;
- Make a push to your branch: `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## :memo: License

This project is under the MIT license. See the [LICENSE](LICENSE) for details.

Made with ♥ by Gabriel Vieira :wave: [Get in touch!](https://www.linkedin.com/in/bielvieira/)
