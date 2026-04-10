# Codice sconto YOOX Italia, recupero automatico da shopilo.it

Modulo Python per il recupero automatico di **codici sconto YOOX Italia** da [shopilo.it](https://shopilo.it/negozi/yoox.it). Restituisce **coupon YOOX Italia** attivi in formato JSON, pronto per l'integrazione in un bot Telegram, estensione del browser o qualsiasi altro strumento.

**Pagina live:** [shopilo-it.github.io/codice-sconto-yoox-it](https://shopilo-it.github.io/codice-sconto-yoox-it/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Installazione

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-it/codice-sconto-yoox-it
cd codice-sconto-yoox-it
python fetch.py
```

## Output di esempio

```json
[
  {
    "store": "YOOX Italia",
    "code": "SHOPILO20",
    "discount": "20%",
    "description": "20% di sconto su brand premium italiani",
    "expires": "2026-10-10",
    "source": "https://shopilo.it/negozi/yoox.it"
  }
]
```

## Coupon YOOX Italia disponibili

| Sconto | Descrizione | Fonte |
|----------|-----------|-------|
| 20% | 20% di sconto su brand premium italiani | [shopilo.it](https://shopilo.it/negozi/yoox.it) |

Codici attivi: **[shopilo.it/negozi/yoox.it](https://shopilo.it/negozi/yoox.it)**

## Domande frequenti

### Come utilizzo un codice sconto YOOX Italia?
Copia il codice dalla tabella qui sopra o da [shopilo.it](https://shopilo.it/negozi/yoox.it), aggiungi i prodotti al carrello su YOOX Italia e inserisci il codice al checkout nel campo dedicato.

### Quanto durano i coupon YOOX Italia?
Ogni coupon ha una data di scadenza indicata nella colonna "Scadenza". Lo script fetch.py restituisce solo i coupon attivi al momento dell'esecuzione.

### Dove trovo i voucher YOOX Italia piu recenti?
La pagina [shopilo.it/negozi/yoox.it](https://shopilo.it/negozi/yoox.it) viene aggiornata quotidianamente con i codici sconto YOOX Italia, voucher YOOX Italia e coupon promozionali YOOX Italia piu recenti.

### Il codice non funziona. Cosa faccio?
Verifica la data di scadenza e le condizioni (importo minimo del carrello, prodotti idonei). Alcuni codici sono validi solo nell'app mobile o per il primo ordine.

## Informazioni su YOOX Italia

YOOX Italia e uno dei negozi online piu popolari. Su [shopilo.it](https://shopilo.it/negozi/yoox.it) trovi i migliori codici sconto YOOX Italia, coupon YOOX Italia verificati e voucher YOOX Italia attivi, aggiornati ogni giorno.

## Installazione npm

```bash
npm install codice-sconto-yoox-it
```

```javascript
const { fetchCoupons } = require('codice-sconto-yoox-it');
fetchCoupons().then(data => console.log(data));
```

## Licenza

MIT, dati prelevati da [shopilo.it](https://shopilo.it)
