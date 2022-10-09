# BETWEEN

# Usando para obter registros que estão entre um valor mínimo e um valor máximo

```sql
    SELECT coluna FROM tabela WHERE coluna BETWEEN valor_mínimo AND valor_máximo
    SELECT Name, ListPrice FROM Production.Product listPrice WHERE ListPrice BETWEEN 1000 AND 1500
    SELECT Name, ListPrice FROM Production.Product listPrice WHERE ListPrice NOT BETWEEN 1000 AND 1500
    SELECT BusinessEntityID, HireDate FROM HumanResources.Employee where HireDate BETWEEN '2009/01/01' AND '2010/01/01' ORDER BY HireDate
```