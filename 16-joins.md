# LEFT OUTER JOIN 

## INNER JOIN + todos os dados da tabela esquerda relacionadas 

```sql
    SELECT * FROM tabela1 LEFT OUTER JOIN tabela2 ON tabela1.coluna1 = tabela2.coluna2 
```

# RIGHT OUTER JOIN 

## INNER JOIN + todos os dados da tabela da direita relacionadas

```sql
    SELECT * FROM tabela1 RIGHT OUTER JOIN tabela2 ON tabela1.coluna1 = tabela2.coluna2 
```

# FULL OUTER JOIN

## INNER JOIN + todos os dados das duas tabelas relacionadas

```sql
    SELECT * FROM tabela1 FULL OUTER JOIN tabela2 ON tabela1.coluna1 = tabela2.coluna2 
```

    Em todos os casos é possível usar o operador IS NULL para inverter o resultado da consulta