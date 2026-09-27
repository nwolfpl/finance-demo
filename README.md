# Como o sistema lê um fundo imobiliário

Demonstração pública de um sistema de gestão financeira pessoal: dez fundos imobiliários
lidos a partir do que os administradores declaram à CVM, com a leitura de cada indicador e
um veredito por fundo.

**→ [Abrir a demonstração](https://nwolfpl.github.io/finance-demo/)**

## O que tem aqui

- `index.html` — os dez fundos, cada um com o resumo executivo: o que pesa a favor, o que
  pesa contra, o que não dá para ler, e a decisão que os números sustentam.
- `fundo-<ticker>.html` — o relatório completo de cada fundo: preço contra valor
  patrimonial pregão a pregão, rendimento pago mês a mês, decomposição do score, rumo dos
  sete fundamentos, sinais de saúde, ciclo do rendimento e o informe da CVM mês a mês.

## De onde vêm os números

Informe e balanço mensais da CVM, informe trimestral, rendimento efetivamente pago por
cota e preço de fechamento do pregão. Nenhuma casa de análise, nenhuma notícia, nenhum
documento interpretado por máquina — e cada página aponta para o gerenciador de documentos
da B3, que é a fonte.

A tendência de cada série é medida com Theil-Sen e Mann-Kendall, e a mudança de patamar com
Pettitt: estatística não paramétrica padrão de série temporal. O método **não** foi validado
contra retorno futuro, e as páginas não prometem previsão — elas dizem para onde cada
fundamento declarado está indo, e desde quando.

## O que estas páginas não são

Não são recomendação de investimento de um profissional habilitado. O veredito de cada
fundo é uma conta com régua declarada, impressa junto dele, para poder ser discutida.

Os dez fundos foram escolhidos por **cobertura de dado** — os que têm mais indicador
efetivamente medido —, e não pelos melhores vereditos: entre eles há fundo para manter,
fundo sob vigilância e fundo para ficar de fora.

## Sobre a data

Cada página é um retrato do dia em que foi gerada, impresso no topo e no rodapé. Elas não
se atualizam sozinhas.

---

Páginas geradas pelo sistema; o código do aplicativo é privado.
