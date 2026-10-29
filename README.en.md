# Anāgatavaṃsa: the verse text from Minayeff's PTS edition (1886), in Thai script

**Read online:** <https://korakot.github.io/anagatavamsa/> · **PDF (A5):** [anagatavamsa-thai-a5.pdf](anagatavamsa-thai-a5.pdf) · [ภาษาไทย](README.md)

Kassapa's *Anāgatavaṃsa*, the 142-verse Pāli poem on the coming Buddha Metteyya, transliterated into Thai script from J. Minayeff's edition in the *Journal of the Pali Text Society* 1886, pp. 41–53 (public domain). An earlier Thai-script edition with a Thai translation exists (see below), made from a later roman edition rather than from the PTS edition.

Not to be confused with the Thai prose *Anāgatavaṃsa* on ten future Buddhas, which is a different text.

## Files

- `index.html`: the reading page; works on phones, switches between Thai and roman script.
- `anagatavamsa-thai-a5.pdf`: an A5 print copy, 17 pages.
- `data/verse.tsv`: one row per pāda (590 rows). Columns: `key` (e.g. `v12.3` = verse 12, third pāda), `verse`, `pada`, `page` (the PTS page), `roman`, `thai`.

## How it was made

1. The roman text was transcribed from the page images of the printed edition.
2. It was compared letter by letter with K. R. Norman's re-edition (*JPTS* 28, 2006), whose apparatus records Minayeff's reading wherever Norman changed it. Every difference was checked on a zoomed image of the print.
3. Minayeff's spellings are kept as printed. Three obvious misprints are corrected (verses 30, 31, 39).
4. The Thai script was produced by [axorn](https://github.com/korakot/axorn), following the VRI Tipiṭaka convention (พินทุ ฺ for a consonant without a vowel, นิคหิต ํ for ṃ).

It was made with AI assistance and hasn't been proofread independently yet, so it is a draft. Please report errors in [GitHub issues](https://github.com/korakot/anagatavamsa/issues).

## Related editions

- พระมหาชนะ ธมฺมธโช (ภมรพล), *อนาคตวํส คัมภีร์อนาคตวงศ์ พระอริยเมตไตรย* (2000): Pāli in Thai script with a Thai translation, made from U Chit Tin & W. Pruitt's roman edition (1988).
- K. R. Norman, "The Anāgatavaṃsa Revisited", *JPTS* 28 (2006): a revised text with an English translation.

## Licence

[CC0 1.0](LICENSE): dedicated to the public domain. Use, copy, adapt and share freely, with no permission needed.
