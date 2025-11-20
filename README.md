# Turni 4ª Squadra 2026

Questa è una semplice applicazione web per visualizzare e gestire il calendario dei turni per la 4ª squadra per l'anno 2026.

## Scopo

L'applicazione fornisce un'interfaccia chiara e semplice per i membri della squadra per:
- Visualizzare il proprio turno giornaliero.
- Vedere il calendario mensile dei turni.
- Analizzare le statistiche annuali (giorni lavorati, riposi, notti, ecc.).
- Tenere traccia dei turni dei colleghi di altre squadre.
- Esportare il calendario per l'uso in altre applicazioni.

## Setup

Non è richiesta alcuna configurazione complessa. Basta aprire il file `index.html` in un qualsiasi browser web moderno. L'applicazione è interamente contenuta in un unico file e non richiede una connessione internet per funzionare.

## Funzionalità

### 🏠 Oggi
- Mostra il turno del giorno corrente con i dettagli dell'orario.
- Include un conto alla rovescia per l'inizio o la fine del turno.
- Elenca i turni per i prossimi 7 giorni.

### 📅 Mese
- Un calendario completo per visualizzare i turni di qualsiasi mese del 2026.
- Evidenzia il giorno corrente.
- Cliccando su un giorno si apre una finestra con i dettagli del turno.

### 📊 Analisi
- Fornisce statistiche annuali come giorni lavorati, giorni di riposo, turni di notte e ore totali.
- Calcola i weekend liberi (Sabato + Domenica).
- Suggerisce "ferie smart" per massimizzare i periodi di riposo.

### 👥 Squadra
- Permette di aggiungere i colleghi di altre squadre per visualizzare i loro turni a confronto.
- I dati dei colleghi vengono salvati localmente nel browser.

### 📲 Export
- **Sincronizza col Telefono**: Scarica un file `.ics` con tutti i turni del 2026, importabile in Google Calendar, Apple Calendar, e altre applicazioni di calendario. Include notifiche 1 ora e 15 minuti prima di ogni turno.
- **Copia Turni Mese**: Copia i turni del mese corrente come testo semplice.
- **Reset Dati**: Cancella tutti i dati salvati localmente (come la lista dei colleghi).

## Tecnologie Utilizzate

- HTML
- CSS
- JavaScript (Vanilla)

L'applicazione è volutamente semplice e non utilizza framework esterni per garantire la massima portabilità e facilità d'uso.
