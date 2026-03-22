# 📱 Android Secret Codes & Network Commands

Una raccolta completa e corretta di codici USSD e segreti per Android per la diagnostica hardware, la gestione della privacy e il controllo delle chiamate.

## ⚠️ Avvertenze
- **Procedere con cautela:** Alcuni codici (specialmente nella categoria Reset) possono cancellare i dati senza preavviso.
- **Compatibilità:** Alcuni codici dipendono dal produttore (Samsung, Xiaomi, ecc.) o dall'operatore di rete.

---

## 📋 Lista dei Codici

| Categoria | Funzione | Codice | Descrizione |
| :--- | :--- | :--- | :--- |
| **Identità** | Visualizza IMEI | `*#06#` | Identificativo univoco universale del dispositivo. |
| **Identità** | Info Telefono e Batteria | `*#*#4636#*#*` | Statistiche d'uso, info batteria e dettagli rete. |
| **Privacy** | Anonimo (Attiva) | `*31#` | Nasconde il numero per la chiamata successiva. |
| **Privacy** | Anonimo (Disattiva) | `#31#` | Mostra il numero se precedentemente nascosto. |
| **Privacy** | Anonimo (Stato) | `*#31#` | Verifica se l'ID chiamante è attivo o nascosto. |
| **Rete** | Avviso di Chiamata | `*43#` / `#43#` | Attiva o disattiva l'avviso di chiamata in entrata. |
| **Rete** | Reset Deviazioni | `##002#` | Disattiva istantaneamente tutte le deviazioni di chiamata. |
| **Sicurezza** | Blocco Tutte Entrata | `*35*Password#` | Inibisce la ricezione di tutte le chiamate in arrivo. |
| **Sicurezza** | Sblocca Tutte Entrata | `#35*Password#` | Riabilita la ricezione delle chiamate in entrata. |
| **Sicurezza** | Blocco Tutte Uscita | `*33*Password#` | Inibisce l'effettuazione di tutte le chiamate in uscita. |
| **Sicurezza** | Sblocca Tutte Uscita | `#33*Password#` | Riabilita le chiamate in uscita. |
| **Sicurezza** | Stato Blocchi | `*#33#` / `*#35#` | Verifica se ci sono blocchi attivi su uscita o entrata. |
| **Hardware** | Test Generale (Samsung) | `*#0#*` | Menu di test completo per LCD e sensori. |
| **Hardware** | Test Touch Screen | `*#*#2664#*#*` | Verifica la precisione del pannello. |
| **Hardware** | Sensore Prossimità | `*#*#0588#*#*` | Test del sensore di spegnimento schermo. |
| **Hardware** | Vibrazione/Backlight | `*#*#0842#*#*` | Test motorino e retroilluminazione. |
| **Hardware** | Test Audio | `*#*#0673#*#*` | Test altoparlanti e frequenze. |
| **Hardware** | Info Fotocamera | `*#*#34971539#*#*` | Dettagli firmware fotocamera (Non aggiornare). |
| **Connettività** | MAC Wi-Fi | `*#*#232338#*#*` | Visualizza l'indirizzo fisico della scheda Wi-Fi. |
| **Connettività** | Test Bluetooth | `*#*#232331#*#*` | Test di connessione del chip Bluetooth. |
| **Connettività** | Test GPS | `*#*#1472365#*#*` | Test rapido del ricevitore GPS. |
| **Firmware** | PDA e Phone | `*#*#1234#*#*` | Versioni firmware PDA e parte telefonica (Samsung). |
| **Firmware** | Dettagli Build | `*#*#44336#*#*` | Mostra Build Time e numero della Changelist. |
| **Utility** | Backup Media | `*#*#273282*255*663282*#*#*` | Backup rapido di immagini e video. |
| **Utility** | Service Mode | `*#*#197328640#*#*` | Menu per test ingegneristici avanzati. |
| **Reset** | Factory Reset | `*#*#7780#*#*` | Ripristino dati (mantiene il firmware). |
| **Reset** | Factory Format | `*2767*3855#` | Formattazione totale e reinstallazione firmware. |
