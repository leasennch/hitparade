# Senkrechtstarter in der Schweizer Hitparade
Wie aus dem Nichts schoss Ava Max mit ihrem Hit «Sweet But Psycho» auf Platz 1 der Schweizer Single-Hitparade. Gab es das früher auch schon? Kommt das heutzutage häufiger vor als früher? Wie haben sich die Karrieren danach entwickelt?

### Der publizierte Artikel
[https://www.watson.ch/!270726641](https://www.watson.ch/!270726641)

### Ausgangsthese
Heute gibt es häufiger musikalische Senkrechtstarter, die nach sehr kurzer Zeit einen Nummer-1-Hit landen (wie z.B. kürzlich Ava Max)

### Idee
Wie aus dem Nichts schoss Ava Max mit ihrem Hit «Sweet But Psycho» an die Spitze sämtlicher internationalen Charts. Ich frage mich, ob das ein «neumodisches Phänomen» ist, oder ob es solche Situationen auch vorher schon gab. 

Bereits im Oktober 18 habe ich Code geschrieben, der die Daten von hitparade.ch ausliest. Ich wollte damals eine Schweizerkarte mit den erfolgreichsten Musikern nach Kanton zeichnen, habe die Idee jedoch verworfen. Auf die Entwürfe des Scrapers kann ich nun jedoch aufbauen und ihn so erweitern, dass ich mir eine gute Datengrundlage schaffen kann. 

1) Gibt es Künstler, die ebenfalls nach 4 oder weniger Wochen nach ihrem ersten Erscheinen in der Schweizer Charts einen Nummer-1-Hit landeten?
2) Falls ja: Wann war das? Häufen sich diese Senkrechtstarter in den letzten Jahren?
3) Wie ist die Karriere von Senkrechtstartern danach verlaufen? Evt. kann man eine ähnliche Grafik realisieren, wie wir sie [hier](https://public.tableau.com/profile/bo.mccready8742#!/vizhome/MostYearsChartingontheBillboardHot100/MostYearsCharting) haben, man müsste jedoch den Weg zur ersten Nummer 1 grafisch hervorheben.

4) Zusatzoption 1: Eine Slideshow mit dem Karriereverlauf der erfolgreichsten Künstler. Beziehungsweise noch cooler: Eine interaktive Grafik, wo man den Karriereverlauf seines Lieblingskünstlers abrufen kann.
5) Zusatzoption 2: Falls man mit den Daten etwas anfangen kann: Spotify API anzapfen und Infos wie z.B. Länge einzelner Stücke abrufen 

### Einschätzung von Aufwand / Ertrag
Den Scraper zu bauen und die Daten sinnvoll aufzubereiten, sollte gut möglich sein. Die Webseite ist gut strukturiert. Arbeit gibt wohl vor allem die Analyse in Pandas. Auch ins Visualisieren sollte genug Zeit investiert werden, damit man den Inhalt schnell erfassen kann.
![Spider](https://github.com/leasennch/hitparade/blob/master/diverses/Spider.jpg "Spider")


### Knackpunkte
Schön wäre es gewesen, wenn der Datensatz Verbindungen unter den Künstlern beinhalten würde, also zum Beispiel, dass «Remady & Manu-L» als zwei Einzelne Künstler gewertet werden, oder dass bei den Erfolgen von «Ritschi» auch die Erfolge seiner Band «Plüsch» mitgewertet würden. Das sprengt jedoch zeitlich den Rahmen, weil nicht nur die Datenbeschaffung aufwändiger wäre, sondern auch die logische Darstellungsform in den Grafiken.

Eine interaktive Grafik wäre ein schönes Nice-To-Have. Ich habe mir D3.js bereits einmal für ein Projekt etwas angeschaut, es ist jedoch in meinen Augen ein ziemlich komplexes Tool und würde mich relativ viel Zeit kosten, damit eine interaktive Grafik zu bauen. 

### Briefingpersonen
Ich habe mit den Musikchefs von Radio 24 und Radio Argovia gesprochen. 

__Chris Jäckli, Radio 24:__
1) Früher waren Bands mit mehreren Songs in den Charts vertreten, bis sie richtig erfolgreich waren. Heute stürmen Leute wie Ava Max innert Wochen die Charts. Teilst du diesen Eindruck auch oder hast du eine andere Ansicht?
*«Teilweise. Auch früher gab es Bands und Künstler, welche vermeintlich aus dem Nichts mit einem Hit um die Ecke kamen. Nehmen wir die Band Fool’s Garden mit ihrem Song ‘Lemon Tree’ als Beispiel. Nach diesem Hit waren sie nie mehr in der Schweizer Hitparade. Was man aber gerne vergisst ist die Tatsache, dass die Künstler schon vor ihrem Hit Musik gemacht haben. Kaum jemand hat zum ersten Mal ein Instrument in die Hand genommen, als er seinen ersten Hit gelandet hat. Heute ist es aber sicher schnelllebiger geworden und die Künstler haben durch neue Technologien mehr Chancen in die Charts zu kommen.»*
 
2) Kannst du dir das Phänomen irgendwie erklären?
*«Was heute sicher ein Vorteil gegenüber früher ist, sind die Technologien, welche den Musikern heute zur Verfügung stehen. Dank Plattformen wie Youtube oder Soundcloud kann ein Künstler seine Musik veröffentlichen, ohne Plattenfirma und umständliche Vertriebswege. So kann theoretisch eine Fangemeinde aufgebaut werden, ohne jemals den Proberaum oder das Haus verlassen zu müssen. Früher war es unerlässlich raus zu gehen, live zu spielen und sich zu zeigen. Heute braucht man auch viel weniger physische CD-Verkäufe, um in die Hitparade zu kommen. Dass Spotify Streams ebenfalls in die Hitparade eingerechnet werden hilft bei diesem Phänomen zusätzlich.»*
 
