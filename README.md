## Apresentação

Somos alunos do 1º semestre (2021-1) do curso Desenvolvimento de Software Multiplataforma da Fatec São José dos Campos - Prof. Jessen Vidal.  
<br>

Integrantes da Equipe | Função | Linkedin | Github|
:--------- | :------: | :-------: | :-------:
Gabriel Camargo Leite | DT | [Linkedin](https://www.linkedin.com/in/gabriel-camargo-915452196/) | [Github](https://github.com/GabrielCamargoL)
João Marcos Oliveira Santos | DT | [Linkedin](https://www.linkedin.com/in/joaomarcosoliveiraa/) |  [Github](https://github.com/JoaoM-py)
Luiz Fernando Moloni | DT | [Linkedin](https://www.linkedin.com/in/luiz-fernando-moloni-ab9021204/) | [Github](https://github.com/FernandoGT3)
Monique Carniello | SM | [Linkedin](https://www.linkedin.com/in/monique-carniello-511ba61b6/) | [Github](https://github.com/Monique-c)
Otavio Ferraroni G Pane | DT | [Linkedin](https://www.linkedin.com/in/otavioferraronigpane)| [Github](https://github.com/OtavioPane)
Rafael Roberto Lopes | DT | [Linkedin](https://www.linkedin.com/in/rafael-roberto-lopes/) | [Github](https://github.com/Rafael-Faioli)
Thiago Henrique Ferreira | DT | [Linkedin](https://www.linkedin.com/in/thiago-henrique-ferreira-2499a41a8/) | [Github](https://github.com/ThHenrique)   
<br> 

`DT - Developers Team`  
`SM - Scrum Master`  
 
<br>
<br>

## Objetivo

Utilizando de metodologia ágil, desenvolver um site com análise de dados públicos, focando no eleitorado do Estado de São Paulo, com uma linguagem familiar ao cliente (Python) e que demonstre os dados também através de gráficos e porcentagens
<br>
<br>
## Bases de dados:

- [Eleitorado](https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1)   
Página inicial > eleitorado > 2020 > perfil eleitor por seção atual > São Paulo  
Página inicial > eleitorado > atual > perfil eleitor por seção atual > São Paulo

- [Comparecimento e abstenção](https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1)  
Página inicial > Comparecimento e Abstenção > 2016     
Página inicial > Comparecimento e Abstenção > 2018  
Página inicial > Comparecimento e Abstenção > 2020  

- [Renda](<src="CSV_Renda\pibSPcsv.csv"/>)
<br>
<br>

## Tecnologias utilizadas no desenvolvimento

<img src="Images/Tecnologias.png"/>  

<br>
<br>

## Product Backlog

O Product Backlog foi desenvolvido considerando as funcionalidades solicitadas e também a priorização requeridas pelo cliente, podendo haver mudanças na priorização ao longo do desenvolvimento do projeto, seja por fatores técnicos ou solicitação do cliente

 |Prioridade| Funcionalidade |
:---------: | :------ | 
01 | Prototipação interativa do site | 
02 | Backend no Jupyter Notebook |
03 | Visualizar os dados do eleitorado |
04 | Visualizar as cidades e regiões com maiores e menores índices |
05 | Comparar os dados de duas cidades |
06 | Visualizar os dados de comparecimento e abstenção |
07 | Relacionar dados disponíveis com informação de renda média |
08 | Relacionar dados disponíveis com representante eleito |
09 | Exportar os gráficos|

<br>
<br>

## User Stories



<h5> 1. Como jornalista quero saber a quantidade de eleitores por faixa etária do Estado de São Paulo e de cada uma de suas cidades, para utilizar esses dados em reportagens
<h5> 2. Como jornalista quero saber o estado civil dos eleitores do Estado de São Paulo e de cada uma de suas cidades, para utilizar esses dados em reportagens
<h5> 3.	Como jornalista quero saber a escolaridade declarada dos eleitores do Estado de São Paulo e de cada uma de suas cidades, para utilizar esses dados em reportagens
<h5> 4.	Como jornalista quero saber a quantidade de eleitores que solicitaram inclusão de nome social, do Estado de São Paulo e de cada uma de suas cidades, para utilizar esses dados em reportagens
<h5> 5.	Como jornalista quero poder comparar os dados de uma categoria (exemplo: escolaridade) entre duas cidades selecionadas, para utilizá-los em reportagens
<h5> 6.	Como jornalista quero saber as cidades que têm o maior e menor índice de determinada categoria (exemplo: qual cidade tem mais eleitores jovens e qual tem menos), para esses dados em reportagens
<h5> 7.	Como jornalista quero saber a renda média das cidades e regiões do Estado de São Paulo, para utilizar esses dados em reportagens
<h5> 8.	 Como jornalista quero comparar a renda média de duas cidades ou regiões selecionadas, para utilizar esses dados em reportagens
<h5> 9.	 Como jornalista quero saber qual cidade tem a maior e qual tem a menor renda média, para utilizar esses dados em reportagens
<h5> 10.	 Como jornalista quero saber a quantidade de eleitores, por faixa etária, que compareceram e que não compareceram na eleição 2020, do Estado de São Paulo e de cada uma de suas cidades, para utilizar esses dados em reportagens
<h5> 11.	 Como jornalista quero saber o a quantidade de eleitores, por estado civil, que compareceram e que não compareceram na eleição 2020, do Estado de São Paulo e de cada uma de suas cidades, para utilizar esses dados em reportagens
<h5> 12.	 Como jornalista quero saber a quantidade de eleitores, por escolaridade declarada, que compareceram e que não compareceram na eleição 2020, do Estado de São Paulo e de cada uma de suas cidades, para utilizar esses dados em reportagens
<h5> 13.	Como jornalista quero poder comparar os dados de abstenção/comparecimento de uma categoria (exemplo: escolaridade) entre duas cidades selecionadas, para utilizá-los em reportagens
<h5> 14.	 Como jornalista quero saber as cidades que têm o maior e menor índice de comparecimento e abstenção de determinada categoria para utilizá-los em reportagens
<h5> 15.	 Como jornalista quero poder relacionar o representante eleito de uma cidade com outros índices disponibilizados, para utilizar esses dados em reportagens
<h5>16.	 Como jornalista gostaria de poder automatizar a publicação de gráficos em diferentes plataformas, de maneira que possam ser utilizadas em TV, na internet, em newsletter, etc, para utilizar esses dados em reportagens

<br>
<br>
<br>

# Sprints
O desenvolvimento do projeto é dividido em quatro sprints, cada uma com 21 dias de duração, e o esforço medido de cada tarefa foi elaborado através de planning poker    
<br>        
### Sprint 01 - 08/03/2021 a 28/03/2021

Durante a primeira entrega, grande parte do esforço foi concentrado em pesquisas, planejamento e também na elaboração de um protótipo interativo do site. Além disso, iniciamos o desenvolvimento da homepage e da página de perfil do eleitorado.

Sprint Backlog | Esforço | Entrega | 
:--------- | :------: | :-------: | 
Levantamento requisitos | 13 | |
Pesquisa | 20 | |
Homepage e página de eleitorado - frontend | 8 |[Vídeo](https://youtu.be/Yx8WpT7ADQs) / [Repositório](https://github.com/fa-API-Group-02/web) ||
Protótipo interativo do site (Figma) | 13 | [Protótipo](https://www.figma.com/proto/UVEmw6ey4058ZKu0a9DaWu/FA-API-dados_eleitorais?node-id=275%3A222&scaling=scale-down-width&page-id=0%3A1) |
Demonstração do protótipo | 5 |[Vídeo](https://youtu.be/KQw8BBUtF6M) | |<br>
<br>




### Sprint 02 - 29/03/2021 a 18/04/2021
Para essa sprint, devido à uma priorização do cliente, desenvolvemos back end em Python, fazendo uso de suas bibliotecas Pandas, Numpy e Matplotlib, e do ambiente Jupyter Notebook 

Sprint Backlog | Esforço | Entrega | 
:--------- | :------: | :-------: | 
Páginas Eleitorado, Comparecimento e Renda - visualização frontend | 13 | [colocar link aqui]()/ [Repositório](https://github.com/fa-API-Group-02/web)|
Jupyter Notebook do Eleitorado - pesquisa | 13 | |
Jupyter Notebook do Comparecimento e Abstenção - pesquisa | 13 ||
Jupyter Notebook de Renda - pesquisa| 13 || 
Jupyter Notebook do Eleitorado - desenvolvimento | 13 |[Eleitorado](<src="Jupyter_Notebook\Comparecimento_Abstencao"/>) |
Jupyter Notebook do Comparecimento e Abstenção - desenvolvimento | 13 |[Comparecimento](<src="Jupyter_Notebook\Comparecimento_Abstencao"/>) |
Jupyter Notebook de Renda - desenvolvimento | 13 |[PIB](<src="Jupyter_Notebook\Comparecimento_Abstencao"/>) | <br>
<br>

### Sprint 03 - 26/04/2021 a 16/05/2021
Para a terceira entrega, planejamos desenvolver  front end e back end do site, e também realizar incrementação e possíveis alterarações no Jupyter Notebook solicitadas pelo cliente

Sprint Backlog | Esforço | Entrega | 
:--------- | :------: | :-------: | 
Jupyter Notebook- incremementação |8| |
Front end - molde dos gráficos do eleitorado | 13 |  |
Front end - molde dos gráficos de comparecimento e abstenção |13 | |
Front end - molde dos gráficos de renda |13 | |
Front end - molde dos gráficos página gráficos relevantes |13 | |
Back end - definição de rotas  |20| |
Back end - consultas do eleitorado |13 | |
Back end - consultas de comparecimento e abstenção |13 | |
Back end - consultas de renda |13 | |
Back end - consultas dos gráficos relevantes|13 | |<br>
<br>

### Sprint 04 - 17/05/2021 a 05/06/2021

Sprint Backlog | Esforço | Entrega | 
:--------- | :------: | :-------: | 
Automatizar publicação (exportar os dados para outros meios) | 20 | |
Documentação do site | 20 | |
Hospedagem | 5||
Integração do front end com a API - eleitorado |20  |  |
Integração do front end com a API - comparecimento e abstenção |20 ||
Integração do front end com a API - renda |20 ||
Integração do front end com a API - gráficos relevantes |20 ||
<br>