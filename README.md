# Pokemon-Card

Aprender nem sempre é doloroso, hoje coloquei em pratica consumo de API's com Javascript. 



Pra entender oque é uma API sugiro esse artigo: https://www.robinwieruch.de/what-is-an-api-javascript/  



Usei fetch pra conexão com api, uma rápida explicação : Fetch é composto por promisses javascript, e basicamente o primeiro .then() recebe a resposta da requisição e por meio de uma função transformamos essa resposta em um json, logo depois o segundo .then() recebe essa resposta, e a imprime no console. Por fim temos o catch que só é executado caso aconteça algum erro na operação e a imprime uma mensagem de erro console.



Para a próxima etapa, uma função chamada generateCard(). Agora, usando os dados obtidos da API, obtemos os dados necessários e os atribuímos às variáveis. Em seguida, geramos HTML para o cartão usando variáveis ​​que criamos.


