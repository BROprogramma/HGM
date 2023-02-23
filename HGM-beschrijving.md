Ondergrondmodel Hydrogeologisch Model (REGIS)
=============================================

Beschrijving
------------

REGIS II is een registratieobject in het domein *modellen.* Het gaat in dit
domein om schattingen of voorspellingen van de opbouw en eigenschappen van de
bodem of ondergrond in twee of drie dimensies.. Deze schematische weergaven
geven een schatting of voorspelling van de opbouw en eigenschappen van de bodem
of ondergrond. Modellen zijn sterk afhankelijk van de hoeveelheid en kwaliteit
van de beschikbare ondergrondgegevens zoals boormonsterbeschrijvingen. De
kwaliteit van de modellen zal daarom toenemen naarmate er meer
ondergrondgegevens in de BRO beschikbaar komen.

REGIS II is een driedimensionaal hydrogeologisch model van de laagopbouw en
hydraulische eigenschappen van de matig diepe ondergrond van Nederland tot een
gemiddelde diepte van ongeveer 500 meter onder NAP, met een maximum diepte van
1200 m onder NAP. REGIS II is gebaseerd op de interpretaties van de
boormonsterbeschrijvingen en het lagenmodel van DGM. In REGIS II zijn de
lithostratigrafische eenheden van DGM verder onderverdeeld in hydrogeologische
eenheden.

De termen hydrogeologische eenheid en lithostratigrafische eenheid worden
hieronder toegelicht:

-   **Lithostratigrafie** betekent het rangschikken van gesteentelagen in
    eenheden zoals formaties en laagpakketten op basis van lithologische
    kenmerken (waaruit bestaat het materiaal?), verbreiding (waar komt de
    eenheid voor?) en positie (wat is de ligging ten opzichte van andere
    eenheden?). Lithostratigrafische eenheden worden formeel gedefinieerd in de
    Stratigrafische Nomenclator van de Ondiepe Ondergrond van Nederland.

-   Een **hydrogeologische** eenheid is gedefinieerd als een gesteentelichaam
    dat op grond van petrografie (gesteentesamenstelling en -eigenschappen),
    textuur of structuur binnen vastgestelde bandbreedten uniforme
    hydrogeologische eigenschappen vertoont en door laaggrenzen, faciesgrenzen,
    erosieranden of breuken wordt begrensd. Binnen REGIS II worden
    hydrogeologische eenheden onderscheiden op grond van lithostratigrafische
    eenheid en lithologische klasse.

Een hydrogeologische eenheid maakt onderdeel uit van een lithostratigrafische
eenheid of valt daar mee samen. Een hydrogeologische eenheid kan derhalve niet
uit meerdere lithostratigrafische eenheden zijn opgebouwd. Door het hanteren van
dit criterium wordt de consistentie tussen het geologische model DGM en het
hydrogeologische model REGIS II gewaarborgd.

REGIS II bestaat uit de volgende in de BRO opgenomen producten die ontstaan uit
een gestandaardiseerd werkproces:

-   De interpretaties van de geselecteerde boormonsterbeschrijvingen in
    **hydrogeologische eenheden**. Elke boormonsterbeschrijving is binnen het
    voor REGIS II relevante dieptetraject onderverdeeld in dieptetrajecten
    behorende bij een hydrogeologische eenheid.

-   De schattingen van de **doorlatendheid** van de hydrogeologische eenheden op
    de boorpunten voor de hydrogeologische eenheden.

-   **Breuken**. Per breuksegment is aangegeven in welke basis van kleiige,
    venige, bruinkool en complexe hydrogeologische eenheid dit breuksegment nog
    invloed heeft.

-   Een **lagenmodel** waarbij de ondergrond is weergegeven als een stapeling
    van hydrogeologische eenheden die begrensd zijn door een top- en een
    basisvlak. Beide vlakken zijn weergegeven als een **raster** met cellen van
    100 x 100 meter, waarbij elke **rastercel** de hoogteligging van top en
    basis in meter ten opzichte van NAP geeft en daarvan afgeleid de dikte in
    meters. Naast rasters die de geometrie beschrijven omvat het lagenmodel ook
    rasters van hydraulische eigenschappen van de hydrogeologische eenheden,
    zoals de horizontale en verticale doorlatendheid, de transmissiviteit en de
    hydraulische weerstand. Welke rasters beschikbaar zijn verschilt per
    hydrogeologische eenheid. Voor de doorlatendheden zijn ook rasters
    beschikbaar die de modelonzekerheid representeren.

Versiebeheer
------------

