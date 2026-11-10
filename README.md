# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev15.4

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.4/LAN_Blaster_0.1.0-dev15.4_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev15.4) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.4/LAN_Blaster_0.1.0-dev15.4_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev15.4

- Den nya banan heter nu **Desert Ruins** i spelet. Samma bana, originalgrafik och layouter för 2–4, 5–8 och 9–16 spelare finns kvar.
- Fortress-förhandsvisningen i Rules ändras direkt när befästa flaggrum slås av eller på. Efter Apply settings uppdateras även huvudmenyns banvy. Cancel behåller tidigare val.
- Audio-knappen får rätt storlek och placering både vid start och efter återkomst från en match.
- How to play ligger helt inom menyns nederkant och går fortfarande att öppna med knappen eller F1.
- BUILD och FRIENDLY FIRE är klickbara snabbval som sparar regeln direkt. BUILD återställer föregående frekvens när det slås på igen; Basic-only kräver byte till Mixed i Rules.
- Spelarprofilen har flyttats åt vänster och namntexten fått större utrymme samt anpassad textstorlek för långa namn.
- Customize rules får en varm accentfärg när inställningarna avviker från ett färdigt/sparat paket. Den fristående Custom-texten är borttagen; hjälptexten förklarar markeringen.
- Arena är frikopplad från huvudmenyns regelpaket. Standard, Quick match och My presets behåller vald bana, rotation och banlista. Ett banbyte släcker inte Quick match eller markerar spelreglerna som Custom. Fullständiga sparade profiler och Rules finns kvar.
- CTF Fortress finns via Capture The Flag → My presets. Välj Desert Ruins under Arena. Samma val används i Practice och Host LAN; vanliga CTF-regler och egna sparade val behålls.
- Ett enda nedladdningsspår: den vanliga nedladdningssidan länkar till senaste versionen. Äldre numrerade versioner finns kvar.

Fortress-reglerna är oförändrade: stå still på fiendens flaggruta i 1,5 sekunder för att stjäla flaggan från basen, släpp alla rörelseknappar. Skada avbryter försöket. En tappad fiendeflagga tas direkt. Respawnskydd måste ha upphört. Egen flagga måste vara hemma när motståndarens flagga lämnas in.

Desert Ruins är fortsatt första grafikprovet. Övriga banor använder sin tidigare grafik och spelmodell. Inga nya banor eller specialregler har lagts in i denna version.

Provspela särskilt de båda Fortress-previewerna, Audio/How to play före och efter match, start av Desert Ruins i Practice/LAN samt läsbarhet, kollision och eld runt centralruinen. Automatiska GitHub-kontroller ersätter inte fysiskt Windows-/LAN- och handkontrollsprov.

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

