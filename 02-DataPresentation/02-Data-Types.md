Categorizar Dados
---------------------------

Todo dado pode ser qualificado por sua natureza, importante para o engenheiro de dados saber atribuir um tipo, uma categoria, uma classificação ou até mesmo a validade de um dado.

Dados podem ser:

### Numéricos

* receita;
* idade;
* temperatura;
* quantidade;
* distância.

### Categóricos

* região;
* produto;
* sexo;
* departamento;
* categoria.

### Temporais

* dia;
* mês;
* trimestre;
* ano;
* timestamp.

### Espaciais

* latitude;
* longitude;
* município;
* estado;
* país.

### Relacionais

* cliente comprou produto;
* pessoa pertence a grupo;
* cidade conecta-se a outra cidade.

### Textuais

* comentários;
* descrições;
* documentos;
* mensagens.

---

# Classificação dos dados

### O que são dados qualitativos? 

Pense em um cenário que você fez uma pesquisa de satisfação em um curso online. As notas médias mostram que a maioria dos alunos ficou relativamente satisfeita, mas isso não explica o motivo da avaliação. 

Somente olhar para os números deixa uma lacuna: o que levou alguém a dar nota 7 e não 9? O que poderia ser melhorado para aumentar a satisfação? 

É aí que entram os dados qualitativos. Ao abrir o banco de dados e ver os comentários da pesquisa, você encontra observações como “o conteúdo foi ótimo, mas os exemplos poderiam ser mais práticos”. 

Esse tipo de informação não aparece nos gráficos, mas ajuda a entender a experiência real da pessoa. 

Podemos dizer que dados qualitativos são informações não numéricas que descrevem características, atributos e percepções.  

Eles mostram o contexto e a história por trás dos resultados numéricos, revelando nuances que um número sozinho não explica. 

Agora que já entendemos um pouco o que são dados qualitativos, é hora de olhar para suas principais características e ver como eles ajudam a dar sentido às informações que coletamos.

* Características dos dados qualitativos 

Já sabemos que, os dados qualitativos não dependem de números. Eles ajudam a entender o porquê e o como das coisas e podem ser descritos por características como: 

| Característica | Descrição | Exemplo |
|---|---|---|
| **Não numéricos** | Representados em palavras, descrições ou observações | Comentários em uma pesquisa de satisfação |
| **Mostram significados** | Ajudam a entender o porquê e o como das coisas | Entrevistas revelando motivos de escolha de um produto |
| **Profundos** | Exploram detalhes e nuances que dificilmente surgem em estatísticas | Relatos de clientes contando em detalhe suas experiências |
| **Interpretativos** | Precisam ser organizados e analisados para revelar padrões | Agrupar respostas abertas em categorias como elogios, críticas e sugestões |


Tipos dos dados qualitativos 
-----------------------------

Os dados qualitativos também podem ser classificados em categorias. Essa divisão é importante porque indica de que forma eles podem ser organizados e interpretados. 

As duas principais são: 

*   **Nominais**: são categorias que não possuem ordem entre si. Elas apenas nomeiam ou identificam algo, sem hierarquia.  

**Exemplo**: estado civil (solteiro, casado, divorciado), cores favoritas (azul, verde, vermelho), ou gêneros de filme (comédia, drama, ação). 

*   **Ordinais**: são categorias que possuem uma ordem definida (hierarquia), mas que representam conceitos abstratos ou subjetivos, o que faz com que a diferença exata entre um nível e outro não possa ser medida de forma precisa. 

 **Exemplo**: nível de satisfação (insatisfeito, neutro, satisfeito), grau de escolaridade (fundamental, médio, superior), ou classificação de um serviço (bronze, prata, ouro). 

E tem ainda um caso que alguns autores preferem destacar à parte: 

*   **Binários ou dicotômicos**: são variáveis que só admitem duas categorias possíveis. 

**Exemplo**: “sim/não”, “presença/ausência” ou “aprovado/reprovado”.  

