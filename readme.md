# Tarefas

Implementar lista de `todos` baseado em chamada `Api`

## Requisitos

Lista:

- Deve carregar uma lista de `todos` assim que o navegador terminar de carregar.
- Deve ser implementado um atraso na chamada a `Api` de 2 segundos
- Equanto não carrega a lista de `todos` deve renderizar um `loading`
- Assim que a lista terminar de renderizar, o `loading` deve sumir
- Deve existir um botão no header que quando cliado deve emitir um evento que fará novamente a chamada `Api`

Link API: https://jsonplaceholder.typicode.com/todos

Item:

- Cada item deve se apresentar no formato `id - title` e no canto direito uma badge em verde se `completed == true` e amarelo caso retorne `false`
    - component: https://getbootstrap.com/docs/5.0/components/badge/

- Cada item ao ser `clicado` deverá fazer uma chamada a `Api` de users e mostrar em um `modal` no formato de formulario as informaçoes do usuario.
     - component: https://getbootstrap.com/docs/5.0/components/modal/

Link API: https://jsonplaceholder.typicode.com/users
