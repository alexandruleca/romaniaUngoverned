## Romania Ungoverned

#### Data Support

"Romania Ungoverned" seeks to offer the data support needed to analyze the relationship between the Romanian Parliament and the Romanian Government, in terms of their regulatory prerogatives. It provides data on which political scientists and historians might base their analysis. 

We offer data support by gathering, cleaning, and analyzing information regarding the ordinances and laws passed by the Romanian Government, the Romanian Parliament, the French Government, and the French Parliament between January 1, 1992 (the start date when Romanian ordinances become available online) and December 21, 2020 (the last day of the Orban Cabinet), though it can be extended further. 

#### Clarifications about data

- The information that is gathered regarding the Romanian ordinances comprises: date of the ordinance, title of the ordinance, status (approved, rejected, forgotten, abrogated through another ordinance, abrogated through law), name and date of the law approving, rejecting, abrogating the ordinance, if any. 

- The information that is gathered regarding the Romanian laws comprises title and date of the law.

- The information that is gathered regarding the French ordinances and laws comprises name and date of the ordinance / law. No correlation between a French ordinance and the law approving or rejecting it could be established as 1. the French website does not present information in such a way and 2. until 2008 the French Constitution stipulated that an ordinance was considered approved if the Parliament did not pass a law stating otherwise, which in fact meant that at least until 2008 there are ordinances fully supported by the Parliament but without having a law attached to the ordinance. 

French ordinances and laws were considered as Romania's constitutional model has been modeled after the French constitutional model. Thus, a comparison between the Romanian and the French usage of ordinances and laws seemed useful in analyzing how much or how little what is resembles what should have been.

#### Getting started

Run ```scrapRowLaws.py``` to get the Romanian laws: 

```
scrapRouLaws.py // results in => rouLaws3jan.csv
```

Run ```scrapRouOrdos.py``` to get the Romanian ordinances:

```
scrapRouOrdos.py // results in => rouOrdos3jan.csv
```

Run ```scrapRouOrdosAbrog.py``` to get the abrogated Romanian ordinances:

```
scrapRouOrdosAbrog.py
```

Run ```scrapFrLawsAndOrdos.py``` to get the French laws and ordinances:

```
scrapFrLawsAndOrdos.py
```
- french ordos initial data as of 3 jan.pages // results in => french ordos as of 3 jan.csv
- french laws initial data as of 3 jan.pages // resuts in => french laws as of 3 jan.csv

Finally run:

```
analysisRouFr.py
```

and

```
analysisRouOrdosGovAndParl.py
```