- PASS: PDF count: 66
- PASS: Word count: 66
- PASS: all 66 expected PDF file names present
- PASS: all 66 expected Word file names present
- PASS: all 66 Word files open and contain document.xml
- PASS: all 66 PDFs open (pdfinfo)
- PASS: no other-state names or 'County Clerk'/'Election Commissioner' titles in any of the 66 PDFs
- PASS: required framing, addressee, statutes, and equipment string present in all 66 PDFs
- PASS: every printed share, gap, ΔG, registration change, and statewide total in all 66 PDFs matches the raw-source recompute

## Ten-county spot check against raw SOS figures
- PASS: Minnehaha: Auditor Leah Anderson, 415 N Dakota Ave, Sioux Falls, SD 57104-2465; ballot share 44.17% → 46.40%; reg share 28.22% → 24.83%; gap +15.95 → +21.57; ΔG +5.62; Dem reg 36,920 → 34,549; Dem votes 33,376 → 31,521; ballots 75,570 → 67,931; tabulator ES&S DS850 (Batch-Fed Optical Scanner)
- PASS: Pennington: Auditor Sabrina Green, PO Box 6160, Rapid City, SD 57709; ballot share 35.28% → 35.70%; reg share 20.82% → 18.73%; gap +14.47 → +16.96; ΔG +2.50; Dem reg 17,964 → 16,805; Dem votes 16,215 → 13,861; ballots 45,958 → 38,829; tabulator ES&S DS850 (Batch-Fed Optical Scanner)
- PASS: Lincoln: Auditor Sheri Lund, 104 N Main, Ste 110, Canton, SD 57013-1703; ballot share 37.66% → 38.65%; reg share 22.30% → 19.37%; gap +15.36 → +19.28; ΔG +3.92; Dem reg 9,865 → 10,015; Dem votes 10,727 → 10,292; ballots 28,483 → 26,628; tabulator ES&S DS850 (Batch-Fed Optical Scanner)
- PASS: Brookings: Auditor Jennifer Beller, 520 3rd St., Suite 100, Brookings, SD 57006; ballot share 40.43% → 40.16%; reg share 25.46% → 21.96%; gap +14.97 → +18.20; ΔG +3.24; Dem reg 5,166 → 4,854; Dem votes 5,096 → 4,681; ballots 12,606 → 11,655; tabulator ES&S DS850 (Batch-Fed Optical Scanner)
- PASS: Oglala Lakota: Auditor Sue Ganje, 906 N River St, Hot Springs, SD 57747-1398; ballot share 85.95% → 84.04%; reg share 67.24% → 64.51%; gap +18.71 → +19.53; ΔG +0.82; Dem reg 5,360 → 5,060; Dem votes 2,172 → 1,901; ballots 2,527 → 2,262; tabulator ES&S DS450 (Batch-Fed Optical Scanner)
- PASS: Moody: Auditor Tawny Heinemann, 101 E Pipestone Ave STE D, Flandreau, SD 57028-0750; ballot share 33.83% → 39.25%; reg share 33.13% → 27.27%; gap +0.70 → +11.98; ΔG +11.28; Dem reg 1,379 → 1,217; Dem votes 910 → 979; ballots 2,690 → 2,494; tabulator ES&S DS450 (Batch-Fed Optical Scanner)
- PASS: Harding: Auditor Kathy Glines, PO Box 26, Buffalo, SD 57720-0026; ballot share 4.83% → 4.92%; reg share 7.40% → 5.42%; gap -2.57 → -0.50; ΔG +2.07; Dem reg 73 → 55; Dem votes 33 → 33; ballots 683 → 671; tabulator ES&S DS200 (Hand-Fed Optical Scanner)
- PASS: Hughes: Auditor Thomas Oliva, 104 E. Capitol Avenue, Pierre, SD 57501; ballot share 34.91% → 31.01%; reg share 19.11% → 16.19%; gap +15.80 → +14.81; ΔG -0.99; Dem reg 2,224 → 1,921; Dem votes 2,652 → 2,034; ballots 7,597 → 6,560; tabulator ES&S DS450 (Batch-Fed Optical Scanner)
- PASS: Jones: Auditor Kerri Venard, PO Box 307, Murdo, SD 57559; ballot share 13.39% → 10.63%; reg share 10.41% → 8.11%; gap +2.98 → +2.52; ΔG -0.47; Dem reg 69 → 52; Dem votes 64 → 49; ballots 478 → 461; tabulator ES&S DS200 (Hand-Fed Optical Scanner)
- PASS: Buffalo: Auditor Debra Morrison, PO Box 146, Gann Valley, SD 57341-0146; ballot share 57.92% → 63.25%; reg share 62.95% → 57.98%; gap -5.03 → +5.28; ΔG +10.30; Dem reg 581 → 516; Dem votes 234 → 241; ballots 404 → 381; tabulator ES&S DS200 (Hand-Fed Optical Scanner)

## ZIP packages
- PASS: SD_County_Auditor_Letters_All_66.zip: 66 PDFs, 66 Word, README=True, size=5,730,596 bytes
- PASS: SD_County_Auditor_Letters_East_River.zip: 44 PDFs, 44 Word, README=True, size=3,821,240 bytes
- PASS: SD_County_Auditor_Letters_West_River.zip: 22 PDFs, 22 Word, README=True, size=1,910,454 bytes

## Voting equipment table
- PASS: equipment CSV rows: 66
- PASS: equipment counties match the 66 SOS counties
- PASS: equipment CSV is in population order, largest to smallest
- PASS: confirmed ED tabulator: 66 of 66
- PASS: every county has a listed election-day tabulator (no guessed equipment)
- PASS: vendor counts: ES&S 66
- PASS: ED equipment: ES&S DS200 (Hand-Fed Optical Scanner) 31, ES&S DS450 (Batch-Fed Optical Scanner) 26, ES&S DS850 (Batch-Fed Optical Scanner) 9
- PASS: poll books: Paper Poll Book 53, KNOWiNK Poll Pad 10, KNOWiNK TotalVote ePollbook 2, BPro TotalVote ePollbook 1

## Summary
- flags: 0
