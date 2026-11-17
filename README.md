# BI Toolkit

**Padrões reutilizáveis de Business Intelligence: DAX, Qlik Sense, SQL e automações.**

Repositório de referência com soluções para problemas recorrentes de modelagem, cálculo de indicadores, tratamento de dados e automação. Cada padrão é documentado de forma curta, com o problema que resolve, a lógica aplicada, o código e os critérios de uso, para que possa ser aplicado e mantido por qualquer pessoa.

[![GitHub](https://img.shields.io/badge/GitHub-rafaellacorrea--data-181717?style=flat)](https://github.com/rafaellacorrea-data)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rafaella--correa-0A66C2?style=flat)](https://www.linkedin.com/in/rafaella-correa)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-green?style=flat)

---

## Por que este repositório

Em BI, boa parte do trabalho se repete: calendário de dias úteis, comparação com o ano anterior, cargas em camadas, segurança por linha. Documentar esses padrões reduz retrabalho, mantém as regras de cálculo consistentes entre painéis e facilita a manutenção por outras pessoas.

## Estrutura

| Pasta | Escopo | Temas |
|---|---|---|
| [`dax/`](dax/) | Power BI: medidas, inteligência de tempo e modelagem | Comparação com o ano anterior, acumulados |
| [`qlik/`](qlik/) | Qlik Sense: load script, QVD, variáveis e segurança | Extração em loop para QVD, Section Access |
| [`sql/`](sql/) | Consultas analíticas e tratamento de dados | Junções, deduplicação, validação |
| [`automacoes/`](automacoes/) | Python e Google Apps Script | Cargas em blocos, agendamentos com feriados |

## Índice de padrões

| Padrão | Ferramenta | Status |
|---|---|---|
| Extração em loop para QVD | Qlik Sense | Em construção |
| Section Access por região | Qlik Sense | Em construção |
| Dias úteis no Power Query | Power BI | Planejado |
| Comparação com o ano anterior (SPLY) | DAX | Planejado |
| Agendamento que ignora fins de semana e feriados | Google Apps Script | Planejado |

## Como cada padrão é documentado

Todos os arquivos seguem o mesmo modelo:

1. **Problema:** a situação de negócio ou técnica que motiva o padrão.
2. **Solução:** a lógica, explicada em linguagem simples.
3. **Código:** a implementação, comentada.
4. **Quando usar e quando não usar:** premissas, limitações e alternativas.
5. **Validação:** como conferir se o resultado está correto.

## Convenções

- Arquivos em minúsculas e com hífen, por exemplo `dax/comparacao-ano-anterior.md`.
- Regra de negócio escrita antes do código.
- Código comentado em português.

## Sobre os dados

Todos os exemplos usam dados fictícios gerados por script ou dados públicos com a fonte citada. Nenhum conteúdo vem de sistemas, bases ou códigos de empresas.

---

**Rafaella Corrêa** · Analista de Business Intelligence · Curitiba, Brasil
Distribuído sob a licença MIT.
