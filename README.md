# Comandos Favoritos
#### Comandos Favoritos de PHP, MYSQL, javascript e o que mais precisar

------------


### MYSQL
- Formatar data

##### Data dd/mm/YYYY

```sql
SELECT DATE_FORMAT(CAMPO,'%d/%m/%Y')
```

##### Data dd/mm/YYYY hh : mm : ss

```sql
SELECT DATE_FORMAT(CAMPO,'%d/%m/%Y %H:%i:%s')
```

- Formatar moeda 0.000,00

```sql
format(upoker_rake,2,'de_DE')`
```

- Criar uma tabela a partir de um SELECT

```sql
CREATE TABLE tabela_nova
  SELECT *
  FROM tabela_origem WHERE id = 1
```

- INSERT a partir de um SELECT

```sql
INSERT INTO destination_table(
	name, date, status
)
SELECT 
	name, date, status 
FROM 
   origin_table
WHERE
   status = 1;
```

------------


### PHP

Mostrar todos tipos de erros

```php
ini_set('display_errors', 1);
ini_set('display_startup_errors', 1);
error_reporting(E_ALL);
```
------------


### Frontend

#### Tamanho de tela mobile
Para um site não dar diferença de tamanho em dispositivos de retina display, adicione essa meta tag no cabeçalho:
`<meta name="viewport" content="width=device-width, initial-scale=1">`

#### Css apenas para o mobile

```css
@media (max-width: 813px) { 
	.id{ max-width: none;  } 
}
```
