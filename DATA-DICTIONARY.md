# Data Dictionary (Starter)

## canonical-index/series.json
- series_id: stable identifier for a series
- title: series title
- canon: canon description
- version: dataset version

## canonical-index/books.json
- book_id: stable identifier for a book/volume
- series_id: parent series
- volume: integer volume number
- title: display title
- status: starter|draft|released
- version: dataset version

## canonical-index/passages.ndjson (per line)
- passage_id: stable passage identifier
- ref: human-readable reference
- themes: controlled vocab theme ids
- crossrefs: passage ids for cross reference
- version: dataset version