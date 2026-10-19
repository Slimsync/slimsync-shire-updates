# Slimsync Shire: nieuwe versies

Hier staan de nieuwe versies van **Slimsync Shire**, een Windows-programma waarin AI-assistenten echt werk doen. Je ziet
ze als bewoners van een klein pixel-art dorp op een zwevend eiland.

In deze repository staan alleen de ondertekende installatiebestanden (zips) en "Wat is nieuw". De broncode staat hier
niet. (De links "Source code" die GitHub bij elke release zet, bevatten alleen deze uitleg.)

## Installeren

1. Open de nieuwste release (rechts, onder **Releases**) en download `Slimsync-Shire-<versie>.zip`.
2. Pak de zip helemaal uit: rechtermuisknop, **Alles uitpakken…**.
3. Open de map **Slimsync Shire**, dubbelklik op **Slimsync Shire** en klik op **Installeren**. Beheerdersrechten zijn
   niet nodig.

Meer staat in `LEES MIJ EERST.txt` in de zip, en in de handleiding in de app.

## Bijwerken

Heb je Slimsync Shire al? Dan kijkt de app hier zelf (na de eerste start meteen, daarna hooguit één keer per dag) en
zegt hij het als er een nieuwe versie is. Klik dan op **Bijwerken**. De app maakt eerst een reservekopie van je
gegevens; je dorp, je gesprekken en je instellingen blijven bewaard.

## Veilig

Elke versie is ondertekend met de sleutel van Slimsync: `Slimsync-Shire-update.sig` is de handtekening over
`Slimsync-Shire-update.json`, en daarin staat de vingerafdruk (SHA-256) van de zip. De app installeert alleen een versie
met een geldige handtekening en de juiste vingerafdruk.
