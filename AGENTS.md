# Istruzioni per gli agenti

Questo repository contiene una tesi di laurea in LaTeX. Ogni modifica deve
preservare il contenuto, la struttura e l'impostazione del documento di
riferimento `reference/riferimento_originale.pdf`.

## Documento di riferimento

- Usa `reference/riferimento_originale.pdf` come fonte di verità per testo,
  ordine delle sezioni, titoli, didascalie, riferimenti e impaginazione quando
  sono oggetto della modifica.
- Non riscrivere, sintetizzare o correggere il testo della tesi se non viene
  richiesto esplicitamente dall'utente.
- Se una modifica richiesta è in conflitto con il PDF di riferimento, segnala
  il conflitto e chiedi conferma prima di procedere.

## Generazione LaTeX

- Genera tutti gli artefatti LaTeX nella directory `out/`.
- Non lasciare nella radice del repository file generati come `.aux`, `.log`,
  `.out`, `.toc` o PDF di compilazione.
- Per le compilazioni, usa una configurazione o opzioni che impostino `out/`
  come directory di output (ad esempio `latexmk -outdir=out tesi.tex`).
- Verifica la compilazione dopo modifiche che interessano il documento, salvo
  impossibilità tecnica da riportare chiaramente.

## Flusso di modifica e Git

1. Completa la modifica richiesta e svolgi le verifiche appropriate.
2. Riassumi con precisione cosa è stato modificato e chiedi all'utente se va
   bene.
3. Solo dopo una conferma esplicita dell'utente, crea un commit e fai push sul
   branch `main`.

Non eseguire commit o push prima dell'approvazione esplicita. Mantieni i commit
circoscritti alla modifica approvata ed evita di includere file generati in
`out/`, salvo richiesta esplicita dell'utente.
