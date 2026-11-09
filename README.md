# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev14.1

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.1/LAN_Blaster_0.1.0-dev14.1_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev14.1) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.1/LAN_Blaster_0.1.0-dev14.1_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev14.1

- **Löpande bonuspåfyllning i Team Deathmatch:** upp till tre nya bonusar var tolfte sekund, med två sekunders synlig förvarning. Välj bonuslådor, lösa bonusar, blandning eller av i Rules. Blandning ger ungefär 70 procent lådor. Lådor med cyan kant och plustecken innehåller en bonus. Taket är det högsta av åtta och två gånger deltagarantalet. Upptagna eller farliga rutor hoppas över; lådor får inte stänga en passage eller placeras nära lagbaser.
- **Fem nya bomber:** röd Superbomb med tre rutor brett eldkors, Borrbomb som förstör och passerar första sprängbara blocket, Studsbomb som rullar framåt och studsar en gång, Stötbomb som knuffar utan egen dödlig eld samt en synlig Minbomb. Minan armeras efter en sekund, reagerar på en motståndare på samma eller angränsande ruta och försvinner genom explosion senast efter 20 sekunder. Väggar stoppar elden och bombägaren behålls vid kedjereaktioner.
- **Laddningar:** ett fynd av en ny bombtyp ger en laddning, högst nio per typ. Placering förbrukar en laddning; misslyckad placering förbrukar ingen. Normalbomben finns alltid. Timebomb och Remote behåller sina tidigare förmågeregler.
- **Slow:** ett fynd halverar alla levande motståndares rörelsefart i fyra sekunder. Lagkamrater och respawnskyddade spelare undantas. Effekten staplar inte hastighetsminskningen; ett nytt fynd förlänger bara tiden. Nedräkning och blå markering syns i spelvyn. Bombknappen fungerar fortfarande.
- **Inventory:** alla åtta bombtyper visas samtidigt, med vald typ, laddningar, obegränsad användning och avstängda typer. Q / handkontroll X växlar bland användbara typer. Tomma och avstängda typer hoppas över; sista specialladdningen växlar tillbaka till Normal. Leave game ligger överst för att inventoryt ska vara fritt.
- **Rules:** flikarna Match, Teams, Maps, Items och Presets. Varje ny bomb och Slow har frekvensval inklusive Off. Avstängda typer spärras i fynd, Mystery och användning även om en laddning finns kvar. Regelpaket laddas för granskning och används först med Apply settings. Äldre sparade regelpaket migreras med bibehållna tidigare val.
- **Musikprov:** Arcade Pulse A i titelmenyn, Pulse B i lobbyn och Arcade Rush A–D i matcher. Team Deathmatch växlar Rush-spår vid nästa match utan direkt upprepning. Respawn byter inte musik. Rules → Match → Soundtrack växlar mellan provmusiken och den äldre musiken. Volym, mute, mjuka övergångar och slutminutens tempoökning finns kvar.

För att prova: **Practice rules → Presets → Team Deathmatch → Load selected preset → Apply settings**. Välj önskat deltagarantal och starta Practice. Ändra vapenfrekvenser på Items-fliken och bonuspåfyllning på Match-fliken.

Alla datorer i samma match måste använda **0.1.0-dev14.1**. Packa upp hela ZIP-filen och behåll EXE och PCK tillsammans. Ingen installation eller internetanslutning behövs för att spela.

Versionen har utvecklingstester och lokal Windows-bildgranskning. Mänskligt LAN-provspel, handkontroll, vapenbalans och musikalisk bedömning av loopskarvar och ljudbalans återstår. De nya Suno-looparna är ett prov, inte slutligt musikval. CTF och byggvapnet ingår inte i denna mellanversion.

## Kom igång

1. Ladda ner och packa upp hela ZIP-filen till en vanlig mapp.
2. Behåll `LANBlaster.exe` och `LANBlaster.pck` tillsammans. Starta `LANBlaster.exe`.
3. Ange **PLAYER NAME**, välj bana och **2–16 players**, och tryck **Practice** för att testa själv med 1–15 botar. Nio banfamiljer finns, inklusive **Factory, Portals och Switchyard**. Förhandsvisningen visar vald bana. Namnet sparas på datorn. **Practice with coins and shop** provar butiken; handla och tryck Done shopping för start.
4. För LAN: en person väljer **2–16 slots** och **Host LAN game**, sedan rätt nätkort under **HOST ADDRESS TO SHARE** och **Copy IP**. Övriga väljer matchen i listan eller ansluter till värdens lokala IP och samma UDP-port.
5. Alla använder **samma version**. Värden kan lägga till botar, välja två/fyra lag, liv, banlista och banomröstning i Match settings. Alla människor ska vara Ready; botar blir redo automatiskt. Minst två deltagare räcker och alla slots behöver inte fyllas. Butiken erbjuder tio köp för mynt och startar rundan när alla är klara eller efter 30 sekunder. Läs regler och föremål i How to play / F1.

Styr med WASD/piltangenter och använd bomber med mellanslag. Q byter bombtyp och WEAPON-panelen visar valet. E / handkontroll Y använder Bomb throw när förmågan finns. Tangentbordet kan bindas om i hjälpen. Escape öppnar menyn. M tystar eller återupptar musiken. Tangentbord och handkontroll stöds. Musik och ljudeffekter har separata reglage.

Standardportar: UDP **24560** för match och **24561** för lokal upptäckt. Windows kan behöva tillåta spelet på det privata nätverket. En utförligare svensk guide och motorns licenstexter ingår i ZIP-filen.

## Hjälp oss testa

Detta är en utvecklingsversion. Fysiska Windows- och LAN-tester återstår. Rapportera versionsnummer, antal spelare, vad som hände och hur felet går att upprepa. Skicka återkoppling till personen som bjöd in dig till testet.

Spelet använder egen kod, grafik, ljudeffekter och musik. Ursprungliga MasterBlaster-resurser ingår inte. Godot och dess beroenden har separata licenser som följer med paketet.

