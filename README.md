# Térinformatika Leaflet beadandó

Az általam elkészített projektfeladatban a Debreceni Egyetem campus területeit digitalizáltam.

A polygonok, markerek pontjainak meghatározására `geojson.io`-t használtam

## Rétegek, rétegkezelés

A projektben 3 alaptérkép közül választhat a felhasználó, melyek a következők:

- OSM alaptérkép
- MapTiler Streets V2
- MapTiler Satellite

### Objektumcsoportok

A térképen megjeleníthető a Debreceni Egyetemhez tartozó `Campusok területei` (ezek sokszögeket jelentenek a térképen). Rájuk kattintva egy felugró ablakban olvashatjuk az adott Capmus terület nevét.

Emelett megjeleníthetőek a különböző egyetemi karok legfőbb épülete, melyeket körök jelölnek. Minden kör színe attól függ, hogy hány hallgatója van az adott karnak. Minél több hallgató jár egy adott karra, annál sötétebb, vörösebb, színe van a körnek. Amennyiben a felhasználó rákattint egy ilyen említett kör objektumra, egy felugró ablakban olvasható az adott kar neve, illetve az, hogy hány hallgatója van a karnak.

Megjeleníthetőek az egyetem fennhatósága alá tartozó kollégiumok helyjelölői is, melyek egy saját ikont használnak. Nem csak a debreceni, hanem pl. a nyíregyházi, vagy szolnoki kollégiumokat is megtalálhatjuk. Ezek az objektumok is el vannak látva pop-up menüvel, melyek akkor jelennek meg, ha a felhasználó rájuk kattint. Ilyenkor megjelenítésre kerül az adott kollégium neve.

Egy 'Térképek' réteg is látható a rétegcsoportok között, amely egy átfedő kép objektumot tartalmaz. Ez az átfedő kép egy felülnézeti térkép a Debreceni Egyetem Böszörményi úti Capmusáról.

## Adatok, hivatkozások

A projekt elkészítéséhez a következő forrásokból gyűjtöttem adatokat:

- https://mad-hatter.it.unideb.hu/portal/displayDocument/Dokumentumtár/Statisztikák/Hallgatói/2022/2023.%20tanév/A%20Debreceni%20Egyetem%20hallgatóinak%202023.%20március%2015-i%20létszámadatai%20finanszírozási%20formák%20szerint.pdf
- https://unideb.hu/kollegiumok

Az alaptérképek stílusait a következő forrás biztosította:
https://www.maptiler.com
