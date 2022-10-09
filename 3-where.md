# WHERE

## Usado para adicionar condicionais a consultas;

```sql
    SELECT coluna FROM tabela WHERE  condicao
    SELECT * FROM Person.Person WHERE LastName = 'Miller'
    SELECT * FROM Person.Person where LastName = 'Miller' AND FirstName = 'anna'
    SELECT * FROM Production.Product where color = 'red' OR Color = 'blue'
    SELECT * FROM Production.Product WHERE ListPrice > 1500
    SELECT * FROM Production.Product WHERE ListPrice > 1500 AND ListPrice < 5000
    SELECT * FROM Production.Product WHERE Color <> 'red'
    SELECT Name FROM Production.Product where Weight > 500 and Weight <= 700
    SELECT * FROM HumanResources.Employee WHERE MaritalStatus = 'M' AND SalariedFlag = 1
    SELECT BusinessEntityID FROM Person.Person WHERE FirstName = 'Peter' AND LastName = 'krebs'
    SELECT EmailAddress FROM Person.EmailAddress WHERE BusinessEntityID = 26

```

<table border='solid'>
<tr>
<td align='justify'>OPERADOR</td> <td align='justify'>DESCRIÇÃO</td>
</tr>
<tr>
<td align='justify'> = </td> <td align='justify'>IGUAL A </td>
</tr>
<tr>
<td align='justify'> > </td> <td align='justify'> MAIOR QUE </td>
</tr>
<tr>
<td align='justify'> < </td> <td align='justify'> MENOR QUE </td>
</tr>
<tr>
<td align='justify'> >= </td> <td align='justify'> MAIOR OU IGUAL </td>
</tr>
<tr>
<td align='justify'><=</td> <td align='justify'> MENOR OU IGUAL</td>
</tr>
<tr>
<td align='justify'> <> </td> <td align='justify'> DEFERENTE DE </td>
</tr>
<tr>
<td align='justify'> AND </td> <td align='justify'> OPERADOR LÓGICO E </td>
</tr>
<tr>
<td align='justify'> OR </td> <td align='justify'> OPERADOR LÓGICO OU </td>
</tr>
</table>
       