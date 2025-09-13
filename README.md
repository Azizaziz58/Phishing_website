# Phishing_website
PWD-main is a core module of the Phishing Website Detection project. It implements the logic and infrastructure to:

Analyze website URLs using a machine learning model to classify them as legitimate or phishing.

Extract domain metadata (registration age, registrar, expiration, registration country, etc.).

Validate URL security (HTTPS vs HTTP).

Provide confidence scores for predictions.

Store and manage scan history.

🔧 Features

Zero-shot classification using a transformer-based NLP model (e.g. facebook/bart-large-mnli)

WHOIS domain lookup for domain age & registrar info

Protocol security check (HTTP/HTTPS)

Visualization (confidence metrics, possibly pie charts)

Data export / history tracking

⚙️ Getting Started

Install dependencies via requirements.txt

Configure any API keys or WHOIS settings if needed

Run application (e.g. python main.py or via a web front-end framework)

Input URL(s), view classification, metadata, and export results

🎯 Intended Use & Limitations

For educational and experimental use; not a guarantee of security in production

Performance depends on model quality and domain registration availability

May not detect very new phishing sites without sufficient data
