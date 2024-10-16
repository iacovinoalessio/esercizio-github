# esercizio-github  # Push

## Cosa significa
La "push" è un'azione in cui invii le modifiche dal tuo repository locale a un repository remoto.

## Esempio di utilizzo
Quando hai finito di lavorare su una nuova feature, esegui il comando:

```bash
git push origin nome-branch
# Cos'è una Pull in Git

## Definizione
La "pull" è un comando in Git che consente di scaricare e integrare le modifiche da un repository remoto nel tuo repository locale. È essenziale per mantenere il tuo lavoro aggiornato con le ultime modifiche apportate da altri collaboratori.

## Funzionamento
Quando esegui un comando `git pull`, Git compie due operazioni:
1. **Fetch**: Recupera i dati dal repository remoto.
2. **Merge**: Integra questi dati nel tuo branch corrente.

## Comando
Per eseguire una pull, puoi utilizzare il seguente comando:

```bash
git pull origin nome-branch
