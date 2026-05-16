# Calendario Piante

App Android nativa in Java per segnare annaffiature, controllare il meteo della città e gestire piante, orto, vasi, balcone, serra o giardino.

## Funzioni principali

- Meteo specifico per città tramite Open-Meteo, senza API key.
- Città predefinita: **Acqui Terme**.
- Ricerca città manuale, compatibile anche con errori come `AquiTerme`.
- Calendario a griglia da 14 giorni.
- Selezione del giorno da calendario Android, pulsanti rapidi Ieri/Oggi/Domani e tap diretto sulla griglia.
- Registrazione annaffiatura per **mattina** o **sera**.
- Campo **Zona o pianta** per usare l'app anche fuori dall'orto.
- Quantità opzionale in litri e note.
- Riepilogo automatico del giorno selezionato.
- Se piove, l'app suggerisce di saltare o ridurre l'annaffiatura.
- Se piove oggi, anche la mattina del giorno dopo viene considerata coperta.
- Salvataggio locale con `SharedPreferences`.

## Come aprire il progetto

1. Apri Android Studio.
2. Fai `File > Open`.
3. Seleziona questa cartella del repository.
4. Aspetta il Gradle Sync.
5. Vai su `Run > Edit Configurations`.
6. In `Module` scegli `app`.
7. Premi Run.

Se Android Studio chiede di installare SDK 35 o Android Gradle Plugin 8.5.2, accetta.

## Note

Il progetto è Java puro, senza AndroidX e senza Compose, così resta leggero e semplice da modificare.