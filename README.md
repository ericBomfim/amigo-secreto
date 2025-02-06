# Projeto Amigo Secreto

Este projeto apresenta um sistema para gerenciar um sorteio de Amigo Secreto. Os usuários podem adicionar nomes a uma lista, remover nomes já adicionados e sortear um amigo secreto de forma aleatória.

## Funcionalidades

- **Adicionar Nome**: Os usuários podem digitar um nome em um campo de texto e adicionar à lista de amigos.
- **Remover Nome**: Os usuários podem digitar o nome de um amigo em um campo de texto e removê-lo da lista.
- **Sortear Amigo Secreto**: Ao clicar no botão "Sortear Amigo", um nome é escolhido aleatoriamente da lista de amigos.
- **Mensagens de Erro**: 
  - Se um nome já estiver na lista, será exibida uma mensagem de erro informando que o nome já foi adicionado.
  - Se um nome estiver vazio, será exibida uma mensagem de erro solicitando um nome válido.
  - Se um nome não estiver na lista ao tentar removê-lo, será exibida uma mensagem de erro informando que o nome não foi encontrado.

## Como Usar

1. **Adicionar um Amigo**: Digite o nome do amigo no campo de texto "Digite o nome do amigo" e clique no botão "Adicionar". O nome será adicionado à lista de amigos.
2. **Remover um Amigo**: Digite o nome do amigo no campo de texto "Digite o nome do amigo" e clique no botão "Remover". O nome será removido da lista de amigos.
3. **Sortear Amigo Secreto**: Clique no botão "Sortear". Um nome será escolhido aleatoriamente da lista de amigos e exibido na tela.
4. **Novo Sorteio**: Clique no botão "Novo Sorteio" para limpar a lista de amigos e iniciar um novo sorteio.

## Estrutura do Código

O projeto utiliza JavaScript para gerenciar as funcionalidades e manipulação da lista de amigos. Aqui estão as principais funções usadas:

- `validarNome()`: Valida e adiciona um nome à lista de amigos.
- `removerNome()`: Remove um nome da lista de amigos.
- `aparecerNomeAmigo()`: Exibe os nomes da lista de amigos na tela.
- `limparListas()`: Limpa a exibição da lista de amigos e o resultado do sorteio.
- `limparCampo(campo)`: Limpa o campo de texto especificado.
- `sortearAmigo()`: Sorteia e exibe um amigo secreto da lista.
- `novoSorteio()`: Limpa a lista de amigos e inicia um novo sorteio.

Essas funções funcionam juntas para fornecer a funcionalidade completa do aplicativo de sorteio de amigo secreto, desde a adição de amigos até a realização e reinício do sorteio.

Quem contribuiu com o projeto:

Os instrutores dos cursos.
No forum da Alura
Varios Parceiros do Discord.
Muitos sites, pesquisa e muita persistência.
https://amigo-secreto-psi-dusky.vercel.app/
