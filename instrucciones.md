# API authors
-GET api/authors
    - devuelve un array con todos los autores
-GET api/authors/IDAUTOR
    - devuelve un autor a partir de su ID
-POST api/authors
    - Creamos un autor
    - Los datos del nuevo autor llegan en el BODY
    - devuelve los datos del nuevo autor insertado


# API posts
-GET api/posts
    - devuelve un array con todos los posts
-GET /api/posts/authors/IDAUTOR
    -devuelve todos los post de su autor
-POST api/posts
    - Creamos un posts
    - Los datos del nuevo autor llegan en el BODY
    - devuelve los datos del nuevo posts insertado
    - 
- -GET /api/posts/authors
    -devuelve los autores con todos sus datos y los datos del posts

i.e. json
{
    "title":
    "description":
    "created_at":
    "category":
    "authors_id": [{}]
}