Op REGIS II is versiebeheer van toepassing. De in de BRO uitgeleverde versie van
REGIS II bevat altijd het meest actuele model.

De beheerder van een model maakt zijn waardenlijsten (codelijsten en/of
referentielijsten) bekend op een algemeen bekend formaat (PDF en als
downloadable bestand) en maakt deze toegankelijk via
www.basisregistratieondergrond.nl. De waardenlijsten worden 
meegeleverd bij de modellevering.

Als er wijzigingen zijn in een waardelijst, wordt er uiterlijk twee maanden vóór
inwerkingtreding een notificatie op die website gezet, zodat gebruikers nog tijd
hebben om hun eigen omgeving op de wijzigingen aan te passen.

Modelonzekerheden
-----------------

### Onzekerheid

De belangrijkste gegevensbron voor REGIS II zijn boormonsterbeschrijvingen. Elk
van deze boormonsterbeschrijvingen geeft vaak gedetailleerde informatie over de
opbouw van de ondergrond op één specifieke locatie. Voor het overgrote deel van
de gridcellen geldt echter dat ze niet doorboord zijn. Dit betekent dat we een
schatting moeten doen op basis van de in de omgeving van de gridcel aanwezige
boormonsterbeschrijvingen. Hoe goed het model hiertoe in staat is, is onder
andere afhankelijk van:

-   de hydrogeologische complexiteit (een homogeen samengestelde eenheid is
    beter te classificeren dan een heterogeen samengestelde eenheid);

-   de hoeveelheid en de kwaliteit van de boormonsterbeschrijvingen in de
    omgeving van de gridcel;

-   de aan het model opgelegde randvoorwaarden zoals verbreidingsgrenzen van
    hydrogeologische eenheden;

-   het gebruikte algoritme met de bijbehorende parameters zoals de gehanteerde
    ruimtelijke correlatiefunctie.

Alle maatstaven van onzekerheid in REGIS II zijn gebaseerd op de in het model
gebruikte (stochastische) interpolatietechnieken. Het is belangrijk om te
beseffen dat deze technieken niet expliciet rekening houden met de
onzekerheidsmarges in de gebruikte brongegevens (waaronder de
boormonsterbeschrijvingen). In REGIS II spreken we daarom van *modelonzekerheid*
in plaats van *onzekerheid*.

### Standaarddeviaties van de geometrie gekarteerde hydrogeologische eenheden

Standaarddeviaties van de geometrie gekarteerde hydrogeologische eenheden De geometrie van de gekarteerde hydrogeologische eenheden wordt berekend middels een zgn. kriging interpolatie. Aangezien bij het modelleren niet alleen informatie uit boringen, maar ook aanvullende hydrogeologische kennis wordt toegevoegd, levert de kriging variantie geen bruikbare maat voor onzekerheid. Daarom wordt voor het bepalen van deze onzekerheid een op cross validatie gebaseerde methode gebruikt. De onzekerheids-rasters geven voor elke rastercel de modelonzekerheid van de geometrie weer, uitgedrukt in een standaarddeviatie (m). Met de standaarddeviatie is het mogelijk om de kans te bepalen dat de diepteligging of dikte van een gekarteerd grensvlak een bepaalde afwijking vertoont van de door het model geschatte, meest waarschijnlijke waarde.
Alleen van gekarteerde hydrogeologische eenheden worden onzekerheden geometrie berekend. Van afgeleide hydrogeologische eenheden worden geen onzekerheden geometrie berekend. In het Totstandkomingsrapport Kleine Release REGIS II onzekerheden geometrie wordt de gebruikte methode nader beschreven.

### Standaarddeviaties van de doorlatendheid in het lagenmodel

Van de meeste hydrogeologische eenheden is van de doorlatendheid een
standaarddeviatieraster berekend. Deze rasters geven voor elke rastercel de
modelonzekerheid van de doorlatendheid weer, uitgedrukt in de standaarddeviatie
(in m/d) van de door het model geschatte, meest waarschijnlijke doorlatendheid.
Met de standaarddeviatie is het mogelijk om de kans te bepalen dat de
doorlatendheid een bepaalde afwijking vertoont van de door het model geschatte,
meest waarschijnlijke waarde. De manier waarop de standaarddeviatie berekend
wordt kan per geologische eenheid verschillen. Welke manier van toepassing is
wordt beschreven in het Totstandkomingsrapport dat met het model in de BRO is
opgenomen.

Doel en gebruik
---------------

