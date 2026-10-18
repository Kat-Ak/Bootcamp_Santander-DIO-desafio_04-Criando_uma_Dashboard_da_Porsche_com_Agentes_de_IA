# 🏁 Desafio 04 · PORSCHE•Core: Dashboard Interativo Web via Agentes de IA

Este projeto finaliza o Bootcamp **Santander - Excel com IA e Claude** em parceria com a [DIO](https://dio.me). Trata-se do **PORSCHE•Core**, um dashboard analítico em formato HTML único, sem as limitações visuais do Excel, publicado em ambiente real de produção via GitHub Pages.

---

## ⚠️ PROJETO EM ESTÁGIO DE MATURAÇÃO (BACKLOG OPERACIONAL)

> **Status do Projeto:** 🛠️ EM DESENVOLVIMENTO (ENTREGA DE MVP)
> **Endereço da Dashboard:** [Acessar Painel Web](https://github.io)
>
> **Nota de Governança:** O esqueleto analítico e as perguntas de negócio foram entregues para trava segura de prazo. O arquivo compilado index.html (gerado via IA no Canvas) está recebendo ajustes finos de responsividade de gráficos em ambiente de testes e será submetido à esteira de produção de forma contínua.

---

## 📈 Inteligência de Negócio & Perguntas Selecionadas

Para extrair respostas comerciais a partir das 100 vendas da base de dados, foram estabelecidas três diretrizes estratégicas:
1.  **Concentração Patrimonial (Receita por Modelo):** Quais modelos de Porsche (ex: 911 Carrera, Cayenne) geram o maior volume monetário líquido para o ecossistema?
2.  **Liquidez Operacional (Métodos de Pagamento):** Qual a preferência transacional do cliente de alto padrão (PIX, Financiamento, Cartão)?
3.  **Densidade Demográfica (Análise Estado/Cidade):** Onde estão centralizados geograficamente os maiores compradores do portfólio?

---

## ⚛️ Processo de Engenharia de Prompt & Tratamento

1.  **Sanitização Contábil:** A base bruta foi higienizada no Excel, isolando colunas tratadas e convertendo anos e preços em números puros (values) para mitigar fórmulas quebradas.
2.  **Prompt de Engenharia Usado:** *"Crie uma dashboard interativa em HTML único utilizando Chart.js para responder às 3 perguntas de negócio. Paleta de cores: Fundo Preto Obsidiana, detalhes em Dourado Champagne e fontes brancas. Inclua filtros funcionais para Modelo e Método de Pagamento nas tags HTML, embutindo os dados sanitizados da Porsche no script de forma segura."*
3.  **Tecnologia Utilizada:** Desenvolvimento em linguagem natural utilizando o ChatGPT com recurso Canvas combinado à skill de modelagem de dados.
