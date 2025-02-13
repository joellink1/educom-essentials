# Rapportage gegevensbestanden

## Markdown (.md)
### Full-Markdown.md
Dit bestand is een referentiebestand dat geschreven is in Markdown syntax. Het legt deze syntax uit aan de hand van voorbeelden door het combineren van plain text (tussen aanhalingstekens) en geïnterpreteerde tekst.

### markdown-sample.md
Dit bestand is bijna hetzelfde als het eerste bestand, in dat het ook het effect van Markdown syntax laat zien, echter zonder de stukken tekst in quotes. alle tekst in het bestand is 
door de ogen van Markdown vertaald. enkele extra voorbeelden zoals blokken code en wiskundige formules vergeleken emt Full-Markdown.md.

### README.md
Dit bestand is een README voor een user-created addon voor een online computerspel. Het bevat een aantal links naar de schrijver van de addon (donaties, social media, etc) en informatie 
over de features die de addon bied. Daarnaast geeft het de gebruikerinformatie over het contacteren van de schrijver voor specifieke redenen zoals bugreports en feature requests.

## JavaScript Object Notation (.json)
### JSON EXAMPLE.json
Het bestand bevat een voorbeeld van de opbouw van een lijst waarin verschillende markup talen met elkaar vergeleken kunnen wroden. De lijst bevat slechts één entry, voor "standard generalised markup language", 
en bevat infovelden voor onder andere een ID, afkorting, ISO nummmer en een korte beschrijving.

### HotkeysConfig.json
Dit bestand is een configuratiefile voor sneltoetsen van het programma ShareX. Boven aan het bestand wordt een lijst met hotkeys geïnitialiseerd. Iedere mogelijke hotkey wordt d.m.v. een boolean aan of uit gezet,
en vervolgens wordt geconfigureerd wat de hotkey doet (aangezien de hotkeys allemaal niet toegwezen zijn, is dit blok voor iedere optie hetzelfde).

## eXtensible Markup Language (.xml)
### XML example.xml
Dit bestand is een exacte kopie van JSON EXAMPLE.json, behalve dat de informatie in dit bestand opgeslagen is in XML syntax. Een interessant verschil is dat de 'see also' waarden hier niet samen in een lijst 
zijn opgeslagen zoals bij de JSON versie, maar alas twee aparte entries met dezelfde key.

### repositories.xml
Deze xml file is afkomstig uit de program files van een digitale listbuildingtool voor miniatuur wargames. Het bevat informatie over de systemen waarvan de regels toegevoegd zijn aan de tool. Zoals in het bestand 
te zien is wordt informatie zoals de naam van het systeem, een tag of gecodeerde naam, de laatst bijgewerkte versie, wanneer deze bijgewerkt, en wat er hierbij is veranderd opgenomen in de repository, 
zodat de tool deze informatie kan weergeven aan de gebruiker.

## Character-Separated Value / Comma-Separated Value (.csv)
### Energieverbruik_particuliere_woningen.csv
Dit bestand, afkomstig van het CBS, gaat over de het gemiddeld energieverbruik door verschillende soorten woningen in verschillende regio's over een aantal jaar. Er wordt duidelijk onderscheid gemaakt tussen 
woningsoorten (bv. appartement tegenover 2-onder-1-kap), regio's (bv. Limburg tegenover Amsterdam), en de verschillende jaren (2020 t/m 2023). Van ieder van deze permutaties wordt het gasgebruik in m<sup>3</sup>, 
de elektriciteitslevering (bruto en netto) en het percentage huizen aan stadsverwarming  genoteerd. Direct valt op dat sommige regio's geen gebruik maken van stadsverwarming, of dat pas recent doen. Het ziet 
uit alsof dit bestand origineel niet in CSV geschreven is, of in ieder geval later in bijvoorbeeld Excel is aangepast. Een belangrijke hint hiervoor is de kopregel, die over meerdere regels verdeeld is om deze 
leesbaarder te maken in bijvoorbeeld Excel, en de extra titel bovenaan het bestand die waarschijnlijk niet zou bestaan als het bestand origineel in CSV formaat zou zijn geweest.

### oscar_age_male.csv
In dit bestand wordt van ieder jaar tussen 1928 en 2016 de winnaar van de Academy Award voor beste acteur genoemd. er wordt gebruik gemaakt van een ID, het jaar van de win (welke ook als ID zou kunnen werken in deze file), 
en enkele datapunten zoals de naam van de acteur, de leeftijd, en de film. In tegenstelling tot de file van het CBS lijkt deze volledig gegenereerd te zijn door een script als CSV; de kopregel is in het format zoals 
deze zou worden gegenereerd door een script, en het gebruik van een ID kolom hint ook naar automatisering door middel van een script.

## Scalable Vector Graphics (.svg)
### api-interface-svgrepo-com.svg
Uit dit SVG bestand is in eerste instantie met het blote oog niet veel af te leiden. Er staat duidelijk in dat XML de basis vormt en een encoding en versie worden genoemd in de header. Tussen de header 
en body staat een stuk gecommenteerde tekst waarin de uploadlocatie genoemd wordt. In de daadwerkelijke content staan een aantal dingen die te lezen zijn, zoals de standaard hoogte en breedte van de vector, 
de bron waar deze te vinden is en een achtergrondkleur. Verder bevat de code enkel instructies om de vector te tekenen.

### stock_svgrepo-com.svg
In dit SVG bestand zijn dezelfde datapunten te vinden als in api-interdace-svgrepo-com.svg. beide SVG bestanden komen van dezelfde bron, dus dit is logisch.

### W3SVG.svg
Dit SVG bestand bevat enkel een body, waarin ook weer een hoogte en breedte genoemd worden, alsook de bron. De tekeninstructies zijn bij deze SVG echter beter te interpreteren aangezien de vector simpeler is. Het gaat
om een circle met een radius van 45 units, die op de coördinaten 50,50 van het tekenveld ontstaat. De rand om de cirkel is 3 units dik en groen, en de cirkel zelf krijgt een rode kleur.

## YAML Ain't Markup Language (.yml)
### YAML W3.yml
Dit document is ook een referentiedocument, dat door middel van gebruik maakt van de YAML syntax om deze syntax uit te leggen. Net als JSON is de opmaak van het document in de vorm van Key/Value, maar zonder de
indentaties en haakjes waardoor dit document simpeler voor een mens te lezen is. Nesting kan worden toegepast door simpelweg een key op te laten volgen door meer Key/Value paren, waarin deze paren samen de Value 
lijken op te maken van de eerste Key.

### YAML example.yml
Het document lijkt een template voor netwerkconfiguratie te zijn, waar veel values nog moeten worden ingevuld. Er is veel gebruik gemaakt van nesting.

## Tom's Obvious, Minimal Language (.toml)
### TOML example.toml
Bij dit document is ook weer sprake van een referentiedocument dat de syntax gebruikt om deze uit te leggen. Ook hier wordt gebruik gemaakt van Key/Value paits, net als bij YAML en JSON, maar nog de haakjes van JSON
nog de indentering van YAML zijn hier aanwezig, en worden ook niet genoemd in het document als een deel van de opmaak.

### test.toml
Dit document is een voorbeeld voor de mogelijke indeling van een TOML document. er wordt gebruik gemaakt van key/value pairs zoals in 'TOML example.toml', en hier wordt expliciet genoemd dat indentering niet relevant is 
bij TOML. De 'hoofdstuktitels' binnen het document worden gemaakt door middel van vierkante haken, welke eigenlijk een lijst zouden maken. Dit lijkt een opmaaktechniek om het bestand leesbarder te maken. 
