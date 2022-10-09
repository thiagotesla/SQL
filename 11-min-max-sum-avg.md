# MIN, MAX, SUM, AVG

## Funções de agragação. 

```sql
    SELECT MIN(LineTotal) AS menor_venda FROM Sales.SalesOrderDetail

    SELECT MAX(LineTotal) AS maior_venda FROM Sales.SalesOrderDetail

    SELECT SUM(Linetotal) AS total_vendas FROM Sales.SalesOrderDetail

    SELECT AVG(Linetotal) AS media_vendas FROM Sales.SalesOrderDetail
```

O AS é usado para dar um nome ao resultado da consulta