
## Run it
```bash
python -m venv venv
venv\Scripts\activate          # Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
python -m src.pipeline
pytest -v
```

## Folders
| Folder | What it holds | In Git? |
|---|---|---|
| `data/raw` | original data exactly as received | no |
| `data/sample` | tiny example data for tests and CI | yes |
| `data/processed` | pipeline output | no |
| `src` | pipeline code | yes |
| `tests` | pytest tests | yes |
| `notebooks` | exploration | yes |
| `workflows-to-add` | workflow files to move into `.github/workflows/` during the practice | yes |
