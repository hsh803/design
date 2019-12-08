---
---
Kmom05 Bild
=========================

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/rapport`.

#### Urval

Jag har valt modebranschen för att analyseringen eftersom de använder många bilder och färger när de bygger en webbplats. Därmed tyckte jag det skulle vara intressant att se hur de tre olika webbplatserna har jobbat med många bilder i webbplatserna och hur smidigt och snabbt de aktiverar på nätet.


#### Metod

Jag har använt Google Pagespeed och development tools som vertyg för att utföra uppgiften.

#### Resultat

Webbplats 1. Monki

[Mitt excelark](https://docs.google.com/spreadsheets/d/1FSi4eiJ0J0LnicvbSRCvPn98xbbo6dNwTtii6nbKO7s/edit#gid=493389505)

[FIGURE src=image/monki.png?w=300]

<table>
<tr>
<th></th>
<th>Sidan 1</th>
<th>Sidan 2</th>
<th>Sidan 3</th>
</tr>

<tr>
<td>Desktop</td>
<td>57</td>
<td>66</td>
<td>65</td>
</tr>

<tr>
<td>Mobile</td>
<td>18</td>
<td>15</td>
<td>14</td>
</tr>
</table>

Enligt siffror från både Google Pagespeed och Devtools är betyg bland tre olika sidor ganska ojämnt jämfört med.
De siffrorna mellan Desktop och Mobile i varje sida diffar inte så mycket men de tre sidorna avviker från varandra i siffrorna.

Webbplatsen kan rensas eller lättas genom att ta bort bilder som inte används och syns i själva sidan eftersom de använda och gömda bilderna som hämtas i sidorna dras ner laddningstid, speciellt i mobile enhet. Javascript och CSS kodning kan även omstruktureras efter vikt för att ladda sidorna fortare.


Webbplats 2. Weekday

[Mitt excelark](https://docs.google.com/spreadsheets/d/1FSi4eiJ0J0LnicvbSRCvPn98xbbo6dNwTtii6nbKO7s/edit#gid=1589358778)

[FIGURE src=image/weekday.png?w=300]


<table>
<tr>
<th></th>
<th>Sidan 1</th>
<th>Sidan 2</th>
<th>Sidan 3</th>
</tr>

<tr>
<td>Desktop</td>
<td>79</td>
<td>79</td>
<td>74</td>
</tr>

<tr>
<td>Mobile</td>
<td>20</td>
<td>20</td>
<td>17</td>
</tr>
</table>

Betyg från Google Pagespeed är högre både i Desktop och Mobile samt jämnare bland sidorna än Monkis.
För att ladda snabbare i den första sidan, dvs. index-sidan i webbplatsen kan video materialet ändras till MPEG4 eller WebM i format istället för att använda GIF.

Javascript och CSS kodning kan även omstruktureras efter vikt för att ladda sidorna fortare.


Webbplats 3. Acne Studio

[Mitt excelark](https://docs.google.com/spreadsheets/d/1FSi4eiJ0J0LnicvbSRCvPn98xbbo6dNwTtii6nbKO7s/edit#gid=92129421)

[FIGURE src=image/acne.png?w=300]

<table>
<tr>
<th></th>
<th>Sidan 1</th>
<th>Sidan 2</th>
<th>Sidan 3</th>
</tr>

<tr>
<td>Desktop</td>
<td>91</td>
<td>91</td>
<td>92</td>
</tr>

<tr>
<td>Mobile</td>
<td>52</td>
<td>41</td>
<td>44</td>
</tr>
</table>


Acne Studio webbplats ha de högsta betygen i både Desktop och Mobile bland de tre utvalda webbplatser. De siffrorna från Devtools är jämna bland sidorna och avviker inte så stort mellan Desktop och Mobile.

För att förbättra laddningstid kan webbplatsen justera bilder i lämplig storlek kan rensa CSS kodning som inte används i sidorna.  


#### Analys

Enligt analysen verkar det som om att bilder som används i webbplatserna
hade kunnat hanteras på olika sätt för att förbättra laddningstid.
Till exempel genom att ändra format av bilder och justera storlek.

Bland de tre webbplatserna fungerar Acne Studio webbplatsen det bästa i jämförelse baserat på betyg från Google Pagespeed och siffrorna från Devtools. Den har den snabbast laddningstid i alla tre sidor och har även jämt siffror i olika sektor bland sidorna.

I analysen hade jag under 2 sekunder och över 4 sekunder som skulle räknas som en snabb respektive långsam laddningstid. Förutom Acne Studio tog Monki och Weekday webbplatser över 3 och 4 sekunder för att ladda alla tre respektive sidor. Och det verkar som om att det beror på vilka typer av bilder används i webbplatserna. Monki och Weekday har nämligen rörande bilder och video i vissa sidor som dröjer laddningstid medan Acne Studio har stilla bilder i sidorna.
