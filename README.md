# Comandos Favoritos
#### Comandos Favoritos de PHP, MYSQL, javascript e o que mais precisar

------------


### MYSQL
- Formatar data

##### Data dd/mm/YYYY

`DATE_FORMAT(CAMPO,'%d/%m/%Y')`

##### Data dd/mm/YYYY hh:mm:ss

`DATE_FORMAT(CAMPO,'%d/%m/%Y %H:%i:%s')`

- Formatar moeda 0.000,00

` format(upoker_rake,2,'de_DE')`

------------


### PHP


------------


### Frontend

#### Tamanho de tela mobile
Para um site não dar diferença de tamanho em dispositivos de retina display, adicione essa meta tag no cabeçalho:
`<meta name="viewport" content="width=device-width, initial-scale=1">`

#### Css apenas para o mobile
`@media (max-width: 813px) {
    #frm-sucesso{
        max-width: none;
    }
    #frm-sucesso h2{
        font-size: 20px;
        padding-left: 10vw;
        padding-right: 10vw;
    }

    .paginacao-tamanho{
        padding-left: 0;
        padding-right: 0;
    }
}`
