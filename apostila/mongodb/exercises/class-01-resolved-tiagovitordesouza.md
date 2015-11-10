# MongoDB - Aula01 - Exercício
autor: Tiago Souza


## Importando os restaurantes

Tue Nov 10 17:49:26.976 dropping: be-mean.restaurantes
Tue Nov 10 17:49:28.137 check 9 25359
Tue Nov 10 17:49:28.458 imported 25359 objects

## Contando os restaurantes

tiago(mongod-2.4.9) be-mean> db.restaurantes.find({}).count()
25359
