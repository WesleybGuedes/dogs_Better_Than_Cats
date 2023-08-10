## Dogs are always better than cats!!!
## Siga o passo a passo a baixo para realizar o exercicio.
<h3> Select Pet </h3>
Você gosta de ver imagens de gatinhos e cachorrinhos fofinhos? Então você vai gostar desse exercício! Vamos criar uma aplicação que exibe fotos aleatórias de cães e gatos. Você poderá escolher qual tipo de animal quer ver a imagem, ou pode escolher a opção “Surprise me” e deixar a sorte definir qual pet será exibido. Gostou da ideia? Vamos para as etapas necessárias:

Crie um novo projeto usando o npm. Instale e configure o vite para usá-lo como web server.
Crie uma nova página que tenha os seguintes elementos:
um botão com o texto Get random dog;
um botão com o texto Get random cat;
um botão com o texto Surprise me;
uma imagem que deve ter como texto alternativo Random pet. Essa imagem começará com o atributo src vazio.
Quando o botão Get random dog for clicado, faça uma requisição para a API https://dog.ceo/api/breeds/image/random. Essa API irá retornar um objeto com a imagem de um cachorro aleatório. Utilize a tag de imagem criada no item 2 para exibir a imagem retornada pela API.
Quando o botão Get random cat for clicado, faça uma requisição para a API https://api.thecatapi.com/v1/images/search. Essa API irá retornar um objeto com a imagem de um gato aleatório. Utilize a tag de imagem criada no item 2 para exibir a imagem retornada pela API.
Quando o botão Surprise me for clicado, faça duas requisições: uma para a API de imagens de gatos e outra para API de imagens de cachorros. Exiba somente a imagem da API que retornar primeiro. Ignore o resultado da segunda requisição e também ignore o resultado caso alguma requisição retorne com erro.
💡Dica: lembre-se dos métodos usados para lidar com várias promises. Qual deles pode ser usado quando queremos o retorno da promise que resolve primeiro, ignorando os casos de erro? 📚Docs: Segue os links abaixo das documentações de cada uma das API’s
