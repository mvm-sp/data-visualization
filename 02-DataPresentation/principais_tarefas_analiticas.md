# 16. Principais tarefas analíticas e suas representações gráficas

Cada tarefa analítica responde a uma pergunta específica sobre os dados. A escolha do gráfico deve facilitar a interpretação e evidenciar a informação que se deseja investigar.

## 1. Comparação
**Pergunta:** Qual é maior?

- **Objetivo:** comparar valores entre categorias, elementos ou períodos, identificando diferenças e semelhanças.
- **Gráfico recomendado:** barras ou colunas.
- **Exemplo:** comparar o número de funcionários de limpeza e segurança em diferentes estações de metrô.

![Comparação: funcionários por estação](imagens/01_comparacao.png)

## 2. Evolução
**Pergunta:** Como mudou ao longo do tempo?

- **Objetivo:** acompanhar variações temporais e identificar tendências, crescimentos, quedas e sazonalidade.
- **Gráfico recomendado:** linhas ou áreas.
- **Exemplo:** analisar a evolução mensal do número de passageiros de uma estação.

![Evolução de passageiros](imagens/02_evolucao.png)

## 3. Distribuição
**Pergunta:** Como os valores estão distribuídos?

- **Objetivo:** compreender a frequência, a concentração, a dispersão e a variabilidade dos valores.
- **Gráfico recomendado:** histograma, boxplot ou gráfico de densidade.
- **Exemplo:** verificar como se distribuem os tempos de espera dos passageiros.

![Distribuição dos tempos de espera](imagens/03_distribuicao.png)

## 4. Relação
**Pergunta:** Existe relação entre variáveis?

- **Objetivo:** investigar associações entre duas ou mais variáveis e identificar padrões de comportamento conjunto.
- **Gráfico recomendado:** dispersão (scatter plot).
- **Exemplo:** investigar se estações com mais passageiros por dia apresentam índices de satisfação menores.

![Relação entre demanda e satisfação](imagens/04_relacao.png)

## 5. Composição
**Pergunta:** Como o total é formado?

- **Objetivo:** mostrar como diferentes partes contribuem para um total, destacando proporções e participações relativas.
- **Gráfico recomendado:** barras empilhadas, barras de 100% ou setores (pizza).
- **Exemplo:** demonstrar a participação das equipes de limpeza e segurança no total de funcionários de uma estação.

![Composição da equipe](imagens/05_composicao.png)

## 6. Localização
**Pergunta:** Onde acontece?

- **Objetivo:** identificar a distribuição geográfica dos fenômenos e reconhecer concentrações, diferenças regionais e padrões espaciais.
- **Gráfico recomendado:** mapa de pontos, mapa coroplético ou mapa de calor.
- **Exemplo:** localizar as estações de metrô e representar a quantidade de passageiros por região.

![Mapa esquemático de demanda](imagens/06_localizacao.png)

*Representação esquemática, não corresponde ao mapa geográfico real.*

## 7. Hierarquia
**Pergunta:** Como os elementos estão organizados?

- **Objetivo:** representar níveis, agrupamentos e relações entre categorias, subcategorias e seus componentes.
- **Gráfico recomendado:** árvore hierárquica, treemap ou diagrama sunburst.
- **Exemplo:** organizar uma rede de transporte por linha, estação e equipes responsáveis.

![Hierarquia de rede, linhas e estações](imagens/07_hierarquia.png)

## 8. Fluxo
**Pergunta:** Como algo se desloca?

- **Objetivo:** demonstrar o movimento de pessoas, recursos, informações ou materiais entre origens e destinos, evidenciando direção, volume e intensidade.
- **Gráfico recomendado:** Sankey, diagrama de fluxo ou mapa de linhas de conexão.
- **Exemplo:** representar os deslocamentos de passageiros entre estações de origem e destino.

![Fluxo de passageiros](imagens/08_fluxo.png)

## 9. Anomalia
**Pergunta:** Existe algo fora do padrão?

- **Objetivo:** detectar valores ou comportamentos incomuns que se afastam do padrão esperado e podem exigir investigação.
- **Gráfico recomendado:** série temporal com linha de referência, gráfico de controle ou boxplot.
- **Exemplo:** identificar uma queda atípica no número de passageiros ou um aumento inesperado nas ocorrências de segurança.

![Detecção de anomalia](imagens/09_anomalia.png)

---

## Síntese: tarefa analítica e gráfico recomendado

| Tarefa | Gráfico mais indicado |
|---|---|
| Comparação | Barras ou colunas |
| Evolução | Linhas ou áreas |
| Distribuição | Histograma ou boxplot |
| Relação | Dispersão |
| Composição | Barras empilhadas ou setores |
| Localização | Mapas temáticos ou de calor |
| Hierarquia | Treemap ou árvore hierárquica |
| Fluxo | Sankey ou diagrama de fluxo |
| Anomalia | Série temporal ou gráfico de controle |

**Princípio fundamental da visualização de dados:** primeiro identifique a pergunta analítica que precisa ser respondida; depois escolha a representação visual que torna a resposta mais clara, precisa e fácil de interpretar.

*Os gráficos são exemplos didáticos com dados ilustrativos, destinados a demonstrar a finalidade de cada tarefa analítica.*
