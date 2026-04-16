# Statistik om de danske folketingsvalg, 1901–2022
Danmarkshistorien.dk / Aarhus Universitet
Denne repository indeholder et datasæt med resultater fra alle danske folketingsvalg i perioden 1901–2022, herunder dokumentation om datasættet.

## Indhold
- *Folketingsvalg_statistik.csv* // Hoveddatasættet med valgresultater pr. parti og valg i .csv format.
- *Folketingsvalg_statistik_1901-2022.xlsx* // Hoveddatasættet med valgresultater pr. parti og valg i .xlsx format.
- *Dokumentation.pdf* // Forklaring af datastruktur, variable, partier, forkortelser, navneskift m.m.

## Databeskrivelse
Datasættet indeholder:

- Alle opstillingsberettigede partier fra 1901 til 2022.
- Stemmetal, procentandele og mandater.
- Markering af regeringspartier og statsministerpartier.
- Parti‑ID, forkortelser og farvekoder.
- Noter om særlige valg (f.eks. 1915 “fredsvalget”, flere valg i 1920 og 1953).

Variablerne er dokumenteret yderligere i afsnit 1.2 af *Dokumentation.pdf* eller under *Struktur* i denne Readme.

Resultater fra de enkelte valgkredse eller fra landstinget er ikke inkluderet, men kan findes i Danmarks Statistisks opgørelser efter hvert folketingsvalg:
- Hovedside om folketingsvalgene: [https://www.dst.dk/da/Statistik/emner/borgere/demokrati/folketingsvalg]
- Historiske udgivelser om folketingsvalgene før 2007: [https://www.dst.dk/da/Statistik/udgivelser/VisPub?cid=20332]

## Struktur
| Kolonne | Indhold |
| :------------- | :------------- |
| Parti | <p>Partiets navn.</p><p>I de fleste tilfælde er partiernes officielle navne i en eller anden grad forkortet. Fx er Venstre – Danmarks liberale parti konsekvent forkortet til Venstre og Danmarks Retsforbund forkortet til Retsforbundet.</p><p>Enkelte af partiernes officielle navne fremgår i visse tabeller, hvor det er kontekstmæssigt fyldestgørende. Dette gælder fx Danmarksdemokraterne – Inger Støjberg og Partiet Klaus Riskær Pedersen.</p><p>Til- og fravalg er udelukkende et skøn fra danmarkshistorien.dk i forhold til, hvad der formidler historien bedst muligt. Se mere under afsnittet ”Navneskift” i dokumentationen</p> |
| Forkortelse | Unik forkortelse skabt af danmarkshistorien.dk. Se mere under afsnittet ”Forkortelser” i dokumentationen |
| ID | Unik numerisk ID skabt af danmarkshistorien.dk. Se mere under afsnittet ”Partier og parti-ID’er” i dokumentationen |
| Farve | Partifarver (angivet som en sekscifret hex-kode) skabt og anvendt af danmarkshistorien.dk. grafer til folketingsvalgene |
| Valg | Dagen for folketingsvalgets afholdelse. |
| Stemmetal | Antallet af gyldige stemmer på det enkelte parti ved folketingsvalget |
| Pct. af stemmer | Procentfordelingen af gyldige stemmer ved folketingsvalget. |
| Mandater | Antallet af mandater det enkelte parti tildeles efter valget. |
| Mandatprocent | Procentfordelingen af mandater efter folketingsvalget. |
| Regeringsparti | <p> Angiver hvorvidt et parti blev en del af regeringen efter valget.</p><ul><li>”SAND” indebærer, at de gik med i regering.</li><li>”FALSK” indebærer, at de ikke gik med i regering.</li></ul><p>Feltet inkluderer ikke ministre for Island, Grønland og Færøerne, da disse ofte stod uden for partierne.</p>|
| Statsministerparti | <p> Angiver hvorvidt et parti bestred statsministerposten efter regeringsdannelsen.</p><ul><li>”SAND” indebærer, at partiet bestred posten efter valget.</li><li>”FALSK” indebærer, at partiet ikke bestred posten efter valget.</li></ul> |
| Partileder | <p>Det enkelte partis frontfigur i valgsammenhæng.</p><p>”Partileder” gælder også en formand, der har funktion af partiets leder, fx i Socialdemokratiet og Venstre. Partier som Radikale Venstre har både en landsformand og en politisk leder, og det er således her, at det er den politiske leder, der bliver oplistet i tabellen, da den politiske leder er formand for folketingsgruppen og deraf har betydning for folketingsvalgsresultaterne.</p><p>Er flere partiledere angivet, vil de være separeret af et komma. Fx står der under Det moderate Venstre i 1901 ”Klaus Berntsen, Niels Neergaard”.</p>|
| Note | <p>Kommentarer til valget eller enkelte partier.</p><p> Noterne er udarbejdet af danmarkshistorien.dk. Noterne er ofte ikke fyldestgørende for at forklare hele valgsituationen, og der opfordres derfor til at læse danmarkshistorien.dk’s artikler om folketingsvalgene, hvis du har nogle spørgsmål.</p> |

## Oprindelse og ophav
Data og dokumentation blev oprindeligt udarbejdet af redaktionen på  danmarkshistorien.dk ved Aarhus Universitet.
Kildedata stammer fra Danmarks Statistik, suppleret med historiske oplysninger fra Folketingets Oplysning og universitetsforskning.

Selvom danmarkshistorien.dk i dag ikke længere eksisterer i samme form, stammer dette materiale direkte fra det oprindelige projekt. Artiklerne udarbejdet i forbindelse med folketingsvalgdatasættet kan i dag findes på Lex.dk[https://lex.dk/].

## Licens
Datasættet er udgivet under Open Data Commons Open Database License (ODbL):

Du må frit:
- Kopiere, dele og anvende datasættet.
- Ændre, transformere og viderebearbejde det.
- Så længe du krediterer danmarkshistorien.dk / Aarhus Universitet som kilde.

***

# Statistics on Danish Parliamentary Elections, 1901–2022
Danmarkshistorien.dk / Aarhus University
 
This repository contains a dataset with results from all Danish parliamentary elections in the period 1901–2022, including documentation about the dataset.

Note that the documentation and datasets are in Danish.
 
## Contents
- *Folketingsvalg_statistik.csv* // The main dataset with election results per party and election in .csv format.
- *Folketingsvalg_statistik_1901-2022.xlsx* // The main dataset with election results per party and election in .xlsx format.
- *Dokumentation.pdf* // Explanation of data structure, variables, parties, abbreviations, name changes, etc.
  
## Data Description
The dataset contains:
 
- All eligible parties from 1901 to 2022.
- Vote counts, percentage shares, and seats.
- Indication of government parties and prime ministerial parties.
- Party ID, abbreviations, and colour codes.
- Notes on special elections (e.g. the 1915 "peace election", multiple elections in 1920 and 1953).
The variables are further documented in section 1.2 of *Dokumentation.pdf* or under *Structure* in this Readme.
 
Results from individual constituencies or from the upper chamber (Landsting) are not included, but can be found in Statistics Denmark's publications after each parliamentary election:
- Main page on parliamentary elections: [https://www.dst.dk/da/Statistik/emner/borgere/demokrati/folketingsvalg]
- Historical publications on parliamentary elections prior to 2007: [https://www.dst.dk/da/Statistik/udgivelser/VisPub?cid=20332]
  
## Structure
| Column | Content |
| :------------- | :------------- |
| Parti | <p>The name of the party.</p><p>In most cases, parties' official names have been abbreviated to some degree. For example, Venstre – Danmarks liberale parti is consistently shortened to Venstre, and Danmarks Retsforbund is shortened to Retsforbundet.</p><p>The full official names of certain parties appear in some tables where contextually appropriate — for example Danmarksdemokraterne – Inger Støjberg and Partiet Klaus Riskær Pedersen.</p><p>Inclusions and exclusions are solely a judgement call by danmarkshistorien.dk based on what best communicates the history. See the "Navneskift" section in the documentation for more.</p> |
| Forkortelse | Unique abbreviation created by danmarkshistorien.dk. See the "Forkortelser" section in the documentation for more. |
| ID | Unique numeric ID created by danmarkshistorien.dk. See the "Partier og parti-ID’er" section in the documentation for more. |
| Farve | Party colours (given as a six-digit hex code) created and used by danmarkshistorien.dk in charts for the parliamentary elections. |
| Valg | The date on which the parliamentary election was held. |
| Stemmetal | The number of valid votes cast for the individual party in the parliamentary election. |
| Pct. af stemmer | The percentage distribution of valid votes in the parliamentary election. |
| Mandater | The number of seats allocated to the individual party after the election. |
| Mandatprocent | The percentage distribution of seats after the parliamentary election. |
| Regeringsparti | <p>Indicates whether a party became part of the government after the election.</p><ul><li>"SAND" means they joined the government.</li><li>"FALSK" means they did not join the government.</li></ul><p>The field does not include ministers for Iceland, Greenland, and the Faroe Islands, as these often stood outside the parties.</p> |
| Statsministerparti | <p>Indicates whether a party held the position of Prime Minister after government formation.</p><ul><li>"SAND" means the party held the position after the election.</li><li>"FALSK" means the party did not hold the position after the election.</li></ul> |
| Partileder | <p>The individual party's leading figure in the context of the election.</p><p>"Partileder" also applies to a chair who functions as the party leader, e.g. in Socialdemokratiet and Venstre. Parties such as Radikale Venstre have both a national chair and a political leader; it is therefore the political leader who is listed in the table, as the political leader chairs the parliamentary group and thereby has significance for parliamentary election results.</p><p>If multiple party leaders are listed, they will be separated by a comma. For example, under Det moderate Venstre in 1901 it reads "Klaus Berntsen, Niels Neergaard".</p> |
| Note | <p>Comments on the election or individual parties.</p><p>The notes have been prepared by danmarkshistorien.dk. The notes are often not exhaustive in explaining the full electoral situation, and readers are therefore encouraged to consult danmarkshistorien.dk's articles on the parliamentary elections if they have any questions.</p> |
 
## Origin and Attribution
Data and documentation were originally compiled by the editorial team at danmarkshistorien.dk at Aarhus University. Source data comes from Statistics Denmark, supplemented with historical information from the Danish Parliament's Information Service and university research.
 
Although danmarkshistorien.dk no longer exists in the same form today, this material originates directly from the original project. Articles prepared in connection with the parliamentary election dataset can now be found at Lex.dk [https://lex.dk/].
 
## Licence
The dataset is published under the Open Data Commons Open Database License (ODbL):
 
You are free to:
- Copy, share, and use the dataset.
- Modify, transform, and adapt it.
- As long as you credit danmarkshistorien.dk / Aarhus University as the source.
