# INNER JOIN

## Permite a junção entre duas ou mais tabelas, desde que hajam entrelaçamento entre todas.

```sql
    SELECT coluna FROM tabela1
    INNER JOIN tabela2 ON tabela1.coluna1 = tabela2.coluna2     

    SELECT pessoa_email.EmailAddress FROM Person.Person AS pessoa_pessoa
    INNER JOIN Person.EmailAddress pessoa_email ON pessoa_pessoa.BusinessEntityID = pessoa_email.BusinessEntityID
    WHERE pessoa_pessoa.FirstName = 'peter' AND pessoa_pessoa.LastName = 'krebs'

    SELECT BusinessEntityID, Name, PP.PhoneNumberTypeID, PhoneNumber FROM person.PersonPhone AS PP
    INNER JOIN person.PhoneNumberType PT ON PP.PhoneNumberTypeID = PT.PhoneNumberTypeID

    SELECT PA.AddressID, PA.City, PSP.StateProvinceID, PSP.Name FROM Person.Address AS PA
    INNER JOIN Person.StateProvince PSP ON PA.StateProvinceID = PSP.StateProvinceID
```