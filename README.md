# Projeto: Hora do Dia

Este projeto é uma aplicação simples que exibe a hora atual e altera a imagem e mensagem exibidas com base no período do dia (manhã, tarde ou noite).

## Estrutura do Projeto

O projeto está localizado na pasta `EXERCÍCIOS.html/exercício 01` e contém os seguintes arquivos:

- `ex01.html`: Arquivo principal da aplicação.
- `estilo.css`: Arquivo de estilos para a página.
- `script.js`: Arquivo JavaScript que contém a lógica para determinar o período do dia e atualizar a interface.
- `manha.png`: Imagem exibida durante a manhã.
- `tarde.png`: Imagem exibida durante a tarde.
- `noite.png`: Imagem exibida durante a noite.

## Funcionalidades

- Exibe a hora atual do sistema.
- Altera a mensagem e a imagem com base no horário:
  - **Manhã**: Entre 0h e 12h.
  - **Tarde**: Entre 12h e 18h.
  - **Noite**: Após 18h.

## Como Executar

1. Certifique-se de que todos os arquivos necessários estão na pasta `exercício 01`:

   - `ex01.html`
   - `estilo.css`
   - `script.js`
   - Imagens: `manha.png`, `tarde.png`, `noite.png`

2. Abra o arquivo `ex01.html` em um navegador da web.

3. A aplicação exibirá a hora atual e a imagem correspondente ao período do dia.

## Tecnologias Utilizadas

- **HTML**: Para a estrutura da página.
- **CSS**: Para estilização da interface.
- **JavaScript**: Para a lógica de exibição dinâmica.

## Personalização

Você pode personalizar o projeto alterando:

- As imagens (`manha.png`, `tarde.png`, `noite.png`) para outras de sua preferência.
- O estilo no arquivo `estilo.css`.

## Problemas Conhecidos

- O arquivo `script.js` contém um erro de digitação na linha onde a data é instanciada: `new.Date()` deve ser corrigido para `new Date()`.

## Autor

Este projeto foi desenvolvido como parte do curso de JavaScript.

---

**Nota**: Certifique-se de que as imagens estão no mesmo diretório que o arquivo `script.js` para que sejam carregadas corretamente.
