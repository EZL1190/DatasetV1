# Dataset 1

[FBI dataset](https://ucr.fbi.gov/crime-in-the-u.s/2016/crime-in-the-u.s.-2016/tables/table-1/table-1.xls#overview)

[Direkte download link](https://ucr.fbi.gov/crime-in-the-u.s/2016/crime-in-the-u.s.-2016/tables/table-1/table-1.xls/output.xls)

Eller du kan downloade den fra repositoriet (fbi.xls)

Har linket til et FBI excel dataset "Crime in the United States", som viser forskellige typer af forbrydelser fra 1997 - 2016.

Når i har downloadet filen, kommer det til at være en stor hjælp, hvis i åbner det og sletter de 3 øverste columns, og de 6 nederste og rykker resten op. Hvis i har hentet filen fra repositoriet har jeg gjort det for jer.

Hvis i sider fast med at læse fra excel filen, så check [linket](https://pythonspot.com/read-excel-with-pandas/) ud.

sheetname = 16tbl01

filtype = .xls

* Hvilket år er "Violent crime rate" højst?
* Hvilken type forbrydelse(ikke "violent crime") er der blevet begået flest af i alt i den tids periode?
* Hvad er det gennemsnitlige antal røverrier(Robbery) om året?
* Med datasettet skal i lave dictionaries med 3 forkskellige forbrydelser(ikke dem med "rate") af eget valg, hvor key er året(year) og value er fx. "violent crime", "rape", "robbery", etc. 
* Hvor mange forbrydelser(Burglary) er der blevet begået i alt fra [2000 : 2010]?


# Dataset 2

[Recipes dataset](https://www.kaggle.com/kaggle/recipe-ingredients-dataset#train.json)

Fordi man skal logge ind for at downloade data settet, har jeg lagt det i repositoriet, og fordi i kun skal bruge det ene ud af to dataset(train.json).

* I skal lave en liste/array med alle ingredienser, som er sorteret med den ingrediens der fremgår flest gange først.
* Hvilke "d, har flest ingredienser?
* i skal lave et multidimensional dictionary, hvor key er cusine og value er et nyt dictionary med de "items" som er inde for den cusine gruppe.

Har tilføjet en fil multidimensional_exemple, som er et eksemple, hvis det jeg skrev ikke gav så meget mening.
* 

