# Agenti che non dormono: il tuo sistema

Questo è il modello del corso "Agenti che non dormono" di AlleniamoImprese.
Da qui crei il tuo repository: la cartella dove vive il tuo sistema, con le
regole per Claude, il lavoro che ripeti e quello che produce.

## Come si usa

1. In alto a destra clicca **Use this template**, poi **Create a new
   repository**.
2. Nome: `agenti`, o quello che preferisci. Visibilità: **Private**.
3. Nel tuo repository apri `LAVORO.md` e descrivi il tuo lavoro ricorrente.

Il resto lo facciamo insieme nelle live.

## Cosa c'è dentro

| File o cartella | A cosa serve |
|---|---|
| `CLAUDE.md` | Le regole che Claude legge ogni volta che lavora qui |
| `AGENTS.md` | Le stesse regole, per chi usa Codex |
| `LAVORO.md` | Il tuo lavoro ricorrente, scritto da te |
| `STATO.md` | Dove Claude annota cosa ha fatto e da dove ripartire |
| `da-leggere/` | Dove metti i testi che Claude deve leggere |
| `uscite/` | Dove Claude lascia i risultati, un file per volta con la data |

## La routine della prima live

Su claude.ai/code/routines crei una routine su questo repository. Il testo da
incollare nel campo delle istruzioni:

```text
Esegui il lavoro descritto in LAVORO.md, seguendo le regole di CLAUDE.md.
Alla fine aggiorna STATO.md, poi fai commit e push sul branch main.
```
