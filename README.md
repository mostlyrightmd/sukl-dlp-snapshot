# SÚKL DLP snapshot (release DLP20260925)

Unzipped copy of the Czech State Institute for Drug Control (SÚKL) open-data release
"Databáze léčivých přípravků (DLP)", published 25 September 2026 and valid for
1 to 31 October 2026 (`dlp_platnost.csv`).

**Source of the data: SÚKL (Státní ústav pro kontrolu léčiv), https://opendata.sukl.gov.cz**
This copy is not produced, endorsed or supported by SÚKL.

- Catalogue page: https://opendata.sukl.gov.cz/?q=katalog/databaze-lecivych-pripravku-dlp
- Archive: https://opendata.sukl.cz/soubory/SOD20260925/DLP20260925.zip
  (sha256 `4b5e646aa9fb62eb99002226af4a0a8cff0d66992c28646df4fd80fa4e76a0c2`, 9,529,608 bytes, downloaded 2026-10-07)
- Data dictionary: https://opendata.sukl.cz/soubory/DLP_datove_rozhrani20260701.csv
  (sha256 `cd1f0d1893796b7aea2b137325c4931e9049cf19d327b400264a955ea63f717f`)
- Terms of use (these apply to any further distribution): https://opendata.sukl.gov.cz/?q=podminky-uziti-otevrenych-dat

## What is here

`DLP20260925/` holds the 30 CSV members of the archive exactly as published: the bytes are
unchanged (Windows-1250 text, semicolon-delimited, CRLF records). `DLP20260925/dlp_datove_rozhrani.csv`
is the data dictionary file, also unchanged apart from its file name. `SHA256SUMS` lists every file;
each member's digest equals the digest of the same member inside the archive. `MANIFEST.json`
lists row and column counts per file.

Steps taken: download the archive, `unzip`, copy. Nothing was re-encoded, edited, filtered or added.

This is a fixed copy of one monthly release. It does not update. Take current data from SÚKL.

## Terms of use (summary of the SÚKL terms linked above)

SÚKL allows users to copy, distribute, communicate to the public, use, cite and commercially use
the open data, provided that SÚKL is named as the source (without suggesting that SÚKL endorses the
user or the use) and that the data are not used in a way that changes or alters their meaning.
Anyone distributing the data further must state these terms, preferably by linking to the page above.
The terms do not apply to documents covered by third-party intellectual property rights.