Você pode ter notado que, assim como os dados nominais, eles não têm ordem entre as categorias. E é isso mesmo!  

Na teoria fazem parte dos nominais, mas como aparecem na maioria das análises, muita gente prefere tratá-los como uma categoria à parte. 

Saber identificar os tipos de dados qualitativos já é um grande passo para trabalhar com eles de forma organizada. A próxima pergunta que surge é: como coletar esse tipo de dado? É justamente o que veremos a seguir. 


Exemplo prático de uso de dados qualitativos 
---------------------------------------------

Vamos colocar em prática e entender como esses dados podem ser aplicados em uma situação real. Um exemplo é no estudo da experiência de quem usa transporte público. 

Nesses casos, em vez de olhar só para números como tempo de viagem ou lotação, podemos conversar diretamente com os usuários por meio de entrevistas ou grupos focais. 

Então, poderíamos construir as seguintes perguntas com as possíveis opções de respostas: 

*   “_Como você avaliaria o conforto durante as viagens?_” 

(Insatisfatório – Regular – Bom – Muito bom – Excelente). 

*   “_Você já deixou de usar o transporte público por sentir insegurança?”_   
    (Sim / Não). 
*   “_Qual aspecto mais influencia sua decisão de usar esse meio de transporte?_”   
    (Preço – Segurança – Conforto – Pontualidade). 

Com essas respostas podemos rastrear pontos que dificilmente apareceriam em relatórios puramente numéricos: insegurança em determinados horários, superlotação, falta de comunicação sobre atrasos, mas também percepções positivas, como economia de custos e praticidade. 

Ao organizar as respostas em categorias, fica muito mais fácil identificar o que realmente pesa na experiência do usuário e quais aspectos merecem mais atenção. 

Até aqui vimos como ouvir relatos traz significados que não cabem em números. Mas e quando precisamos transformar essas informações em métricas objetivas?  

É isso que os dados quantitativos respondem, vamos agora explorar os dados qualitativos. 

O que são dados quantitativos?   
---------------------------------

Imagine uma empresa que coleta feedback dos clientes. Ela entende a importância de ouvir as pessoas, então adiciona um campo textual de comentários. 

Os comentários, que, como vimos, são qualitativos, ajudam a entender os motivos por trás das opiniões, mas sozinhos não permitem **quantificar** quantas pessoas estão satisfeitas ou insatisfeitas.  

Assim, fica difícil saber se a maioria aprovou ou não o serviço. 

É nesse ponto que entram os dados **quantitativos**. Eles transformam percepções em números que podem ser medidos, comparados e organizados em estatísticas, como médias e porcentagens. 

Para o caso da empresa, além dos comentários, ela também pede que cada pessoa atribua uma nota de 1 a 10 para o atendimento. 

Logo, os dados quantitativos são **informações numéricas que podem ser medidas**. Eles permitem calcular médias, modas, medianas, além de possibilitar manipulações matemáticas para melhor entendimento e visualização das informações.  

Além disso, assim como nos dados qualitativos, frequências e proporções podem ser usadas para achar padrões e facilitando generalizações em grupos maiores. 

Levando em consideração essa definição, é hora de explorar as características dos dados quantitativos e ver de que forma eles se destacam em uma análise. 

| Característica | Descrição | Exemplo |
|---|---|---|
| Numéricos | Expressos em números que podem ser contados ou medidos | Notas de 1 a 10 em uma pesquisa de satisfação |
| Mensuráveis | Permitem cálculos como médias, porcentagens e frequências | Média de vendas mensais em uma loja |
| Objetivos | Produzem resultados claros, com menos espaço para interpretações pessoais | Número de acessos a um site em determinado período |
| Generalizáveis | Podem ser aplicados a grandes grupos, facilitando a identificação de padrões e tendências | Percentual de aprovação de um produto em uma pesquisa nacional |
| Comparáveis | Possibilitam análises entre diferentes contextos ou períodos | Comparar o desempenho de duas turmas em provas padronizadas |

