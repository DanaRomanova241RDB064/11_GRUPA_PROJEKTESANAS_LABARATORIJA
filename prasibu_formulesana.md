# Preču piegādes maršrutēšanas sistēmas prasības

## 1. Sistēmas funkcijas un iezīmes

Šajā sadaļā definētas preču piegādes maršrutēšanas sistēmas funkcionālās prasības. Prasības ir formulētas lietotāju stāstu veidā, norādot lietotāju, vēlamo darbību un darbības ieguvumu.

### PR-01 — Lietotāja autorizācija

**Lietotāja stāsts:**  
Dispečers vēlas reģistrēties un pieteikties sistēmā, jo maršrutu informācijai jābūt pieejamai tikai autorizētiem lietotājiem.

**Prioritāte:** Must have.

### PR-02 — Maršruta izveide

**Lietotāja stāsts:**  
Dispečers vēlas izveidot jaunu piegādes maršrutu, jo nepieciešams saplānot preču piegādi vairākiem klientiem.

**Prioritāte:** Must have.

### PR-03 — Klientu pievienošana maršrutam

**Lietotāja stāsts:**  
Dispečers vēlas pievienot maršrutam apmeklējamos klientus un viņu adreses, jo nepieciešams noteikt vietas, uz kurām jānogādā preces.

**Prioritāte:** Must have.

### PR-04 — Piegādes laika ievade

**Lietotāja stāsts:**  
Dispečers vēlas norādīt katra klienta piegādes laika intervālu, jo preces klientiem jānogādā noteiktajā laikā.

**Prioritāte:** Must have.

### PR-05 — Kurjeru skaita norādīšana

Šī funkcija nodrošinās iespēju definēt konkrētu kurjeru skaitu, kas tiek izmantots noteiktas preču grupas piegādei uz kādu atrašanās vietu. Pieejamo kurjeru skaits rada ietekmi uz maršrutu aprēķināšanu, kas sistēmai norādīs, cik klientu var piešķirt katram kurjeram sistēmā. Kad ir norādīts kurjeru skaits, sistēma veidos piegādes maršrutu katram kurjeram, ņemot vērā pieejamo kurjeru skaitu, ja ir norādīti vairāki kurjeri, klientu apkalpošanas zvanus var sadalīt starp dažādiem maršrutiem, tas ir, aprēķinot maršrutus, mēs ņemam vērā ne tikai klientu atrašanās vietas, bet arī to, cik kurjeru ir pieejams.

**Lietotāja stāsts:**  
Dispečers vēlas norādīt pieejamo kurjeru skaitu, jo maršruta aprēķinam jāņem vērā pieejamie piegādes resursi.

**Prioritāte:** Must have.

### PR-06 — Attālumu datu izmantošana

Šī funkcija ļaus mums izmantot attālumu starp visiem punktiem, kas ir maršrutā, šie dati parādīs, cik tālu atrodas konkrēti klienti. Šie dai būs vajadzīgi, lai aprēķinātu maršrutu, jo mūsu sistēmai jāspēj salīdzināt dažādas iespējamās klientu apkalpošanas secības. Kad mēs lietojam šos datus, maršrutēša
**Lietotāja stāsts:**  
Dispečers vēlas izmantot attālumu datus starp maršruta punktiem, jo attālumi ir nepieciešami piegādes maršruta aprēķināšanai.

**Prioritāte:** Must have.

### PR-07 — Maršruta aprēķināšana

Šī funkcija automātiski aprēķinās piegādes maršrutus, izmantojot ievadītos datus un maršrutēšanas iestatījumus, tālāk apstrādās informāciju par klientiem, to atrašanās vietām, piegādes laika ierobežojumiem, kurjeru skaitu un attālumiem starp punktiem. Tādējādies tiks noskaidrots, kādi klienti tiks apmeklēti un kā tie tiks sadalīti kurjeriem. 

**Lietotāja stāsts:**  
Dispečers vēlas aprēķināt piegādes maršrutu, jo nepieciešams noteikt klientu apmeklēšanas secību.

**Prioritāte:** Must have.

### PR-08 — Maršruta attēlošana kartē

Šī funkcija rādīs maršrutu uz kartes, parādīs visus klientus, kas ietilpst maršrutā, un savienojumus starp tiem, lai lietotājs viegli redzētu, kā notiek piegāde. Kartes veidā būs vieglāk pārskatāms un pārbaudāms,  vai maršruts izskatās pareizi, vai tas atbilst plānotajam ceļam, kā arī vieglāk redzami sākuma un beigu punkti, kur atrodas klienti un kādā secībā tie tiks apmeklēti.

**Lietotāja stāsts:**  
Dispečers vēlas apskatīt aprēķināto maršrutu kartē, jo nepieciešams vizuāli pārbaudīt plānoto piegādes ceļu.

**Prioritāte:** Must have.

