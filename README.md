**Amazon India Sales: Data Auditing & Exploration**

Questo progetto nasce dalla curiosità di analizzare un dataset reale e complesso (oltre 120.000 transazioni) per capire come si muovono le vendite di un e-commerce in un mercato come quello indiano.

L'obiettivo non è stata solo la semplice visualizzazione, ma un vero e proprio lavoro di Data Auditing: capire dove i dati "mentono" e come pulirli per ottenere informazioni affidabili.

**Dati**

I dati utilizzati per questa analisi provengono da un file CSV contenente informazioni sugli ordini di vendita, preso da Kaggle e chiamato Ecommerce Sales Dataset, riguardante le vendite di Amazon (link: https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data/discussion?sort=hotness)

**Analisi**

Il progetto si concentra su:

- Investigazione degli "Ordini Nulli": Ho notato la presenza di ordini con importo 0.0 e ho cercato di capire se si trattasse di errori di sistema, resi o promozioni particolari (Amazon Promotions vs VPC Coupon).

- Gestione degli Outlier: Per evitare che i "prezzi anomali" sballassero le medie del fatturato, ho applicato tecniche statistiche come il metodo Interquartile (IQR) e lo Z-Score (IQR e Z-Score per il confronto della distribuzione prima e dopo il cleaning).

- Business Insights: Ho studiato come le diverse categorie (Kurta, Set, Western Dress) interagiscono tra loro, notando ad esempio fenomeni di cannibalizzazione tra i prodotti più venduti.

**Librerie e Sviluppi Futuri**

Tech Stack: Python (Pandas, NumPy), Seaborn, Matplotlib.

Limiti attuali: Alcune visualizzazioni le sistemerò.

Next Step: Questo lavoro è la base esplorativa per un futuro modello predittivo basato su regressione lineare per stimare le vendite dei mesi successivi.
