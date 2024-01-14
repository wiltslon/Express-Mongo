# Curso Node.js

Código criado a partir das aulas do curso "Node.js: criando uma API Rest com Express e MongoDB" da Alura. 

# Installação
 Para executar o código, é necessário ter o Node.js instalado e instalar as dependências executando o comando correspondente. 

```
npm install
```

Para iniciar o servidor HTTP, utilize o comando.

```
nodemon server.js
```

O banco de dados utilizado foi o MongoDB, em sua versão na nuvem Atlas. Para conectar-se ao banco, deverá ser criado um novo banco de dados com duas coleções: "autores" e "livros".

A estrutura das coleções é a seguinte.

### autores
| Atributo | Tipo |
| ------------- | ------------- |
| nome | String |
| nacionalidade | String |

### livros
| Atributo | Tipo |
| ------------- | ------------- |
| titulo | String |
| editora | String |
| preco | int32 |
| paginas | int32 |
| autor | Object |

# Sobre
**Autor:** Wiltslon da Silva Pereira

**Email:** wiltslon@gmail.com
