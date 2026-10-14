# PRD Polo Moda WhatsApp

## Trabalho acadêmico

Este repositório reúne o protótipo navegável desenvolvido no contexto da disciplina de Engenharia de Requisitos do curso de Análise e Desenvolvimento de Sistemas da UNIBALSAS.

O trabalho foi elaborado para apoiar a análise de uma necessidade real identificada na empresa Polo Moda Masculina, organização atuante no comércio varejista de vestuário. A solução estudada busca melhorar o atendimento realizado pelo WhatsApp, especialmente nos períodos em que os funcionários precisam atender simultaneamente clientes presenciais e consumidores dos canais digitais.

## Problema analisado

Os clientes frequentemente entram em contato pelo WhatsApp após visualizarem produtos divulgados no Instagram. As solicitações envolvem preço, fotografias, tamanhos, cores, disponibilidade e condições de retirada ou entrega.

O atendimento manual dessas perguntas repetitivas pode causar demora nas respostas, dificuldade de acompanhamento das conversas e perda de oportunidades de venda. O produto proposto busca centralizar as informações dos produtos e automatizar a primeira etapa do atendimento, preservando o encaminhamento para um funcionário quando houver necessidade de interação humana.

## Objetivo do protótipo

Demonstrar, de forma visual e navegável, os principais fluxos do MVP do sistema:

- consulta de produtos por código;
- visualização de preço, imagens, tamanhos, cores e disponibilidade;
- organização de conversas em uma fila de atendimentos;
- encaminhamento para atendimento humano;
- representação da experiência do cliente no WhatsApp.

## Telas disponíveis

### Painel de catálogo

Apresenta produtos cadastrados, código identificador, preço e disponibilidade. A tela representa a área utilizada para consulta e manutenção do catálogo.

### Fila de atendimentos

Apresenta conversas recentes e uma conversa encaminhada para atendimento humano, permitindo visualizar a solicitação do cliente e a resposta automática enviada pelo sistema.

### Fluxo automatizado no WhatsApp

Representa a consulta de um produto pelo código, o retorno das informações principais e a opção de solicitar atendimento de um funcionário.

## Escopo do protótipo

Este protótipo é uma representação de interface e fluxo. Ele não implementa integração real com WhatsApp, banco de dados, autenticação, pagamentos, estoque ou processamento de dados pessoais.

Os dados exibidos são demonstrativos e devem ser substituídos ou revisados antes de qualquer uso operacional.

## Estrutura do repositório

```text
prd-polo-moda-whatsapp/
├── README.md
├── index.html
└── .github/
    └── workflows/
        └── pages.yml
```

### `index.html`

Página principal do protótipo navegável, contendo as telas e os fluxos de demonstração.

### `.github/workflows/pages.yml`

Fluxo de automação reservado para uma futura publicação do protótipo no GitHub Pages, após validação do conteúdo e autorização para publicação.

## Privacidade e publicação

Não devem ser publicados neste repositório:

- o PDF acadêmico completo;
- nomes e matrículas dos estudantes;
- nome ou dados de contato de entrevistados;
- atas ou registros de validação com informações identificáveis;
- informações internas ou não autorizadas da organização.

## Outros trabalhos acadêmicos da faculdade

Os trabalhos a seguir também foram desenvolvidos no contexto das atividades acadêmicas da faculdade e podem ser consultados como exemplos de documentação, implementação e organização de projetos:

- [TED 01 - Documento de Visão](https://github.com/GersonResplandes/apa-2026-2-ted-01)
- [TED 02 - Central Recursiva](https://github.com/GersonResplandes/apa-2026-2-ted-02)
- [Pesquisa de CI/CD com GitHub Actions](https://github.com/GersonResplandes/pesquisa-cicd-github-actions)