Essas características ajudam a entender por que os dados quantitativos são tão importantes. Mas além de como eles se apresentam, também vale conhecer seus tipos, que mostram as diferentes formas de organizar essas informações. 

Tipos dos dados quantitativos 
------------------------------

Os dados quantitativos podem ser classificados de duas formas principais: pela **natureza dos valores** e pela **escala de medição**.  

Cada uma dessas classificações mostra como os números podem ser entendidos e utilizados em análises. 

### Pela natureza dos valores 

*   **Discretos**: são dados que vêm de contagens. Eles só podem assumir valores inteiros, sem casas decimais. 

  **Exemplo**: número de clientes atendidos em um dia, quantidade de filhos em uma família. 

*   **Contínuos**: são dados que vêm de medições. Podem assumir qualquer valor dentro de um intervalo, incluindo casas decimais. 

  **Exemplo**: altura de uma pessoa, tempo de resposta em segundos, peso de um produto. 

### Pela escala de medição 

*   **Intervalares**: permitem organizar os dados em ordem e medir as diferenças entre eles, mas não possuem um “zero absoluto” (ou seja, o zero não significa ausência total do fenômeno). 

  **Exemplo**: temperatura em graus Celsius ou Fahrenheit. 

*   **De razão**: além de terem ordem e intervalos iguais, possuem zero absoluto. Isso permite comparações de proporção, como dizer que algo é o dobro do outro. 

 Exemplo: peso, idade, renda, distância percorrida. 

Saber identificar os tipos de dados quantitativos é essencial para escolher a forma certa de analisá-los. Mas antes de aplicar cálculos e comparações, é preciso entender como esses números são obtidos.  

Agora é hora de ver como esses números nascem: os métodos mais usados para coletar dados quantitativos. 


Exemplo prático de uso de dados quantitativos 
----------------------------------------------

Os dados quantitativos ganham valor quando conseguimos transformá-los em indicadores que mostram, o desempenho de um produto, serviço ou estratégia. Um exemplo está em pesquisas de satisfação, como o NPS (_Net Promoter Score)_, utilizado por empresas de diferentes setores para medir a lealdade dos clientes. 

Aqui, podemos fazer as seguintes perguntas: 

*   “_De 0 a 10, qual a chance de você recomendar nossa empresa para um amigo ou colega?_” 
*   “_De 0 a 10, como você avalia a qualidade do nosso atendimento?_”

As respostas podem ser classificadas em três grupos: 

*   Detratores (0 a 6): clientes insatisfeitos. 
*   Neutros (7 e 8): clientes indiferentes. 
*   Promotores (9 e 10): clientes fiéis e entusiasmados. 

A partir dessas respostas, calculamos um índice que combina a proporção de clientes satisfeitos e insatisfeitos, oferecendo uma visão do nível de satisfação. 

Esse tipo de dado mostra como os números conseguem resumir percepções em indicadores objetivos, facilitando comparações ao longo do tempo e apoiando decisões estratégicas 

Depois de entender como cada um funciona na prática, nada melhor do que compará-los diretamente para ver suas diferenças. 

Principais diferenças entre dados qualitativos e quantitativos   
-----------------------------------------------------------------

Antes de mergulhar nas diferenças, deixa eu te perguntar: você acha mais fácil trabalhar com números ou com descrições?  

A resposta já dá uma pista de como os dados qualitativos e quantitativos se separam. Vamos colocar os dois lado a lado para enxergar melhor: 

Perguntas frequentes sobre dados qualitativos e quantitativos 
--------------------------------------------------------------------

### **O que diferencia dados qualitativos de quantitativos?** 

Os qualitativos descrevem percepções, opiniões e contextos, enquanto os quantitativos transformam fenômenos em números e métricas. Um explica o porquê, o outro, mostra o quanto. 

### **Quais são as principais características dos dados qualitativos?** 

