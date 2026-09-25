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

**Lietotāja stāsts:**  
Dispečers vēlas norādīt pieejamo kurjeru skaitu, jo maršruta aprēķinam jāņem vērā pieejamie piegādes resursi.

**Prioritāte:** Must have.

### PR-06 — Attālumu datu izmantošana

**Lietotāja stāsts:**  
Dispečers vēlas izmantot attālumu datus starp maršruta punktiem, jo attālumi ir nepieciešami piegādes maršruta aprēķināšanai.

**Prioritāte:** Must have.

### PR-07 — Maršruta aprēķināšana

**Lietotāja stāsts:**  
Dispečers vēlas aprēķināt piegādes maršrutu, jo nepieciešams noteikt klientu apmeklēšanas secību.

**Prioritāte:** Must have.

### PR-08 — Maršruta attēlošana kartē

**Lietotāja stāsts:**  
Dispečers vēlas apskatīt aprēķināto maršrutu kartē, jo nepieciešams vizuāli pārbaudīt plānoto piegādes ceļu.

**Prioritāte:** Must have.

### PR-09 — Maršruta grafiska attēlošana

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

## 3. Must have prasības

**Must have** prasības veido sistēmas minimāli nepieciešamo funkcionalitāti. Tās nodrošina lietotāja autorizāciju, maršruta izveidi, klientu un piegādes informācijas ievadi, kurjeru skaita un maršrutēšanas parametru norādīšanu, kā arī piegādes maršruta aprēķināšanu un attēlošanu kartē.

Bez šīm funkcijām nebūtu iespējams nodrošināt sistēmas galveno uzdevumu — preču piegādes maršruta izveidi un aprēķināšanu.

## 4. Should have prasības

**Should have** prasības papildina sistēmas pamatfunkcionalitāti un uzlabo lietotāja iespējas analizēt un pārvaldīt izveidotos maršrutus. Šajā grupā ietilpst maršruta grafiska attēlošana, efektivitātes rādītāji, maršruta saglabāšana, maršrutu saraksta un klientu saraksta pārlūkošana, kā arī maršruta parametru mainīšana.

## 5. Could have prasības

**Could have** prasības nav nepieciešamas sistēmas minimālajai darbībai, bet tās var uzlabot sistēmas lietojamību. Šajā grupā ietilpst iepriekšējo maršrutu pārlūkošana, maršruta datu labošana un maršruta dzēšana.

## 6. Would have prasības

**Would have** prasības šajā projekta posmā atrodas ārpus projekta tvēruma. Tās varētu tikt apsvērtas nākamajās sistēmas versijās. Pie šādām funkcijām var pieskaitīt reāllaika satiksmes datu izmantošanu, kurjera atrašanās vietas izsekošanu un automātisku maršruta pārrēķināšanu piegādes laikā.
