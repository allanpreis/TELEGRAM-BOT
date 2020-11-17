# Explicação do BOT

## Motivação para Solução

A motivação para criação desse bot é para trazer conhecimento para os novos
fãs da Marvel sobre heróis deste universo iconico, fazendo com que caso o fã
queira saber quem é aquele herói, anti-herói ou vilão o mesmo pode tirar
uma foto daquele personagem e o bot o responderá quem ele é, caso queira
saber mais basta pergunta para o bot por meio de texto ou áudio quem é o
herói reconhecido pela foto tirada e ele te dará uma breve explicação sobre o
personagem evitando totalmente spoiler sobre a drama envolta da figura
apresentada.

## Como a solução funciona

Para acessar o bot é bem simples, o acesso pode ser feito atravez do link da
conversa “t.me/SlashicorpBot” ou na aba “busca” no telegram a cima das
conversas buscar por “SLASHICORP” e logo abaixo aparecerá o bot, para
iniciar uma conversa basta apenas mandar no chat “/start” ou já realizar a
pergunta para o bot, com isso ele irá iniciar a conversa. 


## Serviços Usados

Os serviços utilizados para criação desse bot foram Visual Recognition,
Watson Assistants e Speech to Text, os três serviços da fornecedora IBM
Cloud e os serviços do telegram no Node-RED. A utilização do Visual
Recognition se dá para reconhecer o que está sendo apresentado na
imagem forncedida pelo usuário e responder a ele a resposta
equivalente ao que foi fotografado, a resposta que será dada ao usuário
se dá por meio de um treinamento que é feito pelo serviço, onde se
introduz no minímo 20 imagens do personagem que deseja e depois
imagens que representaram a negativa do personagem, a partir deste
treinamento que o serviço saberá reconhecer o personagem. Watson
Assistant é utilizado para o treinamento do bot para que ele saiba
responder por meio de texto as perguntas realizadas pelo usuário, por
meio desse treinamento é dito para o serviço os heróis que ele deve
reconher e as informações que deve fornecer por meio do
reconhecimento do personagem. Por último o serviço Speech to Text,
ocorre a partir do áudio apresentando pelo usuário para o serviço, faz
com que esse áudio essa convertido por meio de texto e esse texto é
mandando diretamente parar o bot, fazendo com que ele entenda qual
foi a pergunta feita.

## Chaves de acesso

```
Visual Recognition API key: YsDJ5q0dWHm_NGXgEZtZJ8tivB928Zm81Ivafek_QIRr
```
```
Watson Assistant API key: rfS5d_9zvaunZFYre_bD_FUejDnu4rTbZfQ6CUmTUbLZ
```
```
Token Bot Telegram: 1323336145:AAFYyAR3g3avxLZG6RJj7iUhJssXrDfqImI
```

