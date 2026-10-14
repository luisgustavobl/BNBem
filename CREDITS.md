# Créditos

O BNBem foi construído pela equipe TATU durante o Hackathon Siará Tech Summit 2026. O edital (item 8.9) permite usar bibliotecas e fontes abertas, desde que sejam creditadas. Esta página lista tudo o que veio de terceiros.

## Bibliotecas de código aberto

| Biblioteca | Versão | Uso no BNBem | Licença | Fonte |
|---|---|---|---|---|
| pdf.js (Mozilla) | 3.11.174 | Ler os PDFs do pacote do projeto | Apache License 2.0 | [mozilla.github.io/pdf.js](https://mozilla.github.io/pdf.js/) |
| pdf-lib | 1.17.1 | Gerar o parecer em PDF | MIT | [pdf-lib.js.org](https://pdf-lib.js.org/) |

As duas são carregadas pelo CDN [cdnjs](https://cdnjs.com/).

## Fonte tipográfica

| Fonte | Uso | Licença | Fonte |
|---|---|---|---|
| Heebo | Toda a interface, seguindo a identidade visual do BNB | SIL Open Font License 1.1 | [Google Fonts](https://fonts.google.com/specimen/Heebo) |

## Inteligência artificial

| Serviço | Uso |
|---|---|
| Claude (Anthropic), pelo runtime de artefatos do claude.ai | Síntese, sugestão dos critérios de Frascati, sinais de não-rotina e assistente "Pergunte ao BNBem" |

A IA só sugere. A classe é recomendada por uma árvore de regras determinística, e a decisão final é do analista.

### Ferramentas de IA usadas pela equipe

| Ferramenta | Uso |
|---|---|
| NotebookLM (Google) | Estudo da Lei do Bem e das normas desde o início do projeto e, depois, conferência de erros que a equipe vinha enfrentando |
| Antigravity (Google), com Claude Opus 5.5 e Gemini 3.8 | Revisão do relatório do projeto |
| ChatGPT (OpenAI) | Nova revisão do relatório |
| Claude (Anthropic) | Copiloto durante o evento (normas, fluxo, pitch e documentação) e correção final dos problemas apontados nas revisões |

### Como as revisões aconteceram

Desde o começo, a equipe usou o NotebookLM como uma forma alternativa de estudar a Lei do Bem e as normas ligadas a ela. Em certo momento, ele também passou a servir para conferir erros que a equipe vinha enfrentando.

A partir daí, o relatório do projeto passou de uma ferramenta para outra, num handoff em sequência: primeiro para o Antigravity, com os modelos Claude Opus 5.5 e Gemini 3.8, e depois para o ChatGPT. Por fim, voltou ao Claude, onde a equipe corrigiu os problemas encontrados ao longo do caminho.

Essa sequência funcionou como uma revisão cruzada. Cada ferramenta recebia o relatório sem ter participado de como ele foi feito e, por isso, o lia com outros olhos. Como modelos diferentes tendem a reparar em coisas diferentes, erros que tinham passado despercebidos por um eram apontados por outro.

O código do protótipo foi escrito durante o hackathon (edital, item 8.7).

## Identidade visual

- **Banco do Nordeste do Brasil (BNB):** as cores (bordô institucional e paleta de apoio), a fonte Heebo e o "canto folha" dos cartões vêm do portal público [bnb.gov.br](https://www.bnb.gov.br). O manual usado pela equipe foi reconstruído a partir desse portal e **não é oficial**. A marca e o logotipo do BNB pertencem ao Banco do Nordeste e aparecem no protótipo apenas como referência ao desafio proposto pelo banco.
- **Hubine:** ambiente de inovação aberta do Banco do Nordeste, por meio do qual o banco propôs o desafio. É citado no protótipo.
- **Marca TATU:** criada pela equipe durante o evento.

## Base normativa

Os textos normativos são atos oficiais públicos. Os trechos da base de conhecimento indicam a fonte de cada item.

| Documento | Fonte oficial |
|---|---|
| Lei nº 11.196/2005 (Lei do Bem), Cap. III | [planalto.gov.br](https://www.planalto.gov.br/ccivil_03/_ato2004-2006/2005/lei/l11196compilado.htm) |
| Decreto nº 5.798/2006 | [planalto.gov.br](https://www.planalto.gov.br/ccivil_03/_ato2004-2006/2006/decreto/d5798.htm) |
| Instrução Normativa RFB nº 1.187/2011 | [MCTI](https://antigo.mctic.gov.br/mctic/opencms/legislacao/outros_atos/instrucoes_normativas/Instrucao_Normativa_SRFMF_n_1187_de_29082011.html) |
| Portaria MCTI nº 9.563/2025 | [MCTI](https://antigo.mctic.gov.br/mctic/opencms/legislacao/portarias/Portaria_MCTI_n_9563_de_03112025.html) |
| Guia Prático da Lei do Bem (MCTI) | [preencher link] |
| FAQ da Lei do Bem (MCTI) | [preencher link] |
| Guia do Usuário do FORMP&D (MCTI) | [formpd.mcti.gov.br](https://formpd.mcti.gov.br) |
| Manual de Frascati 2015 (OCDE) | [preencher link] |

O Manual de Frascati é citado como referência conceitual para os cinco critérios de P&D. O documento não é redistribuído neste repositório.

## Evento

- **Realização:** Sebrae/CE
- **Desafio, especialistas de negócio e premiação:** Banco do Nordeste, por meio do Hubine
- **Metodologia e condução:** Voa Inovação
- **Mentores do BNB:** Luciano Cabral Rôla Neto, Ronaldo Falcão Ribeiro e José Alzir Bruno Falcão

A massa de dados fictícia usada no evento pertence à organização do desafio e não é distribuída aqui.

## Equipe TATU

Matheus Emanuel de Araújo · Ângelo Mendonça Rodrigues · Wanessa Honorato Vieira · Luís Gustavo de Brito Lima · João Pedro Leão