REGIS II is een regionaal ondergrondmodel met een gebruiksschaal die past bij
toepassingen op landelijk en provinciaal niveau. Deze gebruiksschaal is
vergelijkbaar met de schaal van 1:100.000. Bij ondergrondvraagstukken op een
grotere schaal (subregionaal) kan REGIS II dienen als raamwerk waarbinnen meer
detail kan worden aangebracht.

Kwaliteitsaspecten
------------------

### Algemeen

De kwaliteit van REGIS II is onder andere afhankelijk van de volgende factoren:
de kwaliteit van het geologische model DGM, de hoeveelheid, diepte, ruimtelijke
verdeling en kwaliteit van de boormonsterbeschrijvingen, de verbreiding van een
geologische eenheid, de breukwerking in deze eenheid en het modelleren van de
eenheden.

Deze en andere kwaliteitsaspecten wordt in de navolgende paragrafen verder
besproken.

### Kwaliteit van het geologische model DGM

Een hydrogeologische eenheid maakt onderdeel uit van een lithostratigrafische
eenheid of valt daar mee samen. Hierdoor bestaat er een zeer nauwe samenhang
tussen het geologische model DGM, dat de opbouw van de ondergrond in geologische
(lithostratigrafische) eenheden beschrijft, en REGIS II. Om de consistentie
tussen geologische en hydrogeologische informatie te kunnen waarborgen, zijn de
lithostratigrafische interpretaties van de boormonsterbeschrijvingen van de
subset van DGM, en de geometrie van de geologische eenheden van dit model een
randvoorwaarde voor REGIS II. Hydrogeologische interpretaties van de
boormonsterbeschrijvingen en ruimtelijke interpretaties van de hydrogeologische
eenheden dienen gebaseerd te zijn op de informatie van DGM. De kwaliteit van DGM
is daardoor mede bepalend voor de kwaliteit van REGIS II.

#### Boormonsterbeschrijvingen

Voor REGIS II wordt een subset van alle beschikbare boormonsterbeschrijvingen
gebruikt. Dit is dezelfde subset als voor DGM gebruikt wordt. Er wordt gestreefd
naar een zo gelijkmatig mogelijke verdeling van boormonsterbeschrijvingen per
geologische eenheid, maar dit kan niet altijd gerealiseerd worden. Er zijn
gebieden met een hogere boordichtheid (in onderzoeksgebieden,
drinkwateronttrekkingsgebieden) en gebieden met een veel lagere boordichtheid
(Waddenzee, IJsselmeer). Daarnaast kan de boordichtheid per eenheid per regio
variëren. Tot slot varieert de kwaliteit van de boorbeschrijvingen binnen deze
subset. De gebruikte boormethode, de daaraan gekoppelde manier van monstername
en de methode waarmee de monsters zijn beschreven beïnvloeden de kwaliteit van
laagbeschrijvingen.

#### Kwaliteitsfiltering

Binnen REGIS II wordt een subset van alle beschikbare boormonsterbeschrijvingen
gebruikt. Deze initiële subset is identiek aan de subset van de corresponderende
versie van DGM. De boormonsterbeschrijvingen kunnen echter soms te weinig
lithologische kenmerken bevatten of uit te grote diepte-intervallen bestaan om
een hydrogeologische eenheid te kunnen interpreteren. Indien ook aanvullende
informatie, bijvoorbeeld in de vorm van een geofysische boorgatmeting, die
ondersteunend kan zijn bij de interpretatie, ontbreekt, kan besloten worden om
dergelijke boormonsterbeschrijvingen niet bij de modellering van de top en/of
basis van de betreffende hydrogeologische eenheid mee te nemen. De selectie
welke boormonsterbeschrijvingen wel/niet worden meegenomen bij de modellering
van een hydrogeologische eenheid wordt handmatig uitgevoerd.

De lithologische informatie van de boormonsterbeschrijvingen wordt ook gebruikt
bij het schatten van de doorlatendheid van een deel van de hydrogeologische
eenheden. De mate van detail en representativiteit van de
boormonsterbeschrijvingen zijn bepalend of de informatie van een
boormonsterbeschrijving wel/niet wordt gebruikt bij het samenstellen van de
rasters van de doorlatendheid. De selectie welke boormonsterbeschrijvingen
wel/niet worden meegenomen bij de modellering van een hydrogeologische eenheid
wordt deels automatisch, deels handmatig uitgevoerd.

#### Momentopname (ouderdom)

Boormonsterbeschrijvingen zijn een momentopname van de beschreven ondergrond. De
opbouw van de ondergrond ter plaatse van de boormonsterbeschrijving kan in de
tijd die verstreken is tussen het maken van de beschrijving en het construeren
van het model veranderd zijn. Denk aan veen in een boormonsterbeschrijving dat
inmiddels is geoxideerd en vergravingen (havens, vaargeulen).

