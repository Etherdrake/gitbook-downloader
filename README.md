# GitBook Downloader

Universal GitBook downloader that works with any GitBook site using multiple fallback strategies (GitHub cloning, sitemap parsing, web scraping).

## Quick Start

```bash
pip3 install -r requirements.txt
python3 main.py https://docs.example.com -o docs.md
```

## Options

| Option | Description |
|--------|-------------|
| `--strategy` | Strategy: auto/github/sitemap/scraping |
| `--include-assets` | Download images and assets |
| `--section-path` | Download specific section only |
| `--verbose` | Enable detailed logging |
