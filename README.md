# Consumo de API com fetch 

## main.js

- A arrow function trata o resultado pra ele trazer como resultado só os campos que tem no formulario.

- O for in é para que cada campo do formulário armazene o nome no campo retornado pela API. Nesse momento, todos os campos da API são retornados.
    - Para que devolva só os campos do formulário é necessario um if/ternário.
    - O result é tratado como array para que as infos sejam devolvidas separadamente em seu devido campo.


- const option: Para o uso da fetch passa-se parâmetros. 
  - Um deles é o cors para dizer que esta trabalhando com a origem de servidores diferentes.

- fetch 
 - O primeiro then retorna uma promise e, por isso, precisa receber outro then. 

## Promise 

Nada mais é que um objeto criado para fazer requisições assíncronas.