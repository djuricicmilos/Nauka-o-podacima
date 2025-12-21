# Insurance Premium Prediction

## Pregled projekta

Ovaj projekat predstavlja seminarski rad čiji je cilj analiza podataka i izgradnja regresionih modela za predikciju iznosa premije osiguranja (*Premium Amount*). Rad obuhvata kompletan proces rada sa podacima, od osnovnog opisa skupa podataka i eksplorativne analize, preko pretprocesiranja i feature engineering-a, do kreiranja i poređenja linearnih i nelinearnih modela.
Zbog veličine fajlova `train.csv` i `test.csv`, nismo u mogućnosti da izvršimo njihov upload. Trening i test skup mogu da se nađu na ovom [linku](https://www.kaggle.com/competitions/playground-series-s4e12/data). 

## Data description

U ovom poglavlju dat je osnovni pregled skupa podataka i njegovih atributa. Opisane su:
- numeričke i kategorijske promenljive,
- značenje i tip svakog atributa.

Cilj ovog dela je upoznavanje sa strukturom podataka i kontekstom problema.

## Data preparation

Faza pripreme podataka obuhvata osnovne transformacije neophodne za dalju analizu. U okviru ove faze izvršene su:
- konverzije promenljivih tipa `character` u kategorijske promenljive,
- zamena praznih stringova nedostajućim vrednostima (`NA`),
- osnovna provera konzistentnosti i ispravnosti podataka.

## Data analysis

Eksplorativna analiza podataka sprovedena je u više koraka:
- **univarijantna analiza** kategorijskih i numeričkih promenljivih,
- **bivarijantna analiza** odnosa:
  - kategorijska – kategorijska,
  - kategorijska – ciljna promenljiva,
  - kategorijska – numerička,
  - numerička – numerička.

Analiza uključuje deskriptivnu statistiku, statističke testove i odgovarajuće grafičke prikaze radi identifikacije obrazaca i zavisnosti u podacima.

## Data preprocessing

U fazi pretprocesiranja podataka izvršeni su postupci neophodni za uspešno modeliranje:
- obrada nedostajućih vrednosti,
- detekcija i obrada anomalija,
- kreiranje novih atributa (feature engineering),
- transformacije i skaliranje numeričkih promenljivih.

Ova faza ima za cilj poboljšanje kvaliteta ulaznih podataka.


## Model selection

U završnoj fazi rada kreirani su i evaluirani različiti modeli. Razmatrani su:
- linearni modeli kao referentni (baseline),
- nelinearni modeli mašinskog učenja.

Modeli su upoređeni na osnovu RMSE metrike, a izabran je model sa najboljim performansama za predikciju iznosa premije osiguranja.

## Autori

- Miloš Đuričić
- Jana Brzaković  
