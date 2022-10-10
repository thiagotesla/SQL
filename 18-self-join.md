# SELF JOIN

```SQL
    SELECT A.coluna1, A.coluna2, B.coluna1. B.coluna2 FROM tabela A, tabela B WHERE A.coluna1 = B.coluna1
    SELECT OD1.ProductID, OD1.Discount, OD2.ProductID, OD2.Discount FROM [Order Details] OD1, [Order Details] OD2 WHERE OD1.Discount = OD2.Discount
```