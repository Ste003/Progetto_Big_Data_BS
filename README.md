#  Progetto Big Data - Analisi dei Dati sull'Abalone

## Descrizione del Progetto
Questo progetto ha l'obiettivo di analizzare i dati relativi all'abalone e di prevederne l'età basandosi su misurazioni fisiche. La determinazione dell'età di un abalone viene tradizionalmente effettuata contando gli anelli della sua conchiglia, un processo laborioso e dispendioso in termini di tempo. Attraverso tecniche di analisi dei dati e machine learning, questo progetto mira a stimare l'età dell'abalone utilizzando misurazioni più semplici da ottenere.

## Dati Utilizzati
I dati contengono informazioni fisiche sugli abaloni. Tuttavia, si noti che le unità di misura riportate nel dataset sono errate.

### Attributi del Dataset
| Nome | Descrizione |
|------|------------|
| Sex | Sesso dell'abalone: M (Maschio), F (Femmina) e I (Infant - Giovane) |
| Length | Lunghezza della conchiglia (unità errata) |
| Diameter | Diametro perpendicolare alla lunghezza (unità errata) |
| Height | Altezza con la carne all'interno (unità errata) |
| Whole weight | Peso totale dell'abalone (unità errata) |
| Shucked weight | Peso della carne (unità errata) |
| Viscera weight | Peso delle viscere (unità errata) |
| Shell weight | Peso del guscio dopo l'essiccazione (unità errata) |
| Rings | Numero di anelli della conchiglia (+1.5 corrisponde all'età in anni) |

## Obiettivi
- Analizzare la distribuzione dei dati e le correlazioni tra le variabili.
- Correggere le unità di misura errate se possibile.
- Sviluppare un modello predittivo per stimare l'età degli abaloni.
- Valutare la performance del modello con metriche adeguate.

## Struttura del Progetto
- **Abalone.ipynb**: Notebook Jupyter contenente l'analisi esplorativa dei dati, la preparazione dei dati e l'addestramento del modello.
- **abalone_readme.txt**: Documento originale contenente la descrizione dei dati (con unità errate).

## Tecnologie Utilizzate
- Python
- Pandas, NumPy per la gestione e manipolazione dei dati
- Matplotlib, Seaborn per la visualizzazione
- Scikit-learn per la modellazione predittiva

## Note Finali
- Le unità di misura presenti nel dataset sono errate e dovrebbero essere verificate prima di qualsiasi ulteriore analisi.
- Il progetto potrebbe essere esteso considerando fattori esterni come condizioni meteorologiche e disponibilità di cibo per migliorare la previsione dell'età dell'abalone.

