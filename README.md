# Bitcoin & News Sentiment

Progetto veloce per esplorare se il sentiment delle notizie su Bitcoin può dire qualcosa sull’andamento del prezzo il giorno dopo. Spoiler: poco, ma qualcosa si muove.

## 🧠 Cosa c’è dentro

* Analisi giornaliera del sentiment (polarity, subjectivity, numero di notizie)
* Dati di prezzo da Yahoo Finance (BTC-USD)
* Regressione lineare e test di Granger per capire se il sentiment "anticipa" il mercato

## 📦 Dataset

* Notizie: [Crypto News Dataset su Kaggle](https://www.kaggle.com/datasets/oliviervha/crypto-news) (grazie a **OLIVERVHA** per averlo condiviso)
* Prezzo BTC: via `yfinance`

## ⚙️ Tool usati

Python, Pandas, yfinance, matplotlib, seaborn, scikit-learn, statsmodels, kagglehub

## 👤 Autore

Alessandro Zucchiatti – Progetto per il corso di Fondamenti di Analisi Dati

## 📝 Licenza

MIT
