# Changelog

## 2026-09-14

- **Added** `amana_exchange_rates` (GET `amanabank.lk/business/treasury/exchange-rates.html`)
- **Changed** `amana_rates`
- **Changed** `cargills_bank_rates`
- **Changed** `union_bank_offers`

Automated from `catalog/endpoints.yaml` via `scripts/update-api-catalog-changelog.py` (and `.github/workflows/catalog-changelog.yml` after extraction).

## 2026-07-20

- **Bootstrap** catalog fingerprint (3 endpoints).
- Listed `amana_rates` — GET `amanabank.lk/rates/` · access `html_scrape`
- Listed `cargills_bank_rates` — GET `cargillsbank.com/rates-and-tariffs/` · access `html_scrape`
- Listed `union_bank_offers` — GET `unionb.com/.../offers` · access `html_scrape`
