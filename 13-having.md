# HAVING

## Usado para filtar dados após o agrupamento usando o GROUP BY;

```sql
    SELECT colun, funcao_agregacao FROM tabela GROUP BY coluna HAVING funcao_agregacao operador condicao
    SELECT StateProvinceID, COUNT(StateProvinceID) AS q FROM Person.Address GROUP BY StateProvinceID HAVING COUNT(StateProvinceID) > 1000
    SELECT ProductID, AVG(LineTotal) AS media_vendas FROM Sales.SalesOrderDetail GROUP BY ProductID HAVING AVG(LineTotal) < 1000000
```