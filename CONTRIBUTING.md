# Keeping the data up-to-date

## Updating country codes

This one is a manual process. Head to the
[ISO currency codes collection](https://www.iso.org/obp/ui/#search/code/), copy
the table, and paste it into a spreadsheet editor capable of exporting to CSV.
Google Sheets works well.

## Updating currency codes

See the [`update-currency-codes`](./mise-tasks/update-currency-codes) script.

```sh
mise install
mise run update-currency-codes
```

## Updating language codes

See the [`update-language-codes`](./mise-tasks/update-language-codes) script.

```sh
mise install
mise run update-language-codes
```
