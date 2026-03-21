# Encontros Mensais — LABHDUFBA

[![Licença: CC BY 4.0](https://img.shields.io/badge/Licen%C3%A7a-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Repositório de organização dos **encontros mensais ampliados** do [Laboratório de Humanidades Digitais da UFBA (LABHDUFBA)](https://labhdufba.github.io).

O LABHDUFBA reúne pesquisadores interessados na confluência entre humanidades, dados e tecnologias digitais, desenvolvendo metodologias computacionais aplicadas a questões como desinformação, história digital e análise de redes sociais. Os encontros mensais ampliados nasceram da necessidade de abrir esse espaço para além do núcleo fixo do laboratório, convidando estudantes de graduação e pós-graduação, pesquisadores de outras instituições e demais interessados a participar do intercâmbio intelectual que caracteriza o LABHDUFBA. O objetivo é criar um ponto de encontro regular onde diferentes trajetórias e perspectivas se cruzem em torno das humanidades digitais, fortalecendo a comunidade de prática e ampliando o alcance das discussões produzidas no laboratório.

## Sobre os encontros

Os encontros acontecem toda **primeira sexta-feira do mês, às 14h**, alternando entre dois formatos:

- **Debate de texto** — leitura e discussão coletiva de um texto relevante para as humanidades digitais ou discussão de produções de membros do laboratório.
- **Debate de ferramenta/método** — apresentação e discussão prática de uma ferramenta ou abordagem metodológica

Cada edição conta com um(a) responsável diferente, que propõe o tema e conduz a discussão.

## Cronograma

Veja o cronograma completo em [cronograma.md](cronograma.md).

## Estrutura do repositório

```
encontros-mensais/
├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── cronograma.md
├── encontros/
│   └── YYYY-MM-DD-tipo/   ← uma pasta por encontro
│       └── README.md
└── assets/                ← imagens e arquivos de uso geral
```

Cada pasta dentro de `encontros/` segue o padrão `YYYY-MM-DD-tipo/`, onde `tipo` é `texto` ou `metodo`.

## Como contribuir

Consulte o [CONTRIBUTING.md](CONTRIBUTING.md) para o fluxo completo de contribuição (branch → Pull Request → revisão).

Em resumo: crie uma pasta em `encontros/` no padrão `YYYY-MM-DD-tipo/`, adicione o `README.md` com Tema, Responsável, Resumo, Materiais e Notas, e abra um PR marcando um revisor.

## Licença

Este repositório está licenciado sob [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).