São não numéricos, interpretativos e profundos. Aparecem em forma de palavras ou descrições e ajudam a entender sentimentos e motivações que os números não mostram. 

### **E as características dos dados quantitativos?** 

São numéricos, mensuráveis e comparáveis. Permitem cálculos, médias e porcentagens, tornando a análise mais objetiva e generalizável. 

### **Quando devo usar dados qualitativos ou quantitativos?** 

Use qualitativos quando quiser entender opiniões e contextos. Use quantitativos quando precisar medir resultados e confirmar hipóteses. Muitas vezes, combinar os dois é a melhor escolha. 

### **Qual tipo de dado é melhor para uma análise?** 

Depende do objetivo. Se você quer descobrir por que algo acontece, use qualitativos. Se quer saber quanto acontece, use quantitativos. Cada tipo tem seu papel, e juntos oferecem uma visão mais completa.

| Aspecto | Dados Qualitativos | Dados Quantitativos |
|---|---|---|
| Natureza | Descritivos e não numéricos | Numéricos e mensuráveis |
| Exemplos comuns | Cores, nomes, opiniões, relatos | Idade, altura, renda, notas |
| Forma de análise | Padrões, temas e interpretações | Métodos estatísticos e cálculos matemáticos |
| Mensuração | Não podem ser medidos numericamente | Podem ser submetidos a operações matemáticas |
| Coleta | Entrevistas, grupos focais, observações | Questionários estruturados, escalas, medições |
| Foco principal | Explicar o porquê e o como | Mostrar quanto e quanto |

Tipos dos dados estruturais
------------------------------

Referem-se à organização, formato e regras que definem como a informação é guardada e relacionada, independentemente do seu conteúdo geográfico ou do tempo.

* **Foco principal**: Organização lógica, tipos de dados e esquemas.
* **Exemplos**: Banco de dados relacionais (tabelas SQL com colunas como ID, Nome, Preço), arquivos JSON, hierarquias organizacionais ou tipologias de clientes.
* **Importância**: Garante que a informação seja padronizada para que algoritmos consigam processá-la com eficiência.

### Dados Temporais

Representam a dimensão do tempo. Indicam quando um evento aconteceu ou como um dado se comporta ao longo de um período.
* **Foco principal**: Ordem cronológica, frequência, tendências e sazonalidade.
* **Exemplos**: Séries temporais (histórico de ações da bolsa de valores), registros de logs com timestamps (data e hora), evolução da temperatura média global por ano.
* **Importância**: Fundamental para prever comportamentos futuros (forecasting) e entender o passado (análise histórica).

### Dados Espaciais

Representam a dimensão do espaço ou geografia. Indicam onde um objeto está localizado na superfície da Terra ou em um plano coordenado.
* **Foco principal**: Coordenadas, formas geométricas (pontos, linhas, polígonos) e proximidade.
* **Exemplos**: Coordenadas de GPS (latitude e longitude), mapas de calor de criminalidade, o desenho dos bairros de uma cidade em um arquivo Shapefile ou GeoJSON.
* **Importância**: Essencial para logística, planejamento urbano, geomarketing e sistemas de navegação.

### Redes (Dados de Grafos)

Representam as relações e conexões entre diferentes entidades (nós/vértices) através de ligações (arestas).
* **Foco principal**: Conectividade, topologia, fluxos e influência.
* **Exemplos**: Redes sociais (usuários e suas amizades), malha aérea (aeroportos e os voos entre eles), internet (páginas web e hyperlinks), ou a rede elétrica de um país.
* **Importância**: Permite descobrir comunidades, identificar gargalos de infraestrutura e entender como informações ou doenças se propagam.


```text
                         DADOS
                           │
          ┌────────────────┼────────────────┐
          │                │                │
      QUANTITATIVOS    QUALITATIVOS       ESTRUTURAIS
          │                │                │
      contínuos         nominais         temporais
      discretos         ordinais         espaciais
                                           redes
```