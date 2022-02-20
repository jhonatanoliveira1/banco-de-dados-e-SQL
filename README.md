<h1> MODELAGEM BÁSICA  </h1>

<p>  
	ENTIDADE = TABELA <br> 
	CAMPOS = ATRIBUTOS 
</p>

<h4> EXEMPLO: </h4>

<p> 
CLIENTE<br>

NOME - CARACTER(30)<br>
CPF - NUMERICO(11)<br>
EMAIL - CARACTER(30)<br>
TELEFONE - CARACTER(30)<br>
ENDERECO - CARACTER(100)<br>
SEXO - CARACTER(1)<br>
</p>


<h3> COMPARANDO OS TIPOS </h3>

<p> 
NOME - CHAR E VARCHAR<br>
NÚMERO - FLOAT E INT<br>
DOCUMENTO - BLOB<br>
TEXTO EXTENSO - TEXT<br>
</p> 

<h3> PROCESSOS DE MODELAGEM </h3>

1. MODELAGEM CONCEITUAL
2. MODELAGEM LÓGICA
3. MODELAGEM FÍSICA

<h3> INICIANDO A MODELAGEM CONCEITUAL </h3>

![GitHub Modelagem Conceitual](https://github.com/jhonatanoliveira1/banco-de-dados-e-SQL/blob/main/.github/img/modelagem-conceitual-01.PNG)

<h3> INICIANDO A MODELAGEM FÍSICA </h3>


<h4> CRIANDO O BANCO DE DADOS </h4>

```SQL

CREATE DATABASE PROJETO;

```

<h4>  CONECTANDO-SE AO BANCO </h4>

```SQL

USE PROJETO;

```

<h4> CRIANDO A TABLA DO CLIENTES </h4>

```SQL

CREATE TABLE CLIENTE (
	NOME VARCHAR(30),
	SEXO CHAR(1),
	EMAIL VARCHAR(30),
	CPF INT(11),
	TELEFONE VARCHAR(30),
	ENDERECO VARCHAR(100)
);

```
<h4> VERIFICANDO AS TABELAS DO BANCO DE DADOS </h4>

```SQL

SHOW TABLES;

```

<h4> DESCOBRINDO COMO É A ESTRUTURA DE UMA TABELA </h4>

```SQL

DESC CLIENTE;

```
