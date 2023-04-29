<h2 align="left">
  👩🏻‍💻 Explorando os dados
</h2>

Hoje vamos bater um papo sobre Boxplot. O Boxplot é uma das visualizações mais poderosas que existe, pois ele permite que você visualize medidas estatísticas como a mediana, os quartis, os valores mínimos e máximos e os valores atípicos outliers.¹
Este gráfico foi criado pelo matemático John Tukey na década de 70 no seu livro “Exploratory Data Analysis”.

Sim, foi ele quem promoveu a análise exploratória de dados.

O gráfico possui uma estrutura formada por uma caixa retangular, uma linha cortando essa caixa e as hastes (ou bigodes) ligadas a caixa.

<p align="center"> <img src="https://github.com/claudiaanjos/exploracao-dados-python-pandas/blob/main/Dia-5/image.png" /> </p>

Os quartis são representados pelos limites da caixa, do quartil inferior (Q1) ao quartil superior (Q3). A mediana (é o Q2) é representada pela linha. Os valores mínimos e máximos são as extremidades das hastes e os outliers são todos os pontos além destes limites.

Hoje, você irá praticar algumas visualizações para entender melhor os dados e desenvolver uma análise em cima do problema.

Desenvolver estratégias para o uso da informação é uma tarefa constante, devido às diversas mudanças que ocorrem o tempo todo: os usuários estão evoluindo seus conhecimentos, novos alunos chegam, alunos que se formam saem e as informações estão sempre em movimento e transformação.

Por este motivo, é importante realizar avaliações constantes do uso da biblioteca e entender em quais cenários (tipos de usuários, estratégias de marketing, atualização de acervo, cenário sócio-político interno e externo) é melhor manter a estratégia atual ou mudá-la.

Você vai fazer dois recortes em seus dados para entender como eles se distribuíram ao decorrer desses anos e, desta forma, possa trazer inferências para levar à diretoria da biblioteca, a fim de que eles possam tomar decisões para o ano atual.

Para isso, você vai avaliar dentre os alunos de graduação e pós graduação a distribuição de empréstimos mensais por ano realizados entre 2010 e 2020 da coleção que tiver a maior frequência de empréstimos.

- Plote um gráfico para cada tipo de usuário.
- Tenha um boxplots para cada ano e analise o que ocorreu.

O que está ocorrendo ao decorrer do tempo? Houve algum ano ou anos em específico que te chamaram atenção para alguma diferença? Quais as maiores diferenças entre os empréstimos para os alunos de graduação e pós graduação?

#

### Extras

Desenvolva a tarefa uma etapa por vez:

- Verifique qual é a coleção com maior frequência para cada tipo de usuário.
- Filtre os dados com condições solicitadas
- Selecione apenas os empréstimos
- Faça a contagem de empréstimos mensais por cada ano
- Crie uma função para gerar a visualização do gráfico de box plot por cada ano.
- Crie o gráfico de boxplot

Fique livre para escolher a biblioteca que desejar para plotar o gráfico, mas não deixe de conferir a documentação:

- Matplotlib
- Pandas
- Seaborn
- Plotly

Para o Seaborn, verifique também sobre a paleta de cores e as configurações estéticas gerais dos gráficos.

Quer criar gráficos dinâmicos? Confira esse meu texto de como criar um boxplot com o Plotly.

Capriche e se atente para desenvolver um gráfico limpo e objetivo.

Caso se interesse em saber mais sobre o boxplot, confira esse artigo científico especificamente sobre o gráfico no qual é a referência anotada.
