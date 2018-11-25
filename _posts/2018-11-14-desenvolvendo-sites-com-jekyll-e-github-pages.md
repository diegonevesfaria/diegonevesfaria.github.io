---
layout: post ## Layout a ser utilizado
date: 2018-11-14 09:08:55 -0200 ## Data e Hora da Criação do Post
image: /assets/img/posts/jekyll-github-sites.jpg ## Imagem de capa
title: "Desenvolvendo Sites com Jekyll e Github Pages" ## Mínimo de 35 Caracteres e Máximo de 50.
description: "Crie sites incríveis e hospede gratuitamente no Github" ## Mínimo de 35 Caracteres e Máximo de 80.
author: Diego Neves Faria ## Autor do Post
categories: 
    - "Front-End"
    - "Back-End"
    - "Mobile"
youtube: vlDzYIIOYmM
tags: ## Tags do Post
 - Jekyll
 - HTML5
 - CSS3
 - Github
---

Olá galera neste artigo falarei sobre oque é o Jekyll e como ele pode ser muito útil para projetos rápido e como o mínimo de investimento (que no seu caso é ter apenas um computador e conexão com a internet), você pode ter um site rodando na internet.

A mais as pessoas vão dizer a por se tratar de um recurso gratuito não deve ser tão bom assim, bem vamos lá, só porque um recurso é gratuito não quer dizer que o mesmo é ruim, exemplos disso são: 

[REACT](https://reactjs.org/) - Nada mais é que um framework do Facebook que é utilizado para desenvolver aplicações Web e para dispositivos Android e IOS.

[PYTHON](https://www.python.org/) - Linguagem de programação rápida que permite integrar sistemas rápidamente.


# Vamos falar sobre o Jekyll


Por isso resolvi desenvolver um curso gratuito de Jekyll para Portais e Blogs, mas não esquenta este curso é totalmente gratuito, você não vai precisar pagar nada por ele.

A mais e as páginas ficam bonitas? Bem isso vai depender da sua experiência em HTML5, CSS3 e Javascript, oque é normal já que você estará fazendo um site. Porém neste curso também estarei ensinando o básico de HTML5 e Bootstrap 4 com isso você irá conseguir desenvolver seu site bem dinâmico e bonito. Abaixo achei alguns exemplos de site feito com o Jekyll:

[AWS Amplify](https://aws-amplify.github.io/) - Não deve ser desconhecido pela comunidade um gigante da indústria AWS.

[Markdown Guide](https://www.markdownguide.org/) - Um ótimo site para aprende sobre Markdown, ainda mais que você terá que aprender para criar artigos para seu blog.

[Netflix OSS](https://netflix.github.io/) - E para você que gosta de séries como eu, um site falando sobre as tecnologia da Netflix.

Bem agora vamos a parte prática vou ensinar vocês a deixar seu ambiente pronto para desenvolver com o Jekyll

Primeiramente instale o Ruby para utilizar o Jekyll:
```sh
$ sudo apt-get install ruby ruby-dev build-essential
```
Agora temos que configurar a váriavel de ambiente para que conseguirmos utilizar o Ruby de qualquer parte de nossa conta:
```sh
$ echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
$ echo 'export GEM_HOME=$HOME/gems' >> ~/.bashrc
$ echo 'export PATH=$HOME/gems/bin:$PATH' >> ~/.bashrc
$ source ~/.bashrc
```

Pronto nosso ambiente Ruby está pronto agora vamos instalar o Jeyll e começar a utilizar o mesmo.

```sh
$ gem install jekyll bundler
```


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].



[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
