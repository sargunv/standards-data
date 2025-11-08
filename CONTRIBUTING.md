# Keeping the data up-to-date

## Updating country codes

Head to the
[ISO currency codes collection](https://www.iso.org/obp/ui/#search/code/), copy
the table, and paste it into a spreadsheet editor capable of exporting to CSV.
Google Sheets works well.

## Updating currency codes

```sh
mise install
mise run update-currency-codes
```