### PR-09 — Maršruta grafiska attēlošana

Šī funkcija parādīs aprēķināto maršruta attēlu kā grafu, tur tiks rādīti maršruta punkti kā virsotnes un savienojumi starp tiem kā posmu. Grafiskais attēlojums vairāk ir paredzēts maršruta analīzei, kas ļauj salīdzināt, kā maršruta struktūra izskatās, un redzēt, kādā secībā klienti tiek apmeklēti. 

**Lietotāja stāsts:**  
Dispečers vēlas apskatīt maršrutu grafiskā veidā, jo nepieciešams pārskatīt klientu un maršruta punktu savstarpējo secību.

**Prioritāte:** Should have.

### PR-10 — Maršruta efektivitātes rādītāji

**Lietotāja stāsts:**  
Dispečers vēlas apskatīt maršruta efektivitātes rādītājus, jo nepieciešams novērtēt aprēķinātā maršruta efektivitāti.

**Prioritāte:** Should have.

### PR-11 — Maršruta saglabāšana

**Lietotāja stāsts:**  
Dispečers vēlas saglabāt aprēķināto maršrutu, jo nepieciešams to izmantot un pārskatīt arī pēc maršruta aprēķināšanas.

**Prioritāte:** Should have.

### PR-12 — Iepriekšējo maršrutu pārlūkošana

**Lietotāja stāsts:**  
Dispečers vēlas apskatīt iepriekš izveidotos maršrutus, jo nepieciešams pārskatīt iepriekšējos piegādes plānus un to rezultātus.

**Prioritāte:** Could have.

### PR-13 — Maršruta datu labošana

**Lietotāja stāsts:**  
Dispečers vēlas labot maršruta datus, jo klientu adreses, piegādes laiki vai citi maršruta parametri var mainīties.

**Prioritāte:** Could have.

### PR-14 — Maršruta dzēšana

**Lietotāja stāsts:**  
Dispečers vēlas dzēst nevajadzīgu maršrutu, jo sistēmā nav nepieciešams saglabāt vairs neizmantojamus maršrutus.

**Prioritāte:** Could have.

### PR-15 — Maršrutēšanas parametru ievade

**Lietotāja stāsts:**  
Dispečers vēlas norādīt maršrutēšanas parametrus, jo nepieciešams pielāgot maršruta aprēķinu konkrētajai piegādes situācijai.

**Prioritāte:** Must have.

### PR-16 — Maršrutu saraksta pārlūkošana

**Lietotāja stāsts:**  
Dispečers vēlas pārlūkot sistēmā izveidoto maršrutu sarakstu, jo nepieciešams ātri atrast un apskatīt konkrētu piegādes maršrutu.

**Prioritāte:** Should have.

### PR-17 — Piegādes klientu saraksta pārlūkošana

**Lietotāja stāsts:**  
Dispečers vēlas pārlūkot maršrutam pievienoto klientu sarakstu, jo nepieciešams pārbaudīt, kuri klienti ir iekļauti piegādes maršrutā.

**Prioritāte:** Should have.

### PR-18 — Maršruta parametru mainīšana

**Lietotāja stāsts:**  
Dispečers vēlas mainīt maršruta aprēķinam izmantotos parametrus, jo dažādām piegādes situācijām var būt nepieciešami atšķirīgi maršrutēšanas nosacījumi.

**Prioritāte:** Should have.


## 2. Prasību prioritizēšana pēc MoSCoW metodes

MoSCoW metode tiek izmantota, lai noteiktu prasību nozīmīgumu un izdalītu sistēmas minimāli nepieciešamo funkcionalitāti no papildu funkcijām.

| Prioritāte | Nozīme | Prasības |
|---|---|---|
| **Must have** | Funkcijas, kas nepieciešamas sistēmas pamatdarbībai | PR-01, PR-02, PR-03, PR-04, PR-05, PR-06, PR-07, PR-08, PR-15 |
| **Should have** | Svarīgas funkcijas, bet sistēma var darboties arī bez tām | PR-09, PR-10, PR-11, PR-16, PR-17, PR-18 |
| **Could have** | Papildu funkcijas, kuras var ieviest, ja ir pietiekami laika un resursu | PR-12, PR-13, PR-14 |
| **Would have** | Funkcijas, kas šobrīd atrodas ārpus projekta tvēruma | Reāllaika satiksmes datu izmantošana, kurjera atrašanās vietas izsekošana un automātiska maršruta pārrēķināšana piegādes laikā |
## 6. Would have prasības

**Would have** prasības šajā projekta posmā atrodas ārpus projekta tvēruma. Tās varētu tikt apsvērtas nākamajās sistēmas versijās. Pie šādām funkcijām var pieskaitīt reāllaika satiksmes datu izmantošanu, kurjera atrašanās vietas izsekošanu un automātisku maršruta pārrēķināšanu piegādes laikā.
