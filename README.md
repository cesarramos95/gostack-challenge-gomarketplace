# Challenge 08 GoStack - GoMarketPlace

An app made with React Native and Typescript using routes, Async Storage and context API concepts.

![GitHub top language](https://img.shields.io/github/languages/top/cesarramos95/gostack-challenge-gomarketplace)
![GitHub language count](https://img.shields.io/github/languages/count/cesarramos95/gostack-challenge-gomarketplace)
![GitHub repo size](https://img.shields.io/github/repo-size/cesarramos95/gostack-challenge-gomarketplace)
[![GitHub license](https://img.shields.io/github/license/cesarramos95/gostack-challenge-gomarketplace?label=license)](https://github.com/cesarramos95/gostack-challenge-gomarketplace/blob/master/LICENSE)
<img src="https://img.shields.io/static/v1?label=made by&message=César&color=blueviolet&style=<STYLE>&logo=<LOGO>">


## 💻 Preview

<br>
<div align="center">
  <img src="./screenshot/Dashboard.jpg" alt="Dashboard" width="200px;">
  <img src="./screenshot/CartScreen.jpg" alt="Cart" width="200px;">
</div>

<div id="technologies">

<p align="center">
 <a href="#technologies">Technologies</a> •
 <a href="#run">How to run</a> •
 <a href="#license">License</a> •
 <a href="#autor">Autor</a>
</p>

---

## 🛠 Technologies
The following tools were used to solve this challenge:
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

</div>

<div id="install">

---

## ℹ How to run

### Requirements

- [React Native](https://reactnative.dev/)
- [Yarn](https://yarnpkg.com)
- [Git](https://git-scm.com)

Clone the repository and install the dependencies:

```bash
# To clone the repository
$ git clone https://github.com/cesarramos95/gostack-challenge-gomarketplace

# To acess the folder
$ cd gostack-challenge-gomarketplace

# Install dependencies
$ yarn

# To run fake API
$ yarn json-server server.json -p 3333
```

To run the application on your device you need to configure your IP on [api.ts](./src/services/api.ts) file:

```shell
baseURl: 'http://<your machine's ip>:3333'
```

You can use baseURL:'http://localhost:3333'. To this, run the command below:

```shell
adb reverse tcp:3333 tcp:3333
```
</div>

<div id="license">

---

## 📝 License
This repository is under [MIT](./license) license.
</div>

<div id="autor">

## Autor

<img src="https://avatars0.githubusercontent.com/u/41995703?s=460&u=e79d6900cae07be99d738d5388709b275f752356&v=4" width="100px" >
<br>
<a href="t.me/cesarramos95">César</a>

[![Linkedin Badge](https://img.shields.io/badge/-César-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/cesararamos/)](https://www.linkedin.com/in/cesararamos/)
[![Gmail Badge](https://img.shields.io/badge/-cesarramos.aug@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:cesarramos.aug@gmail.com)](mailto:cesarramos.aug@gmail.com)

</div>

---

Made with ❤ by César 👋 [Get in touch!](https://linkedin.com/in/cesararamos)

