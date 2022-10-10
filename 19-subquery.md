# SUBQUERY

## Uma consulta baseada em dados de outra consulta;

```SQL
    SELECT * FROM tabela1 WHERE coluna1 operarador (SELECT coluna2 FROM tabela2 WHERE coluna operador condicao)
    SELECT * FROM Person.Address WHERE StateProvinceID IN (SELECT StateProvinceID FROM Person.StateProvince WHERE Name = 'Alberta')
```