# CRIANDO-UMA-TABELA-DE-LIVRARIA
- Aqui eu criei a database e a tabela de uma livraria, inserindo as definições em Livro, Autor, Sexo do Autor, Paginas, Editora, Valor, UF e o Ano de publicação:

/* CRIANDO A TABELA DA LIVRARIA */

Create DataBase Livraria;

/*USE LIVRARIA */

Use Livraria

/* CRIANDO A TABELA */

Create Table Livros(
   Livro varchar(100),
   Autor varchar(100),
   Sexo char(1),
   Paginas int(5),
   Editora varchar(30),
   Valor Float(10,2),
   UF char(2),
   Ano Int (4)
   );

-  Aqui eu inseri os dados na tabela:

   /* INSERINDO DADOS NA TABELA */
 
Insert Into Livros Values ('Cavaleiro Real','Ana Claudia','F',465,'Atlas',49.9,'RJ',2009);

Insert Into Livros Values ('SQL para leigos','João Nunes','M',450,'Addison',98,'SP',2018);

Insert Into Livros Values ('Receitas Caseiras','Celia Tavares','F',210,'Atlas',45,'RJ',2008);

Insert Into Livros Values ('Pessoas Efetivas','Eduardo Santos','M',390,'Beta',78.99,'RJ',2018);

Insert Into Livros Values ('Habitos Saudáveis','Eduardo Santos','M',630,'Beta',150.98,'RJ',2019);

Insert Into Livros Values ('A Casa Marrom','Hermes Macedo','M',250,'Bubba',60,'MG',2016);

Insert Into Livros Values ('Estacio Querido','Geraldo Francisco','M',310,'Insignia',100,'ES',2015);

Insert Into Livros Values ('Pra sempre amigas','Leda Silva','F',510,'Insignia',78.98,'ES',2011);

Insert Into Livros Values ('Copas Inesqueciveis','Marco Alcantara','M',200,'Larson',130.98,'RS',2018);

Insert Into Livros Values ('O poder de mente','Clara Mafra','F',120,'Continental',56.58,'SP',2017);


- Fiz a projeção dos dados inseridos e assim criando a tabela:

/* PROJETANDO OS DADOS INSERIDOS */


![VirtualBox_DBServer SQL_08_07_2024_21_29_56](https://github.com/GregCrovella/CRIANDO-UMA-TABELA-DE-LIVRARIA/assets/173212101/0f314190-061c-4fe9-a0ec-b8ecbbdbed82)




