---
title: "PostgREST, Sites Figma e LangGraph.js - 17 de Maio de 2025"
date: "2025-05-17"
author: "Ramos de Souza Janones"
categories: [Full Stack, Frontend, AI]
tags: [postgrest, figma, javascript, development, ai]
excerpt: "Explorando o PostgREST 13, polêmica do Figma Sites, e recursos do LangGraph.js"
cover_image: "/assets/images/full-stack/may-17-2025.jpg"
featured: false
rating: 5
seo_description: "Deep dive no PostgREST 13, polêmica do Figma Sites, e primeiros passos com LangGraph.js"
canonical_url: "https://ramosdainformatica.com.br/newsletter/2025/full-stack/may-17-2025"
translationUrl: "/newsletter/i18n/en-US/2025/full-stack/newsletter-linkedin-17-05-2025.md"
languageVersion: "pt-BR"
---

[🇧🇷 Português](#) | [🇺🇸 English](/newsletter/i18n/en-US/2025/full-stack/newsletter-linkedin-17-05-2025.md)

***"A sobrevivência é a melhor medida de desempenho."*** –Vicki TenHaken

**Nesta edição:** PostgREST, Figma Sites (polêmica!) e LangGraph.js. + Piadas de programação!

## **Editorial(??)**

Por que essa edição tá supercurta? Porque estou mergulhado de cabeça no meu projeto "Open to Work" ([https://www.linkedin.com/feed/update/urn:li:activity:7328169928056815616/](https://www.linkedin.com/feed/update/urn:li:activity:7328169928056815616/)) — e descobri uma coisa importante:

💡 *"Trabalhar só em projetos de terceiros é ótimo... até você perceber que não tem um portfólio próprio para mostrar suas habilidades!"*

Então, bora corrigir isso! Estou construindo um sistema em Node.js + React do zero, com:

✔️ Melhores práticas (testes, clean code, documentação)
✔️ Tudo open-source (pra você espiar o código e dar feedback!)
✔️ Case real (nada de "TODO app" genérico)

Semana que vem tem atualização quentinha! 🍿 Mas por hoje, curta essa edição *light* — e se prepare para a próxima, que vem com *código, screenshots e talvez até um deploy público!*

Boa leitura! (E me conta: você também já passou por isso? Quem sabe não rola uma troca de ideias!)

## **Banco de dados**

PostgREST 13: API RESTful para Bancos Postgres Um servidor web autônomo que transforma seu banco Postgres diretamente em uma API HTTP RESTful. A versão 13.0 traz:

* Relações *spread* to-many ([docs](https://docs.postgrest.org/en/v13/references/api/resource_embedding.html#spread-to-many-relationships)): simplifica consultas complexas com joins aninhados.
* Conversão automática de tsvector ([docs](https://docs.postgrest.org/en/v13/references/api/tables_views.html#automatic-tsvector-conversion)): busca full-text em campos de texto e JSON *pronta para uso*.

Cenários Reais para Devs:

1. MVP Rápido Crie uma API REST para seu frontend (React/Vue) em minutos, sem escrever código backend.
2. Busca Avançada Implemente filtros complexos e full-text search (ex.: e-commerce) diretamente via URL.
3. Microserviços Leves Exponha partes específicas do banco como endpoints autônomos (ex.: relatórios).
4. Integração com Ferramentas Low-Code Conecte Power BI, Airtable ou Zapier ao Postgres sem desenvolver APIs intermediárias.

Dica: Ideal para prototipagem ou sistemas com regras de negócio centralizadas no banco. 🚀 LINK: [https://docs.postgrest.org/en/v13/](https://docs.postgrest.org/en/v13/)

## **Ferramenta de criação de sites com tecnologia de IA da Figma**

O Figma [anunciou recentemente *os 'Figma Sites'*](https://frontendfoc.us/link/169291/62e4c7e6b7), uma maneira de permitir que você publique rapidamente seus designs Figma diretamente na web — mas a resposta dos desenvolvedores front-end tem sido *bastante mista*, com muitas comparações com os resultados inchados de plataformas como Dreamweaver e Microsoft Frontpage.

Embora ainda esteja em fase beta, houve algumas críticas ao [código pesado em div](https://frontendfoc.us/link/169292/62e4c7e6b7) que ele está produzindo.

* [Figma lança novas ferramentas com tecnologia de IA para criação de sites](https://frontendfoc.us/link/169293/62e4c7e6b7) — Ivan Mehta
* [O verdadeiro caminho para o código lixo: sites Figma](https://frontendfoc.us/link/169294/62e4c7e6b7) — Joe Dolson
* [Não publique seus designs na Web com sites Figma…](https://frontendfoc.us/link/169295/62e4c7e6b7) — Adrian Roselli
* [O Figma Sites é pior do que você imagina](https://frontendfoc.us/link/169296/62e4c7e6b7) — Kevin Powell

---

Qual a diferença entre um commit e um relacionamento? *O commit pelo menos tem uma mensagem clara.*

## **IA com Node, React, etc... ou projetos Javascript**

Começando com LangGraph.js? Explore o "awesome-langgraphjs"!

Está querendo usar LangGraph.js, mas não sabe por onde começar? O repositório "awesome-langgraphjs" reúne uma lista incrível de projetos open source e vídeos no YouTube feitos com ou para LangGraph.js!

Encontre desde sistemas multiagentes prontos para produção até aplicativos de chat full-stack: 👉 [https://github.com/bracesproul/awesome-langgraphjs](https://github.com/bracesproul/awesome-langgraphjs)

Se você conhece ou tem um projeto open source usando LangGraph.js, contribua com um PR para adicionar o link!

## **E PRA TERMINAR... (É FINAL DE SEMANA!)**

Qual é o framework favorito do dev preguiçoso? *O "Sofa.js" — porque ele só quer ficar deitado.*

*Excelente final de semana!*
