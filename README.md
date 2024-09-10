# AI News Scraper

Een Python-tool voor het scrapen en aggregeren van AI-gerelateerd nieuws van verschillende bronnen.

## Functies

- Scrapt AI-nieuws van een grote verscheidenheid aan bronnen
- Filtert artikelen op AI-gerelateerde inhoud
- Genereert een HTML-nieuwsbrief van de verzamelde artikelen

## Vereisten

- Python 3.7+
- Benodige Python-bibliotheken:
  - requests
  - beautifulsoup4
  - newspaper3k
  - pandas
  - nltk
  - pytz

## Installatie

1. Clone de repository:
   ```
   git clone https://github.com/jouw-gebruikersnaam/ai-news-scraper.git
   ```
2. Installeer de vereiste pakketten:
   ```
   pip install -r requirements.txt
   ```

## Gebruik

1. Run de scraper:
   ```python
   python scraper.py
   ```
2. Genereer een nieuwsbrief:
   ```python
   python generate_newsletter.py
   ```

## Configuratie

Pas de lijst van te scrapen websites aan in `websites.py`.

## Bijdragen

Bijdragen zijn welkom! Zie `CONTRIBUTING.md` voor details.

## Licentie

Dit project is gelicentieerd onder de MIT-licentie. Zie `LICENSE` voor details.
