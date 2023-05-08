# PotableWaterItaly2018-Analysis
- [Italiano](#italiano)
- [English](#english)



<a name="italiano"></a>
# PotableWaterItaly2018-Analysis (Italiano)

## Descrizione del progetto

Progetto in R realizzato per il corso di Calcolo delle Probabilità e Statistica Matematica presso l'Università degli Studi di Salerno. Il progetto analizza un dataset riguardante l'erogazione e immissione di acqua potabile nei comuni di Napoli (Italia) nel 2018. Viene eseguita un'analisi statistica sulle quantità di acqua erogata dai comuni, calcolando vari indici di posizione, variabilità e forma. Inoltre, vengono prodotti grafici per visualizzare le distribuzioni e le relazioni tra i dati.

Hanno contribuito a questo progetto:
* [D'Antuono Francesco Paolo](https://github.com/CpDant)
* [Vitale Ciro](https://github.com/cirovitale)

## Struttura del progetto
Il progetto si articola nelle seguenti sezioni:
1.  Caricamento delle librerie
2.  Importazione del dataset e selezione dati opportuni
3.  Selezione di un campione unidimensionale con tabella delle frequenze assolute e relative su di esso
4.  Calcolo indici di posizione, variabilità e forma
5.  Raggruppamento in classi con calcolo frequenze assolute e relative
6.  Quartili, scarto interquartile e boxplot
7.  Intervalli di previsione
8.  Dati bivariati e coefficiente di correlazione campionario

## Dataset
Il dataset utilizzato (acqua.csv) è stato scaricato da istat.it e riguarda l'erogazione e immissione di acqua potabile nei comuni nel 2018.

## Librerie utilizzate
-   readxl
-   tidyverse

## File
-   `.RData`: File di dati R contenente oggetti salvati.
-   `.Rhistory`: File di cronologia delle operazioni eseguite in R.
-   `acqua.csv`: Dataset utilizzato per l'analisi.
-   `progetto_stats.html`: File HTML contenente i risultati dell'analisi.
-   `progetto_stats.Rmd`: File R Markdown contenente il codice sorgente e la descrizione dell'analisi.

## Requisiti
Per eseguire il codice, è necessario avere installato R e le librerie readxl e tidyverse.

## Esecuzione
Per eseguire il progetto, aprire il file `progetto_stats.Rmd` in RStudio e fare clic su "Run All" per eseguire tutte le sezioni. In alternativa, è possibile visualizzare direttamente i risultati aprendo il file `progetto_stats.html` nel browser.



<a name="english"></a>
# PotableWaterItaly2018-Analysis (English)

## Project Description

R project developed for the Probability Calculus and Mathematical Statistics course at the University of Salerno. The project analyzes a dataset concerning the supply and distribution of potable water in municipalities of Naples (Italy) in 2018. It performs a statistical analysis on the quantities of water supplied by the municipalities, calculating various indices of position, variability, and shape. In addition, it produces graphics to visualize distributions and relationships among the data.

Contributors to this project:

-   [D'Antuono Francesco Paolo](https://github.com/CpDant)
-   [Vitale Ciro](https://github.com/cirovitale)

## Project Structure

The project is divided into the following sections:

1.  Loading libraries
2.  Importing the dataset and selecting appropriate data
3.  Selecting a one-dimensional sample with a table of absolute and relative frequencies on it
4.  Calculating indices of position, variability, and shape
5.  Grouping into classes with calculation of absolute and relative frequencies
6.  Quartiles, interquartile range, and boxplot
7.  Forecast intervals
8.  Bivariate data and sample correlation coefficient

## Dataset

The dataset used (acqua.csv) was downloaded from istat.it and concerns the supply and distribution of drinking water in municipalities in 2018.

## Libraries Used

-   readxl
-   tidyverse

## Files

-   `.RData`: R data file containing saved objects.
-   `.Rhistory`: R history file of operations performed in R.
-   `acqua.csv`: Dataset used for the analysis.
-   `progetto_stats.html`: HTML file containing the results of the analysis.
-   `progetto_stats.Rmd`: R Markdown file containing the source code and description of the analysis.

## Requirements

To run the code, you need to have R and the readxl and tidyverse libraries installed.

## Execution

To run the project, open the `progetto_stats.Rmd` file in RStudio and click on "Run All" to execute all sections. Alternatively, you can directly view the results by opening the `progetto_stats.html` file in your browser.
