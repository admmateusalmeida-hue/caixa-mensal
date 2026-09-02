# Caixa Mensal

App pessoal de controle financeiro: entradas e saídas, contas fixas, compras
parceladas, categorias com orçamento, comprovantes de pagamento, reserva de
emergência e um dashboard com gráficos de pizza — tudo em uma página só.

## Link ao vivo

O app funciona de verdade (salvando dados) apenas quando aberto através do
Claude, aqui:

**https://claude.ai/code/artifact/3392952f-6916-4931-a640-de2d7d1094cd**

## Sobre este repositório

Este repositório guarda o **código-fonte** (`index.html`) como backup e
histórico de versões. Ele **não funciona sozinho** se aberto diretamente
(por exemplo, via GitHub Pages ou abrindo o arquivo local): o
armazenamento dos lançamentos depende de uma capacidade de banco de dados
que só é concedida quando a página roda dentro do ambiente do Claude.

Para usar o app no dia a dia, use sempre o link acima.

## Stack

HTML + CSS + JavaScript puro, sem build step. Persistência via
`window.claude` (Claude Artifacts runtime).
