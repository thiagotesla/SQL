# IN

## Usado junto com o WHERE para verificar se algum registro correspode a algum valor passado na lista.

```sql
    SELECT coluna FROM tabela WHERE coluna IN (valor1, valor2, valor3)
    SELECT * FROM Person.Person WHERE BusinessEntityID IN (2, 7, 13)
```