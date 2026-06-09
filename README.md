# Bíblia CEP

Aplicação Web Progressiva (PWA) para leitura da Bíblia Católica em português, utilizando a tradução da Conferência Episcopal Portuguesa (CEP).

Disponível em:

https://hvarios.github.io/biblia-cep/

## Funcionalidades

- Leitura da Bíblia Católica em português
- Navegação por livros e capítulos
- Organização por secções canónicas:
  - Pentateuco
  - Históricos
  - Sapienciais
  - Proféticos
  - Evangelhos
  - Atos dos Apóstolos
  - Cartas Paulinas
  - Cartas Católicas
  - Apocalipse
- Pesquisa de palavras e expressões
- Notas de tradução da CEP
- Modo claro e escuro
- Ajuste do tamanho do texto
- Cópia rápida de versículos
- Partilha de versículos
- Seleção múltipla de versículos para cópia ou partilha
- Instalação como aplicação móvel (PWA)
- Funcionamento offline através de Service Worker

## Estado do Projeto

O projeto encontra-se em desenvolvimento contínuo.

Nem todos os livros da Bíblia estão ainda disponíveis. Os livros em falta são apresentados no menu com a indicação:

> em tradução

A estrutura foi preparada para permitir adicionar novos livros sem alterar a aplicação.

## Estrutura do Projeto

```text
/
├── index.html
├── manifest.json
├── sw.js
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── data/
    ├── books-index.json
    └── books/
        ├── abd.json
        ├── co.json
        ├── mc.json
        └── ...

URL público: https://hvarios.github.io/biblia-cep/

Tecnologias Utilizadas
  HTML5
  CSS3
  JavaScript Vanilla
  Progressive Web App (PWA)
  GitHub Pages

Licença

Este projeto encontra-se em desenvolvimento pessoal e educativo.

O código-fonte está disponível neste repositório.

Os textos bíblicos utilizados pertencem à tradução da Conferência Episcopal Portuguesa (CEP).
