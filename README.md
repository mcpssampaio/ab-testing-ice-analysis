# 📈 A/B Testing & Hypothesis Prioritization - Análise de Teste A/B

Projeto avançado desenvolvido no bootcamp da **TripleTen** focado na priorização de hipóteses de negócio através dos frameworks *ICE* e *RICE*, acompanhamento de métricas acumuladas num teste A/B (conversão, receita e ticket médio), e avaliação de significância estatística em dados brutos e filtrados (remoção de anomalias/outliers).

## 🚀 Tecnologias Utilizadas
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Estatística Inferencial** (Teste de Mann-Whitney U para amostras não paramétricas)
- **Jupyter Notebook**

## 🎯 Objetivos do Projeto
- **Tratamento e Limpeza:** Importação correta de múltiplos ficheiros, padronização de nomenclatura, conversão de datas e identificação/remoção rigorosa de utilizadores sobrepostos entre os grupos A e B para evitar a contaminação dos resultados.
- **Priorização de Hipóteses:** Aplicação dos modelos ICE e RICE, analisando o impacto estratégico da variável *Reach* (Alcance) na alteração de prioridades.
- **Análise do Teste A/B:** Construção de gráficos de receitas acumuladas, tamanho médio dos pedidos (ticket médio) e taxas de conversão (incluindo diferenças relativas).
- **Tratamento de Outliers e Testes Estatísticos:** Cálculo de percentis (95 e 99) para definir limiares de anomalias no número de pedidos e valor de compra, aplicando o teste de Mann-Whitney antes e depois da limpeza.

## 💡 Principais Conclusões
A análise comprovou que o Grupo B obteve um aumento estatisticamente significativo na taxa de conversão (crescendo cerca de 16% a 17.4% face ao Grupo A), enquanto o ticket médio não apresentou diferenças reais estatísticas (sendo a variação aparente nos dados brutos totalmente explicada por um *outlier* extremo de um pedido de $20.000). O teste foi considerado bem-sucedido na conversão de novos utilizadores.
