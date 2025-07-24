**MovieStar** é uma aplicação web desenvolvida em PHP, com foco em permitir que usuários adicionem, avaliem e escrevam críticas sobre filmes.

## 💡 Funcionalidades

- Cadastro e login de usuários com autenticação via token
- Adição de filmes com upload de imagem
- Avaliação de filmes com notas de 1 a 5 estrelas
- Escrita e visualização de críticas e comentários
- CRUD completo de filmes e avaliações
- Integração com banco de dados relacional (MySQL)

## 🧰 Tecnologias Utilizadas

- PHP (com orientação a objetos e arquitetura MVC)
- MySQL + MySQL Workbench
- HTML5 & CSS3
- XAMPP (Apache + MySQL local)
- PDO para acesso seguro ao banco de dados

## 🗂 Estrutura

- `models/` - Classes principais (User, Movie, Review)
- `dao/` - Acesso aos dados com classes DAO
- `img/movies/` - Imagens dos filmes
- `movie_process.php` - Lógica de criação e edição de filmes
- `review_process.php` - Lógica de envio de críticas

## 📦 Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/PHP_MOVIESTAR.git