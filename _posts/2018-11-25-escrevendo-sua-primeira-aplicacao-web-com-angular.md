---
layout: post
date: 2018-11-25 09:00:00 -0200
image: /assets/img/posts/angular.png
title: "Escrevendo sua Primeira Aplicação Web com Angular"
description: "Neste artigo, vou ensinar vocês a criarem um aplicativo que permita ao usuário postar um artigo (com um título e o URL) e depois poder votar qual artigo mais popular."
author: Diego Neves Faria
categories: 
    - "Front-End"
youtube:
---

Olá pessoal vamos criar um aplicativo simples, porem vamos abordar a maioria dos aspectos essenciais do Angular, incluindo:
            
 * Construir Componentes Personalizados;
 * Validar Input's do usuário nos formulários;
 * Renderizar listas de objetos nas Views;
 * Interceptar cliques do usuário e colocar ação neles;
 * Por fim implantar nosso app num servidor.
 
Neste MVP vamos utilizar TypeScript, caso precise consultar a documentação segue o link <a href="https://www.typescriptlang.org/" target="_blank">aqui</a>.
 
<h3><b>Configurando Ambiente de Desenvolvimento com Angular</b></h3>
 
Primeiro você precisa ter os seguintes softwares instalados em sua máquina:
 
Vamos instalar primeiramente o Node.js, como utilizo o Linux Mint irei mostrar como instalar nele via terminal:
<pre><code class="sh">
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash - ## Adicionando Repositório a lista de instalações do Linux
$ sudo apt-get install -y nodejs ## Instalando o nodejs
</code></pre>
 
Agora vocês devem verificar as versões instaladas com os comandos: 
<pre><code class="sh">
$ node -v
$ v10.13.0 ## Versão do Node.js deve ser esta ou superior
</code></pre>  
<pre><code class="sh">
$ npm -v
$ 6.4.1 ## Versão do NPM deve ser esta ou superior
</code></pre>

Se você utiliza Linux pode ser que tenha problemas ao executar as instalações via npm então já vou passar como você vai resolver isso rapidamente e ficar sem dor de cabeça.
<pre><code class="sh">
$ mkdir ~/.npm-global ## Você irá criar o diretório
$ npm config set prefix '~/.npm-global' ## Configurando o NPM para usar o novo diretório
</code></pre>

Agora você terá de abrir o <b>~/.profile</b> com seu editor preferido e colocar a linha abaixo dentro do final do arquivo ai somente salvar e fechar.
<pre><code class="sh">
export PATH=~/.npm-global/bin:$PATH
</code></pre>

Por fim atualize suas variáveis de sistema:
<pre><code class="sh">
$ source ~/.profile
</code></pre>
 
Pronto agora vamos instalar o Typescript e o Angular para utilizar. Digite os seguintes comandos no terminal:
<pre><code>
$ npm install -g typescript
$ npm install -g @angular/cli
</code></pre>
<b>Obs:</b> Instalamos os módulos acima comoo uma instância global para ser utilizado em outros projetos dentro da sua máquina.
 
  
  <pre><code>
  $ npm -v
  </code></pre>