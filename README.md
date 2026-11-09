# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev14.4

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.4/LAN_Blaster_0.1.0-dev14.4_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev14.4) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev14.4/LAN_Blaster_0.1.0-dev14.4_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev14.4

- **Quantum Bomb:** fyra strålar går två rutor rakt, svänger 90 grader medurs och fortsätter två rutor till. Ingen förgrening. Vanlig stubin, en laddning och normala regler för väggar, tegel, skada och kedjereaktioner.
- **Valbar i Rules:** Quantum Bomb frequency har Off/Low/Normal/High. Off spärrar fynd, Mystery, bonuspåfyllning, Q-val och användning av insamlade laddningar. Låg frekvens är standard. Tidigare sparade preset får det nya valet utan att ändra gamla inställningar.
- **Tydlig böj och säker återkomst:** bomben har vit/indigofärgad kropp och vinklade pilar; små L-markeringar visar de möjliga svängarna. Botarnas prognos och säkra respawnplatser följer den böjda elden.
- **Illustrerade sprites för hela föremålspaketet:** samtliga 21 bonusar och nio bombtyper använder nya PNG-bilder med material, reflexer och egna former. Samma bilder syns i spel, butik, guide och inventory.
- **Classic närmare koncepten:** illustrerat gräs, stenpelare, varmt/rött/sprucket grått tegel och låg stenmur. Gemensamma nya föremål används på alla nio banor; övriga åtta banmiljöers grafiklyft följer senare.
- **Nio tydliga vapenplatser:** Q/pad X växlar i ett 3×3-inventory. Tidigare startbutik, respawnutrustning, bonuspåfyllning, Slow och Pulse/Rush-musik finns kvar.

Prova **Classic** i olika storlekar. Välj Mixed och låt Quantum vara på i Rules → Items; samla en laddning, välj den med Q och planera för medurs svängar.

Byggning, bildförberedelse, pixel-/regel-/Practice-/LAN-tester och renderade bildkontroller sker i GitHub Actions. Fysiskt Windows-/LAN-/handkontrollprov, referens-PC-prestanda och slutlig mänsklig stil-/balansbedömning återstår. Alla i samma LAN-match behöver **0.1.0-dev14.4**. Packa upp hela ZIP-filen och behåll EXE och PCK tillsammans.

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

