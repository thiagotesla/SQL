# UNION

## Usado para juntar dados de dois ou mais SELECT

```sql
    SELECT coluna1, coluna2 FROM tabela1
    UNION
    SELECT coluna1, coluna2 FROM tabela2

    SELECT FirstName, LastName FROM person.person WHERE FirstName like '%a%'
    UNION
    SELECT FirstName, LastName FROM person.person WHERE LastName like '%a%' 
```


    Cada instrução SELECT dentro de UNION deve ter o mesmo número de colunas
    As colunas também devem ter tipos de dados semelhantes
    As colunas em cada instrução SELECT também devem estar na mesma ordem