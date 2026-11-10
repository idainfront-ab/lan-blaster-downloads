# LAN Blaster — testversioner för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator. Spelet fungerar utan internetanslutning när det är nedladdat.

## Senaste testversion: 0.1.0-dev15.2

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.2/LAN_Blaster_0.1.0-dev15.2_Windows.zip)**

[Vad är nytt och kända begränsningar](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v0.1.0-dev15.2) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v0.1.0-dev15.2/LAN_Blaster_0.1.0-dev15.2_Windows.zip.sha256) · [Alla versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 0.1.0-dev15.2

- Huvudmenyn följer det godkända konceptet närmare: större logotyp och rubriker, rundade spelkort, tydligare valt läge, mjuka färgtoningar och sammanhängande regelknappar.
- Överdelen samlar avatar och namn i en spelarprofil. Character och Audio har ikoner; How to play ligger i sidfoten och nås även med F1. Namn, alla 19 figurer och accentfärger redigeras via profilen/Character.
- Join LAN, Practice, Host LAN och Customize rules har tydliga ikoner enligt konceptets formspråk.
- Banpanelen visar verklig banegrafik i större detalj. **Full map** växlar till hela den faktiska banan; **Detail** växlar tillbaka. Alla nio banor och Cycle maps finns kvar.
- Regelsammanfattning, BUILD/liv, SHOP och friendly fire grupperas som i konceptet. My presets öppnar både val och sparande av regelpaket.
- Samtliga inställningar, äldre regelpaket och lägesprofiler från Dev15.1 behålls. Spelregler, statistik, musik och Windows-runtime ändras inte.

Utvecklingsversion: mänskligt Windows-/LAN-provspel och fysisk handkontrollsprovning återstår. Alla datorer behöver samma version.

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

