# Analise_Estatistica_Telecom_Teste_T
Estudo de caso para a empresa de telecomunicações Megaline, visando determinar qual dos dois planos pré-pagos (Surf ou Ultimate) gera mais receita para a empresa. 

📞 Megaline: Teste de Hipóteses para Otimização de Receita (Análise de Planos)

Descrição do Projeto

Estudo de caso para a empresa de telecomunicações Megaline, visando determinar qual dos dois planos pré-pagos (Surf ou Ultimate) gera mais receita para a empresa. O projeto envolveu um pipeline completo de análise estatística, desde a preparação complexa de dados de múltiplas fontes até a inferência estatística (Teste T) para orientar a alocação do orçamento de publicidade de 2018.

O trabalho demonstra proficiência em manipulação de grandes conjuntos de dados (cinco tabelas distintas) e aplicação de estatística para responder a perguntas críticas de negócio.

🎯 Objetivo de Negócio

Determinar se há uma diferença estatisticamente significativa na receita média gerada pelos clientes dos planos Surf e Ultimate, e se a localização do cliente (NY-NJ) influencia a receita.

Metodologia e Ferramentas

1. Pré-processamento e Cálculo de Receita

Merge de Dados: Combinação de cinco tabelas de dados (users, calls, messages, internet, plans) em um único dataset analítico.

Arredondamento Personalizado: Implementação da lógica de cobrança da Megaline (arredondar minutos por chamada individual e GB de dados total mensal).

Cálculo da Receita Mensal: Desenvolvimento de uma função para calcular a receita exata gerada por cada cliente por mês, considerando franquias e cobranças excedentes.

2. Análise Comportamental e Estatística Descritiva

Métricas Chave: Cálculo da Média, Variância e Desvio Padrão dos minutos, mensagens e dados consumidos para cada plano.

Visualização de Distribuição: Uso de Histogramas para descrever o comportamento dos clientes e identificar outliers ou assimetrias nas distribuições de consumo.

3. Teste de Hipóteses

Implementação do Teste T de Student para avaliar as diferenças entre as médias com um nível de significância (alfa) de 0.05.

Teste 1 (Planos): Teste se a receita média para usuários do plano Ultimate é diferente da receita média para usuários do plano Surf.

Teste 2 (Regiões): Teste se a receita média dos usuários da área de NY-NJ é diferente da receita média dos usuários de outras regiões.

Ferramenta

Uso

Python

Linguagem de programação central.

Pandas & NumPy

Limpeza, unificação, cálculo de receita e manipulação de dados.

Matplotlib & Seaborn

Visualização das distribuições de consumo.

SciPy

Implementação do Teste T de Student (ttest_ind).

💡 Resultados Chave (Recomendações)

Plano de Maior Receita: A análise estatística revelou que o plano Ultimate gera, em média, uma receita significativamente [Insira se a média foi maior ou menor] do que o plano Surf.

Decisão Estratégica: Embora o plano Ultimate tenha um preço mensal muito maior, a diferença de receita é [Insira aqui a conclusão principal sobre o valor P], o que justifica [Insira a recomendação de negócio: ex: 'reorientar o orçamento de publicidade para atrair clientes do plano Ultimate'].

Impacto Regional: O teste regional [Insira se foi ou não rejeitada a hipótese nula] a hipótese de que a receita média dos usuários de NY-NJ é diferente de outras regiões, indicando que a estratégia de publicidade [Insira a recomendação de negócio: ex: 'não precisa ser segmentada por localização ou precisa de mais foco em outras áreas'].
