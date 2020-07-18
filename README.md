# Projeto Be The Hero

O projeto Be the Hero foi realizado a partir da Semana Omnistack 11 da Rocketseat..

## Objetivo
O objetivo do projeto é criar um site e aplicativo para ONGS que necessitam de ajudas em dinheiro para que seus "casos" possam ser atendidos.

Foi construída uma API REST no backend, a parte visual foi feita com ReactJS no frontend e o aplicativo criado em React Native no Mobile.

## Tecnologias


- Nodejs + Express
- SQLite + Knex.js
- React
- React Native


### Para instalar a  API

```
# Clone this repository
$ git clone https://github.com/DanielObara/SemanaOmnistack11

# Go into the repository
$ cd SemanaOmnistack11/backend

# Install dependencies
$ yarn install

# Run Migrates
$ yarn knex migrate:latest 

# Run Seeds
$ yarn seed

# Run the API
$ yarn dev

# Run tests
$ yarn test 
```

### Como contribuir
- Faça um fork;
- Crie uma branch com a feature: git checkout -b my-feature;
- Faça os comits: git commit -m 'feat: My new feature';
- Faça um push da sua branch: git push origin my-feature.
