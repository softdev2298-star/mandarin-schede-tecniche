# Mandarin – Generatore Schede Tecniche

Strumento web per generare automaticamente le schede tecniche dei macchinari Mandarin Knitting Technology in 5 lingue (IT / EN / PT / ES / TR).

## Come funziona

1. Apri il sito
2. Seleziona il modello di macchinario
3. Scegli la lingua
4. (Opzionale) Sostituisci l'immagine di default con una personalizzata
5. Clicca **Genera PDF** — la scheda viene scaricata pronta da inviare

## Caratteristiche

- **30 modelli** copertura completa catalogo 2026
- **5 lingue** italiano, inglese, portoghese, spagnolo, turco
- **Output A4** singola pagina, layout fedele allo standard Mandarin
- **100% offline** una volta caricato, nessun dato esce dal browser
- **Aggiornamento dati** sincronizzato con il database catalogo

## Stack tecnico

- HTML/CSS/JavaScript vanilla (single-file deployment)
- html2pdf.js per generazione PDF lato client
- Database embedded (~290 KB JSON)
- Hosting Cloudflare Pages
