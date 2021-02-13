![Sobre: Título do projeto](https://github.com/gacarvalho/Projeto-ETL-Producao/blob/main/Image/Background-title.png)

# Tratamento de dados / Processo ETL na ferramenta Pentaho
  
 O objetivo do projeto era realizar o tratamento de dados de autores e produções intelectual dos programas de pós-graduação stricto sensu no Brasil. Esta versão apresenta os dados do 2018!

## Data de execução do projeto?

O projeto foi desenvolvido no mês de Janeiro de 2021 📅

---

## 📢  ETAPA 1 - EXTRAÇÃO

A primeira etapa se basea na extração dos dados, sendo os formatos dos arquivos:
 
 - [x] .csv 
 - [x] .xlsx
 
 Nesta primeira etapa, foi necessários adicionar 2 steps que suportassem receber o formato de arquivo. Logo após, foi atribuido um step para receber os erros de dados do arquivo .xlsx 
 
 ![Sobre: Extração dos dados: GIF](https://github.com/gacarvalho/Projeto-ETL-Producao/blob/main/Image/Conhecendo%20a%20base%20de%20dados.gif)
 
 ## 📢  ETAPA 2 - TRANSFORMAÇÃO
 
 Logo após a extração dos dados, é facil observar vários step necessários para a tratamento dos dados, sendo: 
 
  - [x] Stream Loockup
  - [x] Select Values
  - [x] If field value is null
  - [x] Sort rows
  - [x] Unique rows
  - [x] Dummy 
  
   ![Sobre: Extração dos dados: GIF](https://github.com/gacarvalho/Projeto-ETL-Producao/blob/main/Image/Conhecendo%20a%20base%20de%20dados_1.gif)
   
  ## 📢  ETAPA 3 - CARGAS
  
Neste processo, após realizar as cargas e os tratamentos dos dados, é possível analisar a extração para a base de dados MySQl 🗃. Essa informações são armazenadas em tabelas dimensões no padrão não relacional; As informações que contém erro de tratamento de dados é extraido para uma base no servidor no formato .csv 

 ![Sobre: Extração dos dados: GIF](https://github.com/gacarvalho/Projeto-ETL-Producao/blob/main/Image/Conhecendo%20a%20base%20de%20dados_2.gif)
  
