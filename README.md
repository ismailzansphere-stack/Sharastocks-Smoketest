# Sharastocks Smoke Test

Selenium smoke tests for the ShariaStocks website.

## Configuration

Set `TEST_USER_EMAIL` and `TEST_USER_PASSWORD` in your local environment before running the login smoke test. Never commit real credentials or `.env` files.

ReportPortal is enabled by the pytest configuration. Supply its API key locally with pytest's `--rp-api-key` option, for example in PowerShell:

```powershell
$env:RP_API_KEY = "your-local-key"
pytest --rp-api-key $env:RP_API_KEY
```

The repository intentionally contains no working credentials or API keys.
