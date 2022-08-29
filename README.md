DEVSNOTES: (Sistema de anotações simples)

O que o projeto precisa fazer?

- Listar as anotações
- Pegar informações de UMA anotação
- Inserir uma anotação nova
- Atualizar uma anotação
- Deletar uma anotação

Qual a estrutura de dados?

- local para armazenar as anotações
  -- id
  -- title
  -- body

Quais os endpoints?

- (GET) /api/notes - /api/getall.php
- (GET) /api/note/123 - /api/get.php? (id)
- (POST) /api/note - /api/insert.php (title,body)
- (PUT) /api/note/123 - /api/update.php (id,title,body)
- (DELETE) /api/note/123 /api/delete.php (id)
