# Preču piegādes maršrutēšana

## 1. Ievads

Piegādes maršrutēšanas mērķis ir izvēlēties labākos maršrutus, lai transportlīdzekļi varētu efektīvi piegādāt produktus klientiem.
Maršrutēšanas pamatmērķis būs samazināt kopējo nobraukto attālumu, piegādes ilgumu un pirkuma cenu, ievērojot vairākus ierobežojumus. Viens no šādiem ierobežojumiem varētu būt transportlīdzekļa kravnesība, cits varētu būt klienta norādītais piegādes laika intervāls, un vēl viens varētu būt maksimālais laiks, kurā transportlīdzeklis var darboties.
Piegādes maršrutēšana ir saistīta ar **Vehicle Routing Problem (VRP)** koncepciju, tā balstās uz vairāku maršrutu atrašanu vairākiem transportlīdzekļiem.
---

## 2. Līdzīgo risinājumu izpēte

Preču piegādes maršrutēšanai jau ir izstrādāti dažādi programmatūras risinājumi, to funkcionalitāte un pielietošanas veids atšķiras, taču galvenais uzdevums ir līdzīgs – atrast efektīvus piegādes maršrutus.

### 2.1. Google OR-Tools

**Google OR-Tools** ir atvērtā koda optimizācijas bibliotēka. Tā piedāvā iespējas risināt transportlīdzekļu maršrutēšanas problēmas un citus optimizācijas uzdevumus.

OR-Tools maršrutēšanas funkcionalitāte ļauj izmantot:

- vairākus transportlīdzekļus;
- transportlīdzekļu kravnesības ierobežojumus;
- piegādes laika logus;
- maksimālo maršruta garumu;
- preču saņemšanas un piegādes punktus;
- dažādus citus maršrutēšanas ierobežojumus.

**Priekšrocības:**

- atvērtā koda risinājums;
- plašas pielāgošanas iespējas;
- piemērots dažādu VRP problēmu risināšanai;
- iespējams izmantot programmēšanas projektos.

**Trūkumi:**

- nepieciešamas programmēšanas zināšanas;
- lietotāja saskarne jāizveido pašam;
- nepieciešami dati par attālumiem vai ceļošanas laiku.

Avots: https://developers.google.com/optimization/routing

---

### 2.2. Google Route Optimization API

**Google Route Optimization API** ir mākoņpakalpojums, kas paredzēts transportlīdzekļu un piegādes maršrutu optimizēšanai.

API var izmantot, lai aprakstītu transportlīdzekļus, piegādes, kravnesību, darba laikus un citus ierobežojumus, sistēma pēc tam aprēķina optimizētu maršrutu.

**Priekšrocības:**

- gatavs maršrutu optimizācijas pakalpojums;
- iespējams izmantot vairākus transportlīdzekļus;
- iespējams norādīt kravnesību;
- iespējams izmantot laika logus;
- piemērots integrācijai citās programmās.

**Trūkumi:**

- nepieciešams Google Cloud projekts;
- pakalpojuma izmantošana var būt maksas;
- algoritma iekšējā darbība nav tik brīvi pielāgojama kā paša izstrādātam algoritmam;
- risinājums ir atkarīgs no ārēja pakalpojuma.

Avots: https://developers.google.com/maps/documentation/route-optimization/overview

---

### 2.3. Route4Me

**Route4Me** ir komerciāla platforma maršrutu plānošanai un optimizēšanai, tā ir paredzēta uzņēmumiem, kuriem nepieciešams plānot piegādes un transportlīdzekļu maršrutus.

Platforma piedāvā dažādas funkcijas, piemēram:

- vairāku transportlīdzekļu maršrutēšanu;
- piegādes laika logus;
- transportlīdzekļu kravnesības ierobežojumus;
- vairākas noliktavas;
- prioritātes;
- maršrutu pārplānošanu;
- pickup un delivery uzdevumus;
- API integrācijai ar citām sistēmām.

**Priekšrocības:**

- gatava lietotāja saskarne;
- nav nepieciešams pašam izstrādāt visu optimizācijas sistēmu;
- atbalsta dažādus reālus piegādes ierobežojumus;
- iespējama integrācija ar citām sistēmām.

**Trūkumi:**

- komerciāls risinājums;
- pilna funkcionalitāte var būt pieejama tikai maksas plānos;
- lietotājam ir mazāka kontrole pār izmantoto optimizācijas algoritmu;
- nepieciešams izmantot ārēju platformu.

Avots: https://route4me.com/platform/route-planning-software

---

## 3. Līdzīgo risinājumu salīdzinājums

| Kritērijs | Google OR-Tools | Google Route Optimization API | Route4Me |
|---|---|---|---|
| Risinājuma veids | Atvērtā koda bibliotēka | Mākoņpakalpojuma API | Komerciāla platforma |
| VRP atbalsts | Jā | Jā | Jā |
| Vairāki transportlīdzekļi | Jā | Jā | Jā |
| Kravnesības ierobežojumi | Jā | Jā | Jā |
| Laika logi | Jā | Jā | Jā |
| Pickup / Delivery | Jā | Jā | Jā |
| API | Bibliotēka | Jā | Jā |
| Lietotāja saskarne | Jāizstrādā pašam | Jāizstrādā pašam | Gatava |
| Pielāgošanas iespējas | Augstas | Vidēji augstas | Atkarīgas no platformas |
| Izmaksu modelis | Atvērtā koda | Atkarīgs no izmantošanas | Komerciāls pakalpojums |
| Piemērotība mācību projektam | Augsta | Vidēja | Vidēja |
| Algoritma izpētes iespējas | Augstas | Ierobežotas | Ierobežotas |
