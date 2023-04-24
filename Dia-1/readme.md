<h2 align="left">
  👩🏻‍💻 Importação de dados
</h2>

Iremos explorar os dados de empréstimos dos acervos do sistema de bibliotecas da UFRN.

Um dos objetivos de uma biblioteca é garantir que os materiais informacionais estejam sendo utilizados. Os empréstimos realizados podem ser um indicador, mesmo que de forma básica (pois você não consegue garantir que haja uma leitura ou utilização real).

Por este motivo, entender a quantidade de empréstimos se torna importante.

Questões de diferentes perspectivas podem surgir como:

- A quantidade de empréstimos está aumentando ou diminuindo ao decorrer dos últimos anos?
- Em quais bibliotecas do sistema estão a maior quantidade de empréstimos?
- Quais são os temas mais emprestados? E os menos?

Com estas e outras informações será possível entender o cenário e apresentá-lo à diretoria das bibliotecas, para que possam tomar melhores decisões na melhoria da infraestrutura, dos recursos e processos da unidade de informação.

Mas para que tudo isso seja realizado, você precisará começar com a coleta e organização dos dados para que possa trabalhar com eles nas próximas análises.

Você trabalhará com dados apenas dos últimos 10 anos disponíveis. Por isso, importe para seu Jupyter Notebook os dados de:

- [Empréstimos dos acervos das bibliotecas de UFRN](https://github.com/FranciscoFoz/7_Days_of_Code_Alura-Python-Pandas/tree/main/Dia_1-Importando_dados/Datasets/dados_emprestimos)
- [Exemplares do acervo](https://github.com/FranciscoFoz/7_Days_of_Code_Alura-Python-Pandas/blob/main/Dia_1-Importando_dados/Datasets/dados_exemplares.parquet)

Temos diversas tabelas diferentes e isso dificulta o trabalho. 
Portanto, o seu primeiro passo é unificar em um único Dataframe todos os dados pertinentes para a análise.

Comece pelos empréstimos e você terá os dados das transações. 
Depois, mescle com os dados do acervo, para que você possa entender, por exemplo, de qual biblioteca era o material emprestado ou a qual tema ele se referia. Elas se relacionam pela coluna de código de barras de cada material.

Lembre-se que é muito comum receber dados nulos ou duplicados, por isso não deixe de fazer a limpeza.

#

### Extras

- [Documentação do Pandas](https://pandas.pydata.org/docs/user_guide/io.html) das diferentes formas de entrada de dados;
- Formato de [arquivo Parquet](https://www.alura.com.br/artigos/arquivos-parquet);
- Artigo de ["Como jogar dados fora com Pandas?"](https://franciscofoz.medium.com/como-jogar-dados-fora-com-pandas-23a5be871aac).
