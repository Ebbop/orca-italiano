# Italiano per Orca

L’interfaccia di [Orca](https://github.com/stablyai/orca) in italiano, come plugin di lingua.
Solo dati: non esegue codice e non chiede autorizzazioni. A cura di [jAI Studio](https://jaistudio.it).

> Pacchetto **non ufficiale**, fatto dalla community. Non è affiliato né approvato da Stably / Lovecast Inc.

## Perché questo pacchetto

- **Tutto tradotto, misurato.** A ogni versione si estrae dall’Orca installato l’elenco completo dei testi
  traducibili e si confronta con la traduzione. Il conteggio aggiornato (testi tradotti su testi totali)
  è scritto nella descrizione del plugin, così si vede prima di installarlo.
- **Pensato per i limiti di Orca.** Il pacchetto viene costruito con gli stessi controlli che Orca applica
  al caricamento: segnaposto identici all’inglese, lunghezza massima, testi protetti esclusi. Nessun testo
  viene scartato in silenzio, e l’italiano resta sempre nel menu Lingua.
- **Italiano curato.** Dai del tu, imperativo nei pulsanti, apostrofi tipografici (l’agente, un’app), termini
  git in inglese come li usi ogni giorno (branch, commit, worktree, pull request).
- **Segue Orca.** La versione del plugin è quella di Orca a cui la traduzione è allineata, e si aggiorna
  con le nuove versioni.

I testi che Orca protegge (conferme di sicurezza, pagina dei plugin) restano in inglese con qualsiasi
pacchetto di lingua: è una scelta di Orca.

## Installazione

Da terminale:

```sh
orca plugin install Ebbop/orca-italiano
```

Oppure in Orca: **Impostazioni → Plugin**, cerca **Italiano** nel catalogo community e installalo.
Poi **Impostazioni → Aspetto → Lingua → Italiano**.

## Versioni

Con un Orca più nuovo il pacchetto funziona lo stesso: i testi aggiunti dopo restano in inglese finché
non esce la versione allineata.

## Segnalare un errore

Apri una issue con il testo che vedi, dove lo vedi e come lo scriveresti. Uno screenshot aiuta.

---

# Italian for Orca

Unofficial, community-made Italian UI language pack for Orca by [jAI Studio](https://jaistudio.it). Data only.
Covers every translatable string of the Orca version it is aligned to (the current count is in the plugin description), built
against Orca’s own load-time limits. Not affiliated with or endorsed by Stably / Lovecast Inc. Licensed under
MIT; see `LICENSE`.
