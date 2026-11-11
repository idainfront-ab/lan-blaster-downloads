# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev15.7

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.7/LAN_Blaster_0.1.0-dev15.7_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev15.7) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.7/LAN_Blaster_0.1.0-dev15.7_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev15.7

- **E2-speaker:** de sex godkända utropen First kill, Multi kill, Mega kill, Ultra kill, Shame on you och Last laugh följer med offline. Multi/Mega/Ultra gäller 3/5/7 motståndarkills utan egen död, utan tidsgräns. Serien börjar om vid död och ny runda. Separat volym, mute och röstprov finns under Audio.
- **Napalm Bomb:** kort första kors och tre sekunders kvarvarande eld. **Cluster Bomb:** upp till fyra synliga barnbomber med landningsvarning och 1,25 sekunders stubin efter landningen. Båda ger en laddning per fynd, max två, och väljs med Q. Tidigare bomber och BUILD finns kvar i det utökade inventoryt.
- **Confusion:** en negativ svamp inverterar rörelseriktningarna i fem sekunder. Bomb och Q fungerar normalt. Effekten syns på figuren och försvinner vid död. Varje ny typ har egen Off/Low/Normal/High-inställning under Rules → Items, för både Practice och LAN.
- **Dödseffekt:** pixelpoff övergår i en tecknad blod-/sotfläck som tonar bort. Den påverkar inte kollisioner. Den gamla X-markeringen finns som lokalt alternativ under Audio / Menu.
- **Snow och Volcano** är nya valbara banfamiljer. Garden, Cavern, Docks, Crossroads, Rings, Factory, Portals och Switchyard använder de förberedda spritesen och sina granskade miljöobjekt. Classic får enbart varsamt uppdaterad grafik med samma layout. Desert Ruins finns kvar. Totalt tolv banfamiljer.
- **Närmare konceptbilderna:** större och lugnare golvmönster, kraftigare tematiska murkanter, varierade pelare, lyktor och miljödetaljer. Snow har en större igloo med 5 × 5 fasta rutor och fri gång runtom. Docks får kajstensytor, Rings en stenlagd ring och Switchyard nya svängda rälsdekorationer. Menyns banbilder använder samma rendering som spelet.
- Stora objekt har gemensamma blockerade rutor för värd, klient, bomber och botar. CTF placerar hela speglade objekt med hänsyn till baser och attackvägar. Golvdekorationer är platta. Snö, lava och vatten inför inga nya specialregler. Transportband, portalpar och grindar behåller sin tidigare funktion.
- Banomröstningen rymmer tolv val. Musikvalen omfattar även Snow och Volcano med befintliga spelspår. Alla 19 figurer, rund-/seriestatistik, butik, CTF Fortress och LAN Lab finns kvar.

## Prova gärna
Välj Snow eller Volcano och kör först Practice med åtta spelare, sedan fyra och sexton. Kontrollera hörn och gångar kring stora objekt. Prova Napalm, Cluster och Confusion med Rules-inställningarna på respektive av, och Q-växling inklusive BUILD i CTF. Lyssna på E2 tillsammans med musik/effekter och justera Audio-volymen efter smak.

På LAN ska alla använda Dev15.7. Kontrollera att föremål, eld, barnbomber, dödsfläckar och utrop stämmer mellan datorerna. De automatiska nätverkstesterna använder flera riktiga spelprocesser på samma dator; fysisk LAN-räckvidd, brandväggar, handkontrollkänsla och högtalarmix behöver fortfarande bedömas i provspel.

## Grafikens anpassning
Konceptens lösa hinderfördelning ersätts av spelets vanliga generator. Stora objekts genomskinliga hörn ingår i deras rektangulära blockerade footprint; själva bilden och skuggan visar objektet utan en färgad rektangel under. I CTF kan objekt flyttas och förekomma som speglade par för att hålla baser och vägar fria. Minsta Rings saknar centralsockel. I minsta CTF utelämnas Docks extra vatteninlopp och Factorys trycktank för att hålla vägarna fria. Crossroads får inga breddade huvudpassager. Classic får inga stora objekt. Portalernas stora golvhalo är dekor; den aktiva rutan i mitten och portalparen fungerar som tidigare. Switchyards nya räls är golvdekor, inte en ny tågmekanik.

Det portabla Windows-paketet använder samma oförändrade Godot-programfil och separata genvägsikon som tidigare. Ingen betald signering eller ny tjänst krävs. Äldre numrerade releaser finns kvar på samma nedladdningsspår.

## Kom igång

1. Ladda ner och packa upp hela ZIP-filen till en vanlig mapp.
2. Behåll `LANBlaster.exe` och `LANBlaster.pck` tillsammans. Starta `LANBlaster.exe`.
4. För LAN: en person väljer **Host LAN**, anger matchnamn och **2–16 slots**, och trycker **Create LAN lobby**. Välj sedan rätt nätkort under **HOST ADDRESS TO SHARE** och **Copy IP**. Övriga väljer **Join LAN** och matchen i listan eller ansluter till värdens lokala IP och samma UDP-port.
5. Alla använder **samma version**. Värden kan lägga till botar, välja två/fyra lag, liv, banlista och banomröstning i Match settings. Alla människor ska vara Ready; botar blir redo automatiskt. Minst två deltagare räcker och alla slots behöver inte fyllas. Butiken erbjuder tio köp för mynt och startar rundan när alla är klara eller efter 30 sekunder. Läs regler och föremål i How to play / F1.

Styr med WASD/piltangenter och använd bomber med mellanslag. Q byter bombtyp och WEAPON-panelen visar valet. E / handkontroll Y använder Bomb throw när förmågan finns. Tangentbordet kan bindas om i hjälpen. Escape öppnar menyn. M tystar eller återupptar musiken. Tangentbord och handkontroll stöds. Musik och ljudeffekter har separata reglage.

Standardportar: UDP **24560** för match och **24561** för lokal upptäckt. Windows kan behöva tillåta spelet på det privata nätverket. En utförligare svensk guide och motorns licenstexter ingår i ZIP-filen.

## Egen ikon på en Windows-genväg

Spelfönstret använder LAN Blaster-ikonen. Själva `LANBlaster.exe` är den oförändrade Godot-programfilen och visar därför Godot-ikonen i Utforskaren. `LANBlaster.ico` följer med som separat ikonfil.

1. Packa upp hela ZIP-filen till den mapp du vill behålla spelet i.
2. Högerklicka på `LANBlaster.exe` och välj **Visa fler alternativ → Skicka till → Skrivbord (skapa genväg)**.
3. Högerklicka på den nya genvägen och välj **Egenskaper → Genväg → Byt ikon → Bläddra**.
4. Välj `LANBlaster.ico` i spelets mapp och tryck **OK → Verkställ**.

Om du flyttar spelets mapp behöver genvägens sökvägar uppdateras eller genvägen skapas igen.

## Hjälp oss testa

Detta är en utvecklingsversion. Fysiska Windows- och LAN-tester återstår. Rapportera versionsnummer, antal spelare, vad som hände och hur felet går att upprepa. Skicka återkoppling till personen som bjöd in dig till testet.

Spelet använder egen kod, grafik, ljudeffekter och musik. Ursprungliga MasterBlaster-resurser ingår inte. Godot och dess beroenden har separata licenser som följer med paketet.

