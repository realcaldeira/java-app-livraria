## Sobre o Desafio da Rocketseat

Neste desafio, foi desenvolvido  um sistema básico para gerenciar o empréstimo de livros em uma biblioteca. O foco será na listagem de livros disponíveis e na funcionalidade de empréstimo.

Foi criado um loop de interação com o usuário, perguntando se ele gostaria de ver os livros disponíveis, caso ele afirme, a tela do console mostrará os livros disponíveis.

Caso SIM: Ele deverá escolher o id do livro, e após isso inserir o nome, no final, uma mensagem deverá ser gerada, informando que o livro foi emprestado com sucesso.

Caso NÃO: O sistema se encerrará, lembre-se de colocar uma mensagem, informando o fim da aplicação.

### Gerenciamento de Livros

- **Adicionar um novo livro**: incluindo título e autor. (Como é um desafio introdutório, você pode apenas definir já dentro da classe, igual o Gleyson ensinou nas aulas).
- **Listar todos os livros disponíveis**: mostrar apenas os livros que estão disponíveis para empréstimo.
- **Realizar empréstimo de um livro**: permitir que um usuário escolha um livro disponível e registre o empréstimo.

## Estrutura do Projeto

O projeto será dividido em algumas classes simples para manter a organização. Aqui estão as classes principais e suas funcionalidades:

### Livro

- **id**: Identificador único do livro
- **titulo**: Título do livro
- **autor**: Autor do livro (objeto do tipo Autor)
- **disponivel**: Indica se o livro está disponível para empréstimo
- dataCadastro: Data que o livro foi cadastrado
- dataAtualização: Data que o livro foi atualizado

### Autor

- **id**: Identificador único do autor
- **nome**: Nome do autor
- dataNascimento: Nascimento do autor

### Biblioteca

- **livros**: Lista de livros na biblioteca
- autores: Lista de autores da biblioteca
- emprestimos: Lista de empréstimos da biblioteca

## Regras de Negócio

### Gerenciamento de Livros

- Apenas livros marcados como disponíveis podem ser emprestados.
- O usuário deverá poder informar seu nome ao fazer empréstimo do livro

### Empréstimo de Livros

- Ao realizar um empréstimo, o livro escolhido deve ser marcado como indisponível e durante esta execução do programa NÃO poderá fazer o empréstimo do mesmo livro novamente.

<br>
 <strong><h2>🛠️ Tecnologia usada</h2></strong>
<p></p>

[<li> <strong>Java</strong></li>](https://docs.oracle.com/en/java/)
