# Pokemon-Card

Chegando ao javascript, criamos um array para as cores correspondentes a cada tipo de pokemon. Em seguida, armazenamos o link pokeAPI em uma constante chamada URL. Também obtemos os elementos carde btne os atribuímos a variáveis.

Na próxima etapa, criamos uma função chamada getPokeData. Dentro desta função, geramos um número aleatório entre 1 e 150. Este número será nosso id.

Criamos o finalUrlcombinando o URLe a idstring. Agora vamos buscar os dados para o pokemon correspondente ao id gerado. Usamos esses dados para criar o cartão.

Para a próxima etapa, criamos uma função chamada generateCard(). Agora, usando os dados obtidos da API, obtemos os dados necessários e os atribuímos às variáveis.

Agora usamos o tipo pokemon para obter um valor de cor correspondente do typeColorarray. Agora atribuímos esse valor a uma variável chamada themeColor.

Em seguida, geramos HTML para o cartão usando variáveis ​​que criamos. Neste ponto, chamamos a função appendTypescom o parâmetro data.types.
A appendTypesfunção itera sobre a matriz de tipos e envolve cada tipo dentro de um elemento span. Este spanelemento é então anexado ao typesdiv.

Também chamamos a styleCardfunção que aplica o themeColorao fundo do cartão como gradiente radial e o elemento span dentro dos tipos div. E é isso. Nosso gerador aleatório de cartas pokemon já está pronto.
