# Arbeitsauftrag Abfragen

## 1:

```sql
select ANZAHL, sum(ANZAHL) from VERKAUFE 
    inner join REGION on ANZAHL.REGION = REGION.REGION
    inner join PRODUKTE on PRODUKTE.PRODUKT = VERKÄUFE.PRODUKT
    where KATEGORIE LIKE 'Computer' and JAHR < 2017 order by VERKAUFE.region, VERKAUFE.jahr, VERKAUFE.produkt
```


## 2:
```sql
select sum(ANZAHL) from VERKAUFE 
    inner join REGION on ANZAHL.REGION = REGION.REGION
    inner join PRODUKTE on PRODUKTE.PRODUKT = VERKÄUFE.PRODUKT
    GROUP BY VERKAUFE.PRODUKT order by VERKAUFE.produkt;
```

## 3:


```sql
select sum(ANZAHL) from VERKAUFE 
    inner join REGION on ANZAHL.REGION = REGION.REGION
    inner join PRODUKTE on PRODUKTE.PRODUKT = VERKÄUFE.PRODUKT
    GROUP BY VERKAUFE.WGRUPPE, PRODUKTE.KAEGORIE, VERKAUFE.REGION order by VERKAUFE.KATEGORIE, VERKAUFE.WGRUPPE, VERKAUFE.REGION;
```


## 4:


```sql
select sum(ANZAHL) from VERKAUFE 
    inner join REGION on ANZAHL.REGION = REGION.REGION
    inner join PRODUKTE on PRODUKTE.PRODUKT = VERKÄUFE.PRODUKT
    GROUP BY VERKAUFE.JAHR, PRODUKTE.KAEGORIE, PRODUKTE.WGRUPPE order by VERKAUFE.JAHR, PRODUKTE.KATEGORIE, PRODUKTE.KATEGORIE;
```

## 5
 
```sql
select sum(ANZAHL) from VERKAUFE 
    inner join REGION on ANZAHL.REGION = REGION.REGION
    inner join PRODUKTE on PRODUKTE.PRODUKT = VERKÄUFE.PRODUKT
    GROUP BY VERKAUFE.JAHR, PRODUKTE.KAEGORIE, PRODUKTE.WGRUPPE order by VERKAUFE.JAHR, PRODUKTE.KATEGORIE, PRODUKTE.KATEGORIE;
```

## 6

WITH Gesamt as (
    
)