#### Momentopname (database)

Bij het actualiseren van het model wordt op een zeker moment een momentopname
(‘snapshot’) gemaakt van de boormonsterbeschrijvingen en de bijbehorende
boorbeschrijvingen. De interpretaties van de boormonsterbeschrijvingen worden
gebaseerd op deze momentopname. Alle wijzigingen die na de momentopname aan deze
boormonsterbeschrijvingen worden aangebracht, zullen niet zichtbaar in de
momentopname zijn en zullen daarom niet zichtbaar zijn in het betreffende model.

#### Interpretatie in hydrogeologische eenheden

Alle in de subset aanwezige boormonsterbeschrijvingen worden voorzien van een
hydrogeologische indeling. Op automatische wijze wordt een voorzet voor deze
interpretatie gedaan, waarna de uiteindelijke interpretatie handmatig geschiedt.
Bij deze handmatige interpretatie kan additionele informatie worden gebruikt,
zoals geofysische boorgatmetingen, zware mineralen diagrammen, pollenonderzoek
en in de omgeving opgenomen sonderingen.

Na het in hydrogeologische eenheden interpreteren van de
boormonsterbeschrijvingen worden de interpretaties middels een aantal
plausibiliteitscontroles gecontroleerd.

### Verbreidingen

Voor elke kleiige, venige, bruinkool en complexe hydrogeologische eenheid wordt
een verbreiding vastgesteld. Deze verbreiding bakent het gebied af waarbinnen de
eenheid binnen het model gemodelleerd wordt. De verbreiding is de maximale of
potentiële verbreiding van de eenheid binnen het lagenmodel: buiten de
potentiële verbreiding komt de eenheid niet voor, binnen de verbreiding kan de
eenheid voorkomen.

Bij het construeren van verbreidingsgrenzen wordt een kaartschaal van circa
1:100.000 gehanteerd. Kleine voorkomens van de hydrogeologische eenheid die
buiten de resolutie van deze kaartschaal vallen, worden niet in de verbreiding
opgenomen.

### Breuken

Binnen de modellering van REGIS II wordt rekening gehouden met breuken. Per
breuksegment is aangegeven in welke basis van kleiige, venige, bruinkool en
complexe hydrogeologische eenheid dit breuksegment nog invloed heeft. Om
modeltechnische redenen worden in de modellering van de hydrogeologische
eenheden van REGIS II de breuken verondersteld verticaal te zijn.

### Lagenmodel

#### Consistent lagenmodel

Het lagenmodel is consistent, dat wil zeggen dat de top van een eenheid ofwel
samenvalt met de basis van een of meerdere hoger gelegen eenheden, ofwel aan
maaiveld ligt. Omgekeerd valt de basis van een eenheid samen met een of meerdere
toppen van dieper gelegen eenheden, of de basis ligt aan de onderkant van het
model. Een logisch gevolg is dat elk willekeurig punt in de ruimte (binnen de
begrenzingen van het modelgebied) zich altijd tussen de top en basis van één
enkele hydrogeologische eenheid bevindt.

#### Hydraulische parameters van de eenheden

REGIS II verschaft, afhankelijk van de hydrogeologische eenheid, schattingen van
de hydraulische eigenschappen van de hydrogeologische eenheden. De kwaliteit van
deze schattingen hangt samen met de hoeveelheid, diepte en ruimtelijke verdeling
van geschikte boormonsterbeschrijvingen, de kwaliteit van deze
boormonsterbeschrijvingen, de heterogeniteit van de hydrogeologische eenheid, de
hoeveelheid, kwaliteit en ruimtelijke spreiding van bepalingen van deze
hydraulische eigenschappen door middel van proeven en de bestaande kennis van de
hydraulische eigenschappen van de eenheden en de gebruikte methodiek om deze
schattingen te maken.

Geostatistische procedures worden gebruikt om op basis van geïnterpreteerde
boormonsterbeschrijvingen hydraulische parameters van een deel van de
hydrogeologische eenheden te schatten. Daarbij wordt tevens de standaarddeviatie
van de doorlatendheid als maat van modelonzekerheid uitgeleverd.

Indien er onvoldoende geschikte boormonsterbeschrijvingen zijn, is het niet
mogelijk om de ruimtelijke variatie in de hydraulische eigenschappen aan te
geven. In dat geval is een constante waarde gegeven voor het hele
verbreidingsgebied van de eenheid.

#### Verschillen met boormonsterbeschrijvingen

