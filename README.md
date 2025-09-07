# La Consistenza dell'Aritmetica di Peano

Questa tesi di laurea triennale ripercorre la celebre dimostrazione di Gerhard Gentzen sulla consistenza dell'Aritmetica di Peano. Partendo da una formalizzazione della teoria tramite il Calcolo dei Sequenti, il lavoro esplora il nucleo della prova. Dimostrare la consistenza, in questa ottica, equivale a mostrare l'impossibilità di derivare una contraddizione (il sequente vuoto) a partire dagli assiomi dell'aritmetica, usando unicamente le regole di inferenza permesse. L'argomentazione procede per assurdo, basandosi sull'induzione transfinita: a ogni dimostrazione viene associato un ordinale e si mostra come un'ipotetica prova della contraddizione possa essere ridotta indefinitamente, generando una sequenza infinita e decrescente di ordinali. Questo contraddice il Teorema di Accessibilità, la cui dimostrazione è qui presentata in una rielaborazione personale, garantendo così la consistenza del sistema.

Questo approfondimento, condotto partendo da zero e in completa autonomia su un argomento non previsto dal piano di studi, è stato reso possibile dalla fiducia e dal prezioso supporto metodologico del mio relatore.


## Struttura del Repository

Questo repository contiene l'intero progetto LaTeX utilizzato per la stesura della tesi che, per comodità di gestione, è stata suddivisa in più cartelle. Segue una descrizione di file e cartelle per una facile consultazione.


### File Principali

* **`main.tex`**: file sorgente principale del progetto, ha il solo scopo di unire i vari contenuti.
* **`La Consistenza dell'Aritmetica di Peano.pdf`**: Il file PDF compilato e pronto per la lettura.
* **`Abstract.pdf`**: un breve riassunto in inglese del contenuto della tesi.

### Comandi

* **`comandi.tex`**: file di pacchetti, comandi e impostazioni.

### Frontmatter

* **`intro.tex`**: la premessa della tesi.
* **`titlepage.tex`**: la copertina.

### Mainmatter

* **`chapter1.tex`**: contenuto del primo capitolo.
* **`chapter2.tex`**: contenuto del secondo capitolo.
* **`equazione1.tex`**: una parte di codice che ho preferito gestire a parte (approccio poi abbandonato).

### Backmatter

* **`bibliografia.tex`**: la bibliografia.


### Immagini

* Contiene esclusivamente il logo dell'università, inserita solo per completezza.

---

*Questo lavoro è distribuito con la licenza [Creative Commons BY - NC - ND 4.0 Internazionale](LICENSE).*
