# Agoo Successive-Intersections — Supporting Data (Appendices E and F)

Two study data tables transcribed from the authors' supplied 110-page supporting PDF (`Appendix_D_Data_Tables (1)(1).pdf`).

| Thesis appendix | Files | Records | Description |
|---|---|---:|---|
| E — Automated GitHub Logger Dataset | `Appendix_E_GitHub_Logger_D11.csv`, `.xlsx` | 5,796 | Printed Table D11: Google Directions road-segment travel times and modeled traffic variables |
| F — 7-day Manual Observations | `Appendix_F_Manual_Counts_D1.csv`, `.xlsx` | 830 | Printed Table D1: manual movement counts at intersections I1–I4 (Sept 17–23, 2026) |

**Provenance:** These are structured extractions of the printed tables. They are **not the original unrounded GitHub API/logger file**, nor the original seven Excel counting workbooks. For reproducibility, the original native exports should be retained if available. No numerical entries from the printed tables were intentionally changed.

**Appendix E audit:** 23 segment IDs, 252 records per segment, and 21 represented dates in September 2026. The printed data contain no rows for September 6. Reported TTI, speed, density, and flow preserve their printed precision.

**Appendix F audit:** 830 movement-level rows over seven dates (Sept 17–23, 2026); all rows parse cleanly, and each record's vehicle-class counts sum to its reported total. The original printed `MM-DD` dates and intervals are retained; all records are from 2026.

To link a particular file in a printed thesis, open the corresponding CSV on GitHub and use its permanent commit link (press `Y` when viewing the file), then create a QR code for that URL. Keep E and F as separate links or QR codes beneath the appropriate appendix chapter titles.

## Original data fields
- **E:** Date, Time, Segment, Len (m), Typ. (s), Obs. (s), TTI, Speed, Dens., Flow, Peak.
- **F:** Int., Date, Slot, Movement, Tric., Car, Moto., Bus, Truck, Total.