__Peter Stutz, Radio Argovia:__
1)	Welche Faktoren spielen eine Rolle, damit man einen «Senkrechtstart» in der Schweizer Hitparade hinlegen kann? Am Beispiel Ava Max, aber auch bei anderen Künstlern?

In erster Linie braucht es einen guten Song mit einer Melodie, die, wie im Fall von «Sweet But Psycho», süchtig macht und das breite Publikum anspricht. Ava Max hat ausserdem das «gewissen Etwas», mit dem sie aus der Masse von Pop-Newcomern heraussticht: Eine starke Stimme, einen individualistischen Sinn für Fashion und eine gewisse Coolness. Ausserdem ist sie am Songwriting beteiligt und kann so ihren eigene Stil einbringen.
 
2)	Wie haben sich diese Faktoren verändert im Vergleich zu vor 50 Jahren? (z.B. Live-Auftritte oder Social Media Präsenz sind heute wichtiger geworden)
 
Für junge Künstler wie etwa Ava Max ist es ganz normal auf sozialen Netzwerken wie Facebook oder Instagram zu sein, da sie damit aufgewachsen sind. Diese Plattformen helfen enorm, den Bekanntheitsgrad zu steigern. Wenn man sich auf Social Media authentisch bewegt und auch mal das «ungeschminkte» Popstarleben zeigt, kann das neuen Musiker durchaus helfen, schnell bekannt zu werden und den Durchbruch zu schaffen. Früher hatte man diese Hilfsmittel nicht – da musste einzig und alleine der Song was taugen.
 
3)	Hast du das Gefühl, dass es heute tendenziell einfacher, schwieriger oder gleich schwer ist, schnell weit oben in die Charts einzusteigen?
 
*Mal abgesehen davon, dass es nur noch geringe Verkäufe für einen Charterfolg braucht, denke ich, dass es heute nicht einfacher geworden ist, schnell weit nach oben zu kommen, da man durch die zahlreichen Streamingdienste jederzeit Zugriff auf Millionen von Songs hat. Wenn man es da nicht schafft aus der Masse herauszustechen, hat man schon verloren.
In den oberen Regionen der aktuellen Charts, wo sich seit Monaten praktisch nur Deutschrapper abwechseln, ist Ava Max praktisch die Einzige, die da mithalten kann und das ist schon sehr bemerkenswert.*
 
4)	Gibt es dabei entscheidende Unterschiede für Schweizer Künstler im Vergleich zu internationalen Stars?
 
*Wenn man eine gute Community auf Social Media aufbauen kann, ist die Chance gross, auch als Schweizer Act mit Streamings und Verkäufe wenigstens eine Woche vorne in den Charts mitzumischen und somit eine gewisse Aufmerksamkeit zu erreichen. Sobald die Community aber gut gefüttert ist und mit den Songs kaum weitere Menschen erreicht werden können, sieht’s für eine langlebige Chartkarriere eher düster aus. Kommt noch dazu, dass Musiker von hier, die in Mundart produzieren, auf dem internationalen Markt kaum Chancen haben, sich durchzusetzen. Zwar versuchen sich viele Künstler und Bands auch auf Englisch. Die meistens scheitern aber daran, dass sie sich in dieser Sprache weniger gut und treffend ausdrücken können und so ihre Performance schnell als «unprofessionell» abgestempelt wird.*

### Datensatz / Programmiercode
- [Hitparadenscraper](https://github.com/leasennch/hitparade/blob/master/Hitparade_Scraper.ipynb)
- [Ergebnisse als CSV und Outputs matplotlib](https://github.com/leasennch/hitparade/tree/master/python_outputs)
- [Ergebnisse als Grafiken in Illustrator aufbereitet](https://github.com/leasennch/hitparade/tree/master/finished_graphics)
- [D3.js-Code für die interaktive Grafik](https://github.com/leasennch/hitparade/tree/master/interactive)

### Arbeitsprotokoll

| Datum | Aufwand | Tätigkeit |
| -------- | ---- | ------------- |
| 23.10.18 | 8 h | Scraper für Hitparade schreiben |
| 18.02.19 | 4 h | Idee weiterentwickeln, These prüfen mit Briefingperson |
| 19.02.19 | 8 h | Scraper mit Selenium weiterentwickeln, erste Auswertungen machen |
| 20.02.19 | 4 h | Erste Visualisierungen machen, Struktur der Geschichte bestimmen, Story im Team besprechen  |
| 22.02.19 | 8 h | Interaktive Grafik mit D3.js bauen, Spotify-API testen |
| 23.02.19 | 3 h | Erkenntnisse visualisieren |
| 25.02.19 | 4 h | Interaktive Grafik weiterentwickeln, Projektdokumentation anlegen |
| 26.02.19 | 8 h | Interviews mit Briefingperson in Text einbauen, Design interaktive Grafik anpassen für Mobile |
| 27.02.19 | 4 h | Timeline-Grafik erstellen, Text formulieren, Dokumentation  |
| 28.02.19 | 2 h | Geschichte veröffentlichen, Social Media, Kommentarspalte verwalten |

