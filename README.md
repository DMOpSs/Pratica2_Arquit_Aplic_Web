# NewtonTV - Catálogo de Filmes

## CRUD básico utilizando NodeJS, Express, EJS e MongoDB

### MongoDB:

* Document Name: cinema
* Collection Name: filmes

#### Comands:

1 - use cinema

2 - db.filmes.insertOne({titulo: 'Os Vingadores: Guerra Infinita', sinopse: 'Homem de Ferro, Thor, Hulk e os Vingadores se unem para combater seu inimigo mais poderoso, o maligno Thanos. Em uma missão para coletar todas as seis pedras infinitas, Thanos planeja usá-las para infligir sua vontade maléfica sobre a realidade.', duracao: 150, dataLancamento: '26/04/2018', imagem: 'images/posters/Avengers_Infinity_War.jpg', categorias: ['Aventura', 'Ação', 'Fantasia'], fundo: 'images/backgrounds/Avengers_Infinity_War_Background.jpg'})

3 - db.filmes.insertOne({titulo: 'Os Vingadores: Era de Ultron', sinopse: 'Ao tentar proteger o planeta de ameaças, Tony Stark constrói um sistema de inteligência artificial que cuidaria da paz mundial. O projeto acaba dando errado e gera o nascimento do Ultron.', duracao: 140, dataLancamento: '23/04/2015', imagem: 'images/posters/Avengers_Age_Of_Ultron.jpg', categorias: ['Aventura', 'Ação', 'Fantasia'], fundo: 'images/backgrounds/Avengers_Age_Of_Ultron_Background.jpg'})

4 - db.filmes.insertOne({titulo: 'Vingadores: Ultimato', sinopse: 'Após Thanos eliminar metade das criaturas vivas, os Vingadores têm de lidar com a perda de amigos e entes queridos. Com Tony Stark vagando perdido no espaço sem água e comida, Steve Rogers e Natasha Romanov lideram a resistência contra o titã louco.', duracao: 180, dataLancamento: '25/04/2019', imagem: 'images/posters/Avengers_Endgame.jpg', categorias: ['Ação', 'Ficção Científica', 'Aventura'], fundo: 'images/backgrounds/Avengers_Endgame_Background.jpeg'})
