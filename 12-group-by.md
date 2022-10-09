# GROUP BY

## Agrupa os resultados de uma consulta de acordo com um parametro passado.

```sql  
    SELECT coluna1, funcao_agregacao(coluna2) FROM tabela GROUP BY coluna1
    SELECT SpecialOfferID, SUM(UnitPrice) AS total_vendas_oferta FROM Sales.SalesOrderDetail GROUP BY SpecialOfferID ORDER BY SpecialOfferID ASC
    SELECT SpecialOfferID FROM Sales.SalesOrderDetail GROUP BY SpecialOfferID ORDER BY SpecialOfferID ASC
    SELECT ProductID, SUM(LineTotal) AS total_venda_produtos FROM Sales.SalesOrderDetail GROUP BY ProductID GROUP BY ProductID ASC
    SELECT COUNT(ProductID) AS quantidade_produtos, AVG(OrderQty) AS media FROM Production.WorkOrder GROUP BY ProductID GROUP BY ProductID ASC
```