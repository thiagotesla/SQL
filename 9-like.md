# LIKE

## Usado para buscar um padrão especifico em uma coluna;


```sql
    SELECT coluna FROM tabela WHERE coluna LIKE padrão
    SELECT * FROM Person.Person where FirstName like 'A%'
    SELECT * FROM Person.Person where FirstName like 'A_'
    SELECT * FROM Person.Person where FirstName like '%A%'
    SELECT * FROM Person.Person where FirstName like '_N_'
    SELECT * FROM Person.Person where FirstName like '%A_'
    SELECT * FROM Person.Person where FirstName like '_A%'
```

    Com o LIKE é possivel usar o percentual (%), para zero, um dois ou vários carateres e o underline (_), para um único caracter.
    O LIKE não é Case-sensitive.  