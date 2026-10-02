# 📊 Análise de Cancelamentos de Clientes (Churn)

Este projeto de Análise de Dados foi desenvolvido durante a **Jornada Python** da Hashtag Programações. O objetivo principal é analisar uma base de dados de uma empresa com mais de 50 mil clientes para identificar os principais motivos que levam ao cancelamento dos serviços (churn) e propor ações estratégicas para reverter este cenário.

## 🎯 O Problema

A empresa notou que a maioria da sua base de clientes atual é composta por clientes inativos. O desafio proposto foi explorar os dados de faturação, suporte e contratos para encontrar padrões de comportamento que antecedem o cancelamento e determinar quais ações teriam o maior impacto na retenção.

## 💡 Principais Descobertas e Soluções

Após o tratamento dos dados e a criação de gráficos de histograma para cada variável da base, foram identificados três fatores críticos de cancelamento. A correção destes problemas projeta uma melhoria drástica na retenção:

* **Duração do Contrato:** O formato de contrato mensal (Monthly) apresenta uma taxa de cancelamento desproporcionalmente alta. Incentivar contratos anuais ou trimestrais reduz a taxa global de cancelamento para **46,1%**.
* **Suporte (Call Center):** Clientes que precisam de contactar o call center mais de 4 vezes têm uma taxa de cancelamento altíssima, indicando problemas não resolvidos. Melhorar a eficiência do suporte reduz a taxa para **26,4%**.
* **Dias de Atraso:** Atrasos superiores a 20 dias no pagamento estão diretamente ligados ao fim da subscrição. A implementação de alertas preventivos de pagamento faz a taxa cair para **18,4%**.

**Conclusão:** Ao resolver estes três problemas centrais, a taxa de cancelamento global da empresa cai de quase 56% para **apenas 18,4%**.

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Python:** Linguagem base do projeto.
* **Pandas:** Utilizado para a importação, limpeza (remoção de IDs e dados nulos) e manipulação dos dados (cálculo de percentagens).
* **Plotly Express:** Construção de gráficos interativos (histogramas) para análise visual.
* **Design:** Gráficos personalizados com uma paleta de cores customizada em tons **Rosa Pastel** de alto contraste para facilitar a visualização e distinção das categorias.
