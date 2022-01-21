# Weather Forecast With Playlist

#### Projeto desenvolvido em REACT. 😉 
#### Consumindo API's externas, à partir da documentação. 😄
#### Salvando as informçãoes somente no storage do navegador, sem utilizar back-end e banco de dados. 😃
#### Projeto estruturado em Componentes. 😊
#### Utilizando ContextApi para gerenciar os estados globais. 😆
#### Deploy no Github Pages. 😅

A partir de um nome de cidade de qualquer parte do mundo a aplicação busca na API de tempo (Weather API) a temperatura relativa da localização e assim que retornada a resposta é habilitado um botão para abrir uma lista de músicas  solicitada na API de músicas (Shazam API), onde as músicas são recomendadas de acordo com o clima atual:

+ 🎵 Caso a temperatura seja maior que 32 graus, deverá retornar Rock 🎵    
+ 🎵 Caso a temperatura seja menor que 32 e maior 24, deverá retornar Pop 🎵   
+ 🎵 Caso a temperatura seja menor que 24 e maior que 16, devera retornar Classica 🎵 
+ 🎵 E caso a temperatura seja menor que 16, deverá retornar Lofi 🎵 

Assim que retornado à lista de música, caso seja do agrado da pessoa, poderá ser salva no storage do navegador com o nome da cidade, à temperatura, a data de busca, e a  lista de músicas, com  uma página mostrando a listagem podendo ser deletadas.

**Links das API's utilizadas:** 

https://openweathermap.org/current 

https://rapidapi.com/apidojo/api/shazam 

**Link do projeto:**

https://eduardohor.github.io/weather-forecast-with-playlist/
