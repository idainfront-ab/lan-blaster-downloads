# LAN Blaster för Windows

Ett retroinspirerat arenaspel för **2–16 spelare på LAN**, en spelare per dator, med Practice och botar. Internet behövs inte när spelet är nedladdat.

## Senaste version: 1.2.8

**[Ladda ner LAN Blaster för Windows x64](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v1.2.8/LAN_Blaster_1.2.8_Windows.zip)**

[Versionsnyheter](https://github.com/idainfront-ab/lan-blaster-downloads/releases/tag/v1.2.8) · [Kontrollsumma SHA-256](https://github.com/idainfront-ab/lan-blaster-downloads/releases/download/v1.2.8/LAN_Blaster_1.2.8_Windows.zip.sha256) · [Tidigare versioner](https://github.com/idainfront-ab/lan-blaster-downloads/releases)

## Nytt i 1.2.8

- Liv och vapen visas ovanför spelplanen. Spelarnumren på banan har ersatts av en kort pil vid den egna spelarens respawn.
- Block som väntar på en säker plats blinkar inte. Varningar visas först för kontrollerade placeringar och sprids ut över tid.
- Remote Bomb har synlig nedräkning, max en bomb per spelare, tolv rutors körsträcka och en halv sekunds varning före den snabba detonationen.
- Quantum delar varje stråle åt båda sidor i ett symmetriskt mönster. Den röda Superbomben täcker upp till fem rader per arm, når längre och gör två livs skada. Drill Bomb och Shock Bomb har tagits bort.
- Rules har val för antal bonusar per leverans, gräns för bonusar på banan och bonusschans i nya block. Intensity presets höjer mängden stegvis.
- LAN-värden ser vilka som behöver trycka Ready. Vanliga lobbyändringar behåller Ready. Med sen anslutning på kan gäster titta, trycka Ready och vänta på en plats. En mänsklig spelare kan ersätta en bot.
- Remne, Klint och Hemling finns i Character. Brick Push förklarar den tidigare Superman-förmågan. Small arena scale finns under Video.

## Kom igång

1. Ladda ner och packa upp hela ZIP-filen till en vanlig mapp. Starta `LANBlaster.exe`; behåll PCK-filen och övriga filer i samma mapp.
2. Välj Practice, eller låt en person skapa en lobby med Host LAN. Övriga väljer Join LAN och matchen i listan. Värdens lokala IP-adress och UDP-port fungerar som reservväg.
3. Alla använder samma version och paketvariant. Välj Match settings, lägg vid behov till botar och gör alla spelare Ready innan matchen startas.

WASD/piltangenter flyttar. Space placerar bomber, Q byter vapentyp och vänster Ctrl detonerar Time/Remote-bomber. E kastar bomber när förmågan finns. F1 öppnar den grafiska hjälpen; tangentbord och handkontroll stöds. Alt+Enter växlar fullscreen. Musik och ljudeffekter har separata reglage.

Standardportar: UDP **24560** för match och **24561** för lokal upptäckt. Tillåt spelet på Windows privata nätverk. Guide och motorns licenstexter finns i ZIP-filen. Denna utgåva innehåller inget Lab-program.

## Ikon på skrivbordet

Skapa en genväg till LANBlaster.exe och välj den medföljande LANBlaster.ico under Egenskaper → Genväg → Byt ikon. Programfilen är den oförändrade Godot-exportmallen; spelets fönster har LAN Blaster-ikonen.

## Återkoppling

Ange version, spelläge, bana, antal spelare och vad som hände när du rapporterar ett problem. Källkod och privata byggloggar publiceras inte här. Godot och dess beroenden har separata licenser som följer med spelet.
