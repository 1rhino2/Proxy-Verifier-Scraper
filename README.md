# Proxy-Verifier-Scraper

Scrapes public proxy lists, checks which ones actually work, and writes the live
ones to `working.txt`. Pure Python, standard library only.

## Run

```bash
python main.py
```

`scraper.py` grabs the lists, `verifier.py` tests them, `main.py` runs both.

## License

MIT
