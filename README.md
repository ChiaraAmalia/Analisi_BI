# Analisi dataset relativo alle violenze commesse dalla polizia sul suolo americano

## Introduzione
Con la seguente relazione si intende illustrare l’analisi descrittiva e predittiva svolta su un dataset relativo alle violenze commesse dalla polizia nel territorio americano.

### Dataset
Il dataset che sarà analizzato più avanti nella trattazione è come detto in precedenza un dataset relativo alle violenze commesse dalla polizia nei confronti dei cittadini americani: [link](https://www.kaggle.com/datasets/jpmiller/police-violence-in-the-us)

Questo dataset è una raccolta di dati provenienti da diverse fonti riguardanti le violenze commesse dalla polizia negli Stati Uniti, tra il 2013 e il 2019. Si andranno ad analizzare vari aspetti, tra cui il più importante l’equità razziale, tema molto sensibile negli Stati Uniti. Nel complesso, in sette anni la polizia americana ha ucciso oltre 7.500 persone, ovvero in media 1.100 all’anno e circa 34 ogni 10 milioni di abitanti. Si tratta soltanto di una parte dei 15 mila e più omicidi commessi ogni anno negli Stati Uniti, ma comunque significa-tiva considerando che i poliziotti rappresentano una fetta molto piccola della popolazione.

<ol>
  <li><b>deaths_arrests.csv:</b>questo file contiene informazioni relative all’etnia della popolazione ameri-cana, al numero di persone uccise durante un arresto in un determinato arco temporale e varie medie ottenute da questi dati.</li>
  <li><b>fatal_encounters_dot_org.csv:</b>questo file contiene informazioni relative agli eventi con esito le-tale tra civili e forze dell’ordine, dove i civili hanno perso la vita.</li>
  <li><b>police_deaths_538.csv:</b>questo file contiene informazioni relative ai decessi degli agenti delle forze dell’ordine durante il servizio.</li>
  <li><b>police_killings_MPV.csv:</b>questo file contiene informazioni relative alle persone che sono morte durante una colluttazione con le forze dell’ordine. La differenza con il file precedente è che in questo file sono riportati solo gli eventi letali dovuti ad un intervento diretto delle forze dell’or-dine, nell’altro file consideriamo anche eventi indiretti, come ad esempio incidenti e suicidi.</li>
  <li><b>shootings_wash_post.csv:</b>questo file contiene un sottoinsieme delle informazioni presenti nel file <b>police_killings_MPV.csv</b>.</li>
</ol>

Al fine di preparare il dataset che sarà poi analizzato con i diversi tool di analisi, è risultato necessario mettere in atto una fase di ETL dei dati, articolata in tre fasi principali: Extract, Trasform, Load.

## Qlik
Nello specifico andremo ad utilizzare Qlik Sense, un software per la “Self-service Analytics”, il quale permette all’utente finale di realizzare analisi sui dati d’interesse, al fine di creare report personalizzati e dashboard dinamiche. 
In primis, all’interno dello spazio di lavoro condiviso, è stata creata un’applicazione in cui è presente una raccolta di elementi riutilizzabili, come dati (articolati in misure, dimensioni e visualizzazioni), fogli e racconti. Una volta caricato il dataset abbiamo deciso di effettuare una serie di analisi esplorative, con lo scopo di estrarre informazioni di interesse.

## Tableau
Questo software permette di creare e distribuire dashboard interattive e condivisibili, che rappresentano le tendenze e le conoscenze rilevate dai dati. Permette la fusione di dataset etero-genei e la centralizzazione dei dati. Consente inoltre di stabilire delle relazioni tra le tabelle del dataset effet-tivamente collegate, in modo da poter definire analisi più approfondite. Abbiamo un foglio di lavoro per ogni grafico mentre la dashboard può essere costituita dall’unione di più worksheet. Abbiamo deciso di suddividere le dashboard in relazione al tipo di file che stiamo analizzando, suddividendole in quattro tipologie di analisi.

## PowerBI
Questo software offre una serie di strumenti in grado di rappresentare i dati in maniera grafica ed intuitiva attraverso l’uso dei report, inoltre, mette a disposizione tutta una serie di grafici, utili per svolgere qualsiasi tipo di analisi, e per rappresentare i dati nel modo più corretto.Power BI offre una serie di strumenti aggiuntivi per la manipolazione dei dati attraverso l’editor di Power Query, da una parte, e l’uso di un linguaggio simile a quello utilizzato per Microsoft Excel, dall’altro. Tutte queste funzionalità gli permettono di essere molto utile anche in fase di ETL, inoltre, offre la possibilità di integrare script in R e Python, linguaggi molto utilizzati nell’ambito della data science che permettono di aumentare le funzionalità del software stesso.

## Tecnologie utilizzate
<ul>
  <li>Qlik</li>
  <li>Tableau</li>
  <li>PowerBI</li>
</ul>

Ulteriori dettagli relativi alle analisi effettuate sono riportati nella seguente [relazione](https://github.com/ChiaraAmalia/Analisi_BI/blob/main/Relazione_Qlik_Tableau_PowerBI.pdf)
