# Kafka: streaming data
## Motivazioni
Negli ultimi anni l'avvento delle architetture a microservizi ha portato la necessità di studiare nuove soluzioni al problema della gestione di molteplici fonti di dati.

In sistemi complessi formati da più microservizi tanti componenti interdipendenti comunicano tra loro scambiandosi dati e attingendo da numerose fonti di dati comuni come database, data warehouses oppure servizi esterni.

La necessità di filtrare, standardizzare e gestire molte fonti di dati aveva portato alla nascita del processo di **Extract, Transform, Load** (ETL) per l'estrazione, trasformazione e caricamento di dati in sistemi di sintesi come data warehouse o data mart, questo processo si sta però rivelando complicato ed impegnativo in un mondo dove la mole di dati prodotta dal logging di eventi critici ad un qualsiasi business è in continua crescita: semplici esempi sono la gestione degli eventi in un sistema **IoT** (*Internet of things*) oppure lo studio delle abitudini dei propri clienti per un servizio di e-commerce.

Lo stream processing tra microservizi propone un nuovo approccio per la gestione di questi problemi, fornendo una soluzione adatta alla gestione di dati in real-time altamente scalabile e ad high  throughput.

## Introduzione: Il ruolo dello streaming nelle architetture moderne
### ETL
  >Cos'è un processo di etl

  Un processo di Extract, Transform, Load (ETL) è un processo mirato alla trasformazione di dati contenuti su più database per ottenere un nuovo insieme di dati, filtrato e traformato secondo una particolare logica, destinato ad essere salvato in una data warehouse.  
  Verso la fine degli anni '70 molte aziende iniziarono a ad utilizzare molteplici database per salvare e gestire informazioni vitali al loro business, ed è proprio in questo contesto che nascono i processi di ETL: con l'avanzare del tempo è stato necessario studiare un metodo per l'aggregazione delle varie fonti di dati.
  > Extract

  > Transform

  > Load

  >In che ambiti viene usato

### Event sourcing
  >Cos'è event sourcing

  >Esempio di utilizzo di event sourcing

  >Problemi risolti da event sourcing

  
### Svantaggi di un processo ETL rispetto a streaming

## L'importanza dei dati 
  > Perchè la gestione dei dati è importante nelle architetture a microservizi


## Apache Kafka e l'ecosistema
### Cos'è - come funziona: Log
  > Struttura di base: log  => log compaction

  >Struttura architetturale:  
    >- brokers  
    >- clusters  
    >- topic  

  >Come collegare event sourcing e kafka => perchè kafka è una buona piattaforma per event sourcing
### APIs
#### Kafka Connect
  Source connectors
  Sink connectors
  Community involment
#### Kafka Streams
  cos'è streams
  KSQL/LSQL

## Esempi


## Bibliografia
https://www.confluent.io/blog/data-dichotomy-rethinking-the-way-we-treat-data-and-services/
https://www.confluent.io/blog/build-services-backbone-events/
https://www.confluent.io/blog/apache-kafka-for-service-architectures/
https://www.confluent.io/blog/messaging-single-source-truth/
https://www.confluent.io/blog/building-a-microservices-ecosystem-with-kafka-streams-and-ksql/
https://content.pivotal.io/blog/understanding-when-to-use-rabbitmq-or-apache-kafka
https://qconsf.com/sf2016/system/files/keynotes-slides/etl_is_dead_long-live_streams.pdf <= https://www.youtube.com/watch?v=I32hmY4diFY




