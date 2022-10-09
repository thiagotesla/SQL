# ORDER BY

# Ordena as colunas de forma crescente ou decrescente

```sql
    SELECT coluna FROM tabela ORDER BY coluna asc 
    SELECT coluna FROM tabela ORDER BY coluna desc

    SELECT TOP 4 Name, ProductID FROM Production.Product ORDER BY ProductID ASC
    SELECT * FROM Production.Product listPrice ORDER BY ListPrice DESC
```