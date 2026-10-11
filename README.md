# Special Items

The 1953 centennial guest book and the 2003 “Our Heritage” 150th-anniversary booklet.

Part of the photographed records of the **San Francisco Ladies’ Protection and Relief Society** (Heritage on the Marina). Browse and search every series together at **https://sflprs.github.io**.

70 pages in 2 volumes (about 43 MB of images).

| Code | Volume | Pages | Dates found in text | Scanned from |
|---|---|---:|---|---|
| S1 | Centennial Guest Book 1953 | 13 | — | `Heritage Minutes Day 3/2025_03_10_09_43_15` |
| S2 | Our Heritage 1853–2003 | 57 | — | `Czur` |

## About each volume

- **S1 Centennial Guest Book 1953:** “Presented to the San Francisco Ladies Protection and Relief Society by Mrs. James W. Towne for the Hundredth Anniversary, April 18th 1953.” Signatures.
- **S2 Our Heritage 1853–2003:** “Our Heritage: The San Francisco Ladies’ Protection and Relief Society, 1853–2003, The First 150 Years” — the 150th-anniversary history booklet, scanned page by page.

## Folder layout

```
images/<volume>/   original photos, named <code>_<page>.jpg (e.g. S1_0001.jpg)
thumbs/<volume>/   small previews used by the viewer
text/<volume>/     machine-read (OCR) text of each page, same names, .txt
manifest.csv       one row per page: file names, original scan file, checksum, date found, notes
checksums-md5.txt  MD5 checksum of every image
```

Page numbers follow the order the photos were taken, which is not always the order of the book; some volumes were photographed newest-first or in two sessions (parts A and B in `manifest.csv`). The text is machine-read and contains errors; handwritten pages are not searchable.
