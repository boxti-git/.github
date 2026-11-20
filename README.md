# Expansão do Dicionário de Libras — Documentação

Repositório de documentação do trabalho final da disciplina **AMS0002 – Análise e Modelagem de Sistemas**
(Prof.ª Carla Diacui Medeiros Berkenbrock).

O sistema expande o [Dicionário de Libras do INES](https://www.ines.gov.br/dicionario-de-libras/) para permitir
criar, alterar e excluir todos os campos de um verbete, registrar variações regionais de um mesmo sinal
(ex.: "Pai" no padrão nacional, no RJ e no RS) e enviar o vídeo do sinal. Toda contribuição passa por um
curador antes de ser publicada.

## Sumário

1. [Enunciado do trabalho](docs/01-enunciado.md)
2. [Engenharia de Requisitos](docs/02-engenharia-de-requisitos.md)
   - Tipos de usuário e histórias
   - Requisitos funcionais e não-funcionais (com métricas)
   - Acessibilidade (WCAG 2.2 AA) e LGPD
   - Caso de uso UC01 – Submeter e aprovar novo sinal com vídeo
3. [Modelagem de Software (UML)](docs/03-modelagem/README.md)
4. [Projeto de Software – Proposta de Arquitetura](docs/04-arquitetura.md)
5. [Equipe e atividades por membro](docs/05-equipe.md)

## Estrutura do repositório

```
.
├── README.md                     # este arquivo
├── profile/README.md             # página inicial da organização no GitHub
├── docs/
│   ├── 01-enunciado.md
│   ├── 02-engenharia-de-requisitos.md
│   ├── 03-modelagem/             # diagramas UML (classes, sequência, atividades)
│   ├── 04-arquitetura.md
│   ├── 05-equipe.md
│   ├── assets/                   # imagens e diagramas
│   └── pdf/                      # versões originais em PDF
└── .github/                      # templates de issue e pull request
```

## Documentos originais (PDF)

- [Enunciado do trabalho final](docs/pdf/enunciado-trabalho-final.pdf)
- [Engenharia de Requisitos](docs/pdf/engenharia-de-requisitos.pdf)
- [Proposta de Arquitetura](docs/pdf/proposta-de-arquitetura.pdf)

## Critérios de avaliação

| Etapa | Pontuação | Onde está |
|---|---|---|
| 1. Engenharia de Requisitos | 3,0 | [docs/02-engenharia-de-requisitos.md](docs/02-engenharia-de-requisitos.md) |
| 2. Modelagem de Software | 2,0 | [docs/03-modelagem](docs/03-modelagem/README.md) |
| 3. Projeto de Software | 1,0 | [docs/04-arquitetura.md](docs/04-arquitetura.md) |
| 4. Repositório e Documentação | 1,0 | este README + [docs/05-equipe.md](docs/05-equipe.md) |
| 5. Código em funcionamento | 2,0 | repositório do protótipo |
| 6. Participação em palestra | 1,0 | 24/11/2026 às 13:30 |
