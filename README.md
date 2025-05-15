# The Football Lab: Predicting Player Impact by Position

Questo progetto analizza statisticamente i dati dei calciatori delle principali leghe europee nelle stagioni 2021-2022 e 2022-2023, con l'obiettivo di prevedere l'impatto dei giocatori in base al ruolo.

## Link ai datasets
21-22 dataset: https://www.kaggle.com/datasets/vivovinco/20212022-football-player-stats
22-23 dataset: https://www.kaggle.com/datasets/vivovinco/20222023-football-player-stats?resource=download

## Contenuti

- **Pulizia e strutturazione dei dati:**  
  Importazione, normalizzazione e selezione delle colonne rilevanti dai dataset originali.

- **Analisi Esplorativa:**  
  Visualizzazione della distribuzione dei minuti giocati e assist per ruolo.

- **OLAP:**  
  Analisi multidimensionale delle statistiche (es. assist, età, minuti) tramite cubi OLAP.

- **Test Statistici:**  
  Confronto tra le medie di assist e goal tra diverse competizioni tramite t-test.

- **Modellazione Predittiva:**  
  Addestramento di modelli di regressione lineare per prevedere goal (attaccanti), assist (centrocampisti) e contrasti vinti (difensori).

## Come usare il notebook

1. Assicurati di avere i file CSV nella cartella `datasets/` all'interno dello stesso folder del [notebook.ipynb]
2. Apri [notebook.ipynb] in Jupyter o Visual Studio Code.
3. Esegui le celle in ordine per riprodurre l'analisi e le visualizzazioni.

## Requisiti

- Python 3.x
- pandas
- numpy
- matplotlib
- scipy
- scikit-learn

## Autori
Mammoliti Marco 5564736
Pedullà Filippo 5575626