Een boormonsterbeschrijving geeft veelal een gedetailleerd beeld van de
hoogteligging van geologische eenheden op één specifieke locatie. In het
lagenmodel wordt middels geostatistische technieken een schatting gegeven van de
hoogteligging van de geologische eenheden per rastercel. Deze is daarmee
representatief voor een gebied van 100 bij 100 m (10.000 m2). De diepteligging
van de geologische eenheden in een boormonsterbeschrijving kan daarom afwijken
van de voorspelde diepte van geologische eenheden in het lagenmodel op dezelfde
locatie. Ook geldt dat de opeenvolging van hydrogeologische eenheden in een
boormonsterbeschrijving kan afwijken van de gemodelleerde opeenvolging van de
eenheden, dunne eenheden kunnen weggeschaald zijn in het lagenmodel en een
complexe afwisseling van eenheden moet voor de modellering vereenvoudigd worden.

In de modellering van REGIS II worden de kleiige, venige, bruinkool en complexe
hydrogeologische eenheden gemodelleerd, de geometrie van de zandige eenheden
wordt hiervan afgeleid.

De hoogte van het maaiveld op de locatie van het boormonsterbeschrijving kan
eveneens afwijken van de maaiveldhoogte van het model. Dit kan verschillende
oorzaken hebben zoals fouten in de opname van de maaiveldhoogte of een
daadwerkelijke verandering in maaiveldhoogte door bijvoorbeeld afgraving of
ophoging die in de tijd tussen het maken van het boormonsterbeschrijving en het
construeren van het model heeft plaatsgevonden. Verder geldt dat de
maaiveldhoogte in het model representatief is voor een gebied van 100 bij 100 m
en de hoogte van een boormonsterbeschrijving geldt voor één specifieke
puntlocatie.

Metadata
--------

### Resolutie

Rastercellen in het lagenmodel hebben afmetingen van 100 bij 100 m.

### Gebruiksschaal

In het ondiepe bereik van REGIS II is de gebruiksschaal circa 1:100.000. Door de
afnemende datadichtheid met de diepte geldt op groterere dieptes een kleinere
gebruiksschaal. Door verschillen in datadichtheid zijn er daarnaast regionale
verschillen in de gebruiksschaal van het model. Zie ook de toelichting in 5.4.

### Gebiedsaanduiding

De omgrenzende rechthoek, uitgedrukt in minimale en maximale coördinaten van het
model, is vastgesteld in het Rijksdriehoekstelsel (RD). De waarden zijn in
onderstaande tabel weergegeven, met daarbij de omgerekende waarden in WGS84.

| **Coördinaat**         | **Rijksdriehoekstelsel (m)** | **WGS84 (graden)** | **WGS84 (decimale graden)** |
|------------------------|------------------------------|--------------------|-----------------------------|
| Minimale X- coördinaat | 0                            | E 003 11 40.7450   | 3.19465                     |
| Minimale Y- coördinaat | 300.000                      | N 50 40 09.1109    | 50.66920                    |
| Maximale X- coördinaat | 280.000                      | E 007 16 30.7336   | 7.27520                     |
| Maximale Y-coördinaat  | 625.000                      | N 53 35 46.3216    | 53.59620                    |

### Horizontale begrenzing

De horizontale begrenzing van het model is vastgelegd in een polygoon.

### Verticale begrenzing

Voor het lagenmodel geldt dat de verticale begrenzing aan de bovenkant bepaald
wordt door de top van de ondiepst gelegen geologische eenheid van het DGM dat
aan REGIS II ten grondslag ligt. De verticale begrenzing aan de onderkant wordt
bepaald door de basis van de diepst gelegen geologische eenheid van dit DGM.

### Horizontaal referentiesysteem

Alle coördinaten in REGIS II zijn gegeven in meter in het Rijksdriehoekstelsel
(RD).

Voor de geïnterpreteerde boormonsterbeschrijvingen geven de coördinaten de
ligging van de boorlocatie aan maaiveld aan. Indien een boormonsterbeschrijving
zich binnen een straal van 150 meter van een breukvlak bevindt, wordt deze
locatie 150 meter loodrecht van het breukvlak verschoven. Hiermee wordt
voorkomen dat boormonsterbeschrijvingen gelegen in rastercellen die door
breukvlakken worden doorsneden, een foutieve invloed op het modelresultaat
kunnen hebben.

Voor het lagenmodel geldt de conventie dat de ligging van een rastercel wordt
beschreven door de coördinaten van de linkeronderhoek (“lower left corner”).

### Verticaal referentiesysteem

Alle hoogten in het lagenmodel van REGIS II zijn gegeven in meter ten opzichte
van NAP.
