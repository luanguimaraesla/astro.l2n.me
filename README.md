# Astronomia e Astrofísica

Este projeto é uma ação pessoal para divulgação ciêntifica na área da Astronomia e Astrofísica para o público brasileiro, uma forma de retribuir aos pesquisadores e professores que nos apresentaram ferramentas extraodinárias, que nos ajudam a compreender uma pequena fração do universo que nos cerca.

Este repositório contém, livros, artigos, mídas e documentos didáticos, como a transcrição e formatação do conteúdo do site http://astro.if.ufrgs.br/, mantido pelos professores [Kepler de Souza Oliveira Filho](http://astro.if.ufrgs.br/kp.html) e [Maria de Fátima Oliveira Saraiva](http://www.if.ufrgs.br/~fatima/hpfatima.html) da Universidade Federal do Rio Grande do Sul.

A ideia principal é possibilitar a agregação de informações úteis para o estudo da Astronomia e Astrofísica, tanto para leigos e entusiastas, como eu, quanto para o público universitário que busca um material introdutório em português.

## Site

Para acessar o site oficial clique aqui: http://astro.luanguimaraes.me

## Como executar esse projeto

Primeiramente é necessário instalar a ferramenta para construção de sites estáticos [Hugo](https://gohugo.io/getting-started/installing/).

Após a instalação, basta clonar esse repositório e executar o Hugo dentro da pasta do projeto.

```bash
hugo server -D
```

## Como contribuir

Eu utilizei o tema [Paperesque](https://themes.gohugo.io/paperesque/), sendo assim, para adicionar um novo conteúdo, basta adicionar um novo arquivo em alguma das categorias dentro da pasta `content`.

O formato basico de uma nova publicação está logo abaixo e deve seguir as boas práticas da linguagem [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

```markdown
---
date: 2020-01-03
title: "Título da publicação"
---

Seu texto aqui
```

Após fazer as alterações que deseja, abra um Pull Request neste repositório com uma breve descrição da razão de sua alteração. Eu irei revisar e aceitar se estiver tudo de acordo.
