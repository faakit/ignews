<h1 align="center">Ig.News</h1>
<h3 align="center">Por André Altoé</h3>

<p align="center">
  <img src="public/images/screenshot.png" alt="Ignews Preview" width="100%">
</p>

<!-- TABLE OF CONTENTS -->
<h2 id="summary"> :book: Sumário</h2>

<details open="open">
  <summary>Sumário</summary>
  <ol>
    <li><a href="#sobre"> ➤ Sobre</a></li>
    <li><a href="#tecnologias"> ➤ Tecnologias</a></li>
     <li><a href="#como-rodar"> ➤ Como Rodar</a></li>
    <li><a href="#creditos"> ➤ Creditos</a></li>
  </ol>
</details>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ABOUT THE PROJECT -->
<h2 id="sobre"> :pencil: Sobre</h2>

<p align="justify">
Desafio referente ao terceiro módulo do curso Ignite na Rocketseat, onde nos foi dado o objetivo de criar um blog com next.js consumindo os dados de um backend remoto com um headless CMS chamado Prismic, além disso, as postagens são mostradas apenas para membros inscritos, para o pagamento foi utilizado o Stripe e para guardar os usuários no banco de dados foi utilizado o FaunaDB, além da autenticação social com o Github.
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ABOUT THE PROJECT -->
<h2 id="tecnologias"> :hammer: Tecnologias</h2>

<ul>
    <li><a href="https://www.github.com/" title="Github"><img src="https://github.com/get-icon/geticon/raw/master/icons/github-icon.svg" alt="Github" width="21px" />
    <li><a href="https://stripe.com/br" title="Stripe"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/ba/Stripe_Logo%2C_revised_2016.svg/2560px-Stripe_Logo%2C_revised_2016.svg.png" alt="Stripe" height="22px"></a></li>
    <li><a href="https://fauna.com/" title="Fauna"><img src="https://images.ctfassets.net/po4qc9xpmpuh/7itYmeRxmVGIXwwGWHrQU3/e4ea73c2bebc64bd65d84964576515b9/fauna-logo-new-v2.svg" alt="FaunaDB" height="21px"></a></li>
    <li><a href="https://prismic.io/" title="Prismic"><img src="https://prismic.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-dark.731ed924.svg&w=128&q=75" alt="Prismic" height="21px"></a></li>
    <li><a href="https://nextjs.org/" title="Next.js"><img src="https://github.com/get-icon/geticon/raw/master/icons/nextjs-icon.svg" alt="Next.js" width="21px" height="21px"> Next Js</a></li>
    <li><a href="https://www.typescriptlang.org/" title="Typescript"><img src="https://github.com/get-icon/geticon/raw/master/icons/typescript-icon.svg" alt="Typescript" width="21px" height="21px"> Typescript</a></li>
    <li><a href="https://reactjs.org/" title="React"><img src="https://github.com/get-icon/geticon/raw/master/icons/react.svg" alt="React" width="21px" height="21px"> React Js</a></li>
    <li><a href="https://yarnpkg.com/" title="Yarn"><img src="https://github.com/get-icon/geticon/raw/master/icons/yarn.svg" alt="Yarn" width="21px" height="21px"> Yarn</a></li>
    <li><a href="https://code.visualstudio.com/" title="Visual Studio Code"><img src="https://github.com/get-icon/geticon/raw/master/icons/visual-studio-code.svg" alt="Visual Studio Code" width="21px" height="21px"> Visual Studio Code</a></li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ABOUT THE PROJECT -->
<h2 id="como-rodar"> :nut_and_bolt: Como Rodar</h2>

<p>Para rodar essa aplicação localmente é necessário que você primeiro crie sua conta nos seguintes serviços: Prismic, Stripe, Github e Fauna. Após isso, configurar suas variáveis de ambiente com as seguintes chaves:</p>

<pre><code># Stripe

STRIPE_API_KEY
NEXT_PUBLIC_STRIPE_PUBLIC_KEY
STRIPE_WEBHOOK_SECRET
STRIPE_SUCCESS_URL
STRIPE_CANCEL_URL

# Github

GITHUB_ID
GITHUB_SECRET

# FaunaDB

FAUNADB_KEY

# Prismic CMS

PRISMIC_ENDPOINT
PRISMIC_ACCESS_TOKEN</code></pre>

<p>
    Você pode rodar o projeto em ambiente de desenvolvimento simplesmente digitando os seguintes comandos em seu terminal:
</p>
<pre><code>$ yarn
$ yarn dev</code></pre>

<p>
    Caso esteja a utilizar o Node na versão 17 será necessário acrescentar uma opção na inicialização, podendo ser rodado com:
</p>

<pre><code>$ yarn dev17</code></pre>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ABOUT THE PROJECT -->
<h2 id="creditos"> :eyeglasses: Creditos</h2>

> Feito com 💙 Por André Altoé :wave:

<a href="https://www.linkedin.com/in/andre-altoe/" title="LinkedIn"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>

Durante o curso Ignite da Rocketseat
