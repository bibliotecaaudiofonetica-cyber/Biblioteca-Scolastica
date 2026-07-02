python setup_admin.py
==================================================
  Setup password admin — Biblioteca Scolastica
==================================================

Inserisci la password admin: Audio2026!

✅ Aggiungi queste variabili d'ambiente al tuo sistema o file .env:

BIBLIOTECA_SECRET="4ac135a9f44a134131ff66d015dd5cf68e4bed83b2d9e6021a16266c2297b32f"
BIBLIOTECA_ADMIN_HASH="$2b$12$xERp8z91Je9qWnV5lRL3hOM1h/p6PoDQ.ZkpR60dcRvzzzBVxdUhW"

Esempio con .env (richiede python-dotenv):
  Crea un file .env nella cartella backend/ con il contenuto sopra.
  Poi aggiungi all'inizio di main.py:
    from dotenv import load_dotenv; load_dotenv()

⚠️  Non committare mai il file .env nel repository!