# Atividade3-BackEnd

=====================================================================

*Tabela Fictícia: livros*

=====================================================================

CREATE TABLE livros (

  id INT PRIMARY KEY,
  
  titulo VARCHAR(100),
  
  autor VARCHAR(100),
  
  ano_publicacao INT,
  
  genero VARCHAR(50)
  
);

=====================================================================

*Operações CRUD*

=====================================================================

1. 🟢 CREATE — Inserir um livro

INSERT INTO livros (id, titulo, autor, ano_publicacao, genero)

VALUES (1, 'Dom Casmurro', 'Machado de Assis', 1899, 'Romance');

2. 🔵 READ — Selecionar o livro

SELECT * FROM livros WHERE id = 1;

3. 🟡 UPDATE — Editar o livro (alterar o ano de publicação)

UPDATE livros

SET ano_publicacao = 1900

WHERE id = 1;

4. 🔴 DELETE — Apagar o livro

DELETE FROM livros WHERE id = 1;
