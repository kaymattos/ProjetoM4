# Projeto Resília - Banco de dados da Steam

No módulo IV do curso de DESENVOLVIMENTO WEB FULL STACK da RESILIA EDUCAÇÃO, fomos orientados a organizar e filtrar um banco de dados da steam, onde realizarmos a inserção dos dados dos dados SQL no MYSql. Após, realizamos algumas perguntas e buscamos as respostas por meio consultar na base de dados.


## 🚀 Finalidade

Após escolhermos o tema, fomos elaborando as perguntas e, com isso, ficamos bem curiosos em saber as respostas que teríamos.


## 📋 Tecnologias utilizadas

🛠️No projeto, utilizamos HTML5 de forma semântica, o CSS e o MYsql
<div style="display: inline_block"><br>
<img align="center" alt="Will-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
<img align="center" alt="Will-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
</div>

# ProjetoM4
# Perguntas respondidas no site
1a : 5 Jogos grátis mais avaliados  
<br>
<br>
select name,(positive_ratings+negative_ratings)as avaliacoes,( (positive_ratings/ (positive_ratings+negative_ratings) )*100) as porcentagem_positiva, ( (negative_ratings/(positive_ratings+negative_ratings))*100)as porcentagem_negativa from steam where price = 0 order by avaliacoes desc limit 5 ;
<img src="https://raw.githubusercontent.com/Man-noel/ProjetoM4/main/imagens/1a.png">
<br>
<br>
2a : 5 jogos pagos mais avaliados  
<br>
<br>
select name,(positive_ratings+negative_ratings)as avaliacoes,( (positive_ratings/ (positive_ratings+negative_ratings) )*100) as porcentagem_positiva, ( (negative_ratings/(positive_ratings+negative_ratings))*100)as porcentagem_negativa from steam where price > 0 order by avaliacoes desc limit 5 ;
<img src="https://raw.githubusercontent.com/Man-noel/ProjetoM4/main/imagens/2a.png">
<br>
<br>
3a : 5 jogos mais avaliados por menos de 9 USS
<br>
<br>

select name,(positive_ratings+negative_ratings)as avaliacoes,( (positive_ratings/ (positive_ratings+negative_ratings) )*100) as porcentagem_positiva, ( (negative_ratings/(positive_ratings+negative_ratings))*100)as porcentagem_negativa from steam where price between 1 and 10 order by avaliacoes desc limit 5 ;
<img src="https://raw.githubusercontent.com/Man-noel/ProjetoM4/main/imagens/3a.png">
<br>
<br>
4a :	5 jogos mais avaliados 
<br>
<br>

select name,(positive_ratings+negative_ratings)as avaliacoes,( (positive_ratings/ (positive_ratings+negative_ratings) )*100) as porcentagem_positiva, ( (negative_ratings/(positive_ratings+negative_ratings))*100)as porcentagem_negativa from steam order by avaliacoes desc limit 5 ;
<br>
<img src="https://raw.githubusercontent.com/Man-noel/ProjetoM4/main/imagens/4a.png">





