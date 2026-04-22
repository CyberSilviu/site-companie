# Instrucțiuni și Specificații pentru Crearea Site-ului URBAN MINDS

Acest document conține structura și conținutul extrase din planul de afaceri, destinate echipei de dezvoltare web pentru crearea site-ului oficial al companiei.

## 1. Identitatea de Brand și Informații Generale
* **Nume Companie:** URBAN MINDS
* **Slogan:** "Oraşul tău, transparent și inteligent."
* **Logo:** Iconița `logo.png` (pătrat cu colțuri rotunjite, gradient roz-violet-albastru, text negru "UM").
* **Tehnologii recomandate (conform planului):** HTML5, CSS, JavaScript (hosting pe Netlify).

## 2. Misiune și Viziune (Pentru secțiunea "Despre Noi")
* **Misiunea:** Oferim cetățenilor, mediului de afaceri și administrațiilor publice locale o platformă digitală de inteligență civică ce transformă oraşele în spații mai transparente, mai sănătoase și mai implicate civic. Combinăm stații proprii de monitorizare a calității aerului şi a nivelului de zgomot cu aplicații web.
* **Viziunea:** În 3-5 ani, URBAN MINDS va deveni un brand național recunoscut pentru soluții de tip "smart city la cheie", prezent în minim 20 de primării din România. Existăm pentru că orașul devine inteligent doar atunci când deciziile se iau cu date reale și cu participarea comunității.

## 3. Echipa (Pentru secțiunea "Echipa Noastră")
Compania a fost fondată la Colegiul Tehnic C.F. UNIREA Paşcani.
* **Darius Iuganu** - CEO / Dezvoltare Software (clasa a X-a A)
* **Matei Bostan** - CTO / Hardware și Stații (clasa a XI-a F)
* **Simona Nechifor** - CMO / Design & Relația cu clienții (clasa a X-a A)
* **Prof. Silviu Muraru** - Coordonator

## 4. Structura Recomandată a Site-ului

### Pagina Principală (Home)
* **Hero Section:** Sloganul principal ("Oraşul tău, transparent și inteligent.") și un buton Call-to-Action (ex: "Descoperă Platforma" sau "Vezi Demo").
* **Avantaje Competitive (De ce noi?):** * Produs local (preț de 3-5 ori mai mic decât concurența).
  * Soluție integrată: hardware + software.
  * Componentă educațională unică (jocul "Ești primar").
* **Grup Țintă:** Menționarea clară că ne adresăm Primăriilor (B2G), Companiilor/Școlilor (B2B) și Cetățenilor (B2C).

### Pagina "Produse și Servicii"
URBAN MINDS este structurată în 2 module principale:
1. **Scut Urban 4.0**
   * 2 aplicații pentru calitatea aerului și zgomot.
   * Stații hardware proprii cu 8 indicatori (PM, UV, CO, CH4, VOC, H2, NH3, NO2) și seismometru.
   * Beneficiu: Monitorizare în timp real a poluării și zgomotului.
2. **CivicData LIVE**
   * 4 aplicații: "Investiția mea / Smart City" (investiții pe strada ta), Calculator impozit, Business Map (harta locală de afaceri) și jocul educațional "Ești primar".
   * Beneficiu: Transparență civică și educație.

### Pagina "Pachete și Prețuri"
Afișarea clară a celor 3 pachete disponibile:
* **Pachet Basic:** 2.500 lei/an. Include licență aplicație Scut Urban.
* **Pachet Standard:** 4.500 lei. Include aplicația Scut Urban + 1 stație calitate aer.
* **Pachet Premium (Recomandat pentru Primării):** 12.000 lei/an. Platforma completă URBAN MINDS + 2 stații cu seismometru + CivicData LIVE configurat pentru localitate.

### Pagina "Contact"
* Formular de contact.
* Locație: Colegiul Tehnic C.F. UNIREA Paşcani.
* Link-uri către rețelele sociale (Facebook, Instagram, TikTok conform strategiei de marketing).

## 5. Note Suplimentare pentru Dezvoltator
* **Funcționalități viitoare de integrat:** Dashboard în timp real (prin API REST pentru stații), hartă interactivă, integrare cu baze de date pentru bugetul local.
* **Aspect ecologic:** De menționat pe site că stațiile consumă puțin (0.1 kW) și carcasele sunt printate 3D din material biodegradabil (PLA).
