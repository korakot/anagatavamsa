# Anāgatavaṃsa: the verse text from Minayeff's PTS edition (1886), in Thai script

**Read online (Thai script, roman, Thai translation):** <https://korakot.github.io/anagatavamsa/> · **PDF (A5):** [anagatavamsa-thai-a5.pdf](anagatavamsa-thai-a5.pdf) · [ภาษาไทย](README.md)

Kassapa's *Anāgatavaṃsa*, the 142-verse Pāli poem on the coming Buddha Metteyya, transliterated into Thai script from J. Minayeff's edition in the *Journal of the Pali Text Society* 1886, pp. 41–53 (public domain). An earlier Thai-script edition with a Thai translation exists (see below), made from a later roman edition rather than from the PTS edition.

Not to be confused with the Thai prose *Anāgatavaṃsa* on ten future Buddhas, which is a different text.

## Files

- `index.html`: the reading page; works on phones; Thai script, roman and the Thai translation can each be shown or hidden.
- `anagatavamsa-thai-a5.pdf`: an A5 print copy, 17 pages.
- `data/verse.tsv`: one row per pāda (590 rows). Columns: `key` (e.g. `v12.3` = verse 12, third pāda), `verse`, `pada`, `page` (the PTS page), `roman`, `thai`.
- `data/translation.tsv`: the Thai translation, one row per verse. Columns: `key` (`v12` = verse 12; `head` and `end` are the opening homage and the closing line), `verse`, `thai`, `note` (translator's notes, in English).
- `data/terms.tsv`: the names and terms used in the translation.
- `data/translation-align.tsv`: the translation linked to the Pāli word by word (on the reading page, tap a word to see its partner).
- `data/words.tsv`: per-word data for the 1,357 words: a short Thai gloss, the sandhi or compound split, Thai grammatical analysis, DPD's meaning and MCU's commonest renderings (on the reading page, hover over or tap a Pāli word).

## How it was made

1. The roman text was transcribed from the page images of the printed edition.
2. It was compared letter by letter with K. R. Norman's re-edition (*JPTS* 28, 2006), whose apparatus records Minayeff's reading wherever Norman changed it. Every difference was checked on a zoomed image of the print.
3. Minayeff's spellings are kept as printed. Three obvious misprints are corrected (verses 30, 31, 39).
4. The Thai script was produced by [axorn](https://github.com/korakot/axorn), following the VRI Tipiṭaka convention (พินทุ ฺ for a consonant without a vowel, นิคหิต ํ for ṃ).

It was made with AI assistance and hasn't been proofread independently yet, so it is a draft. Please report errors in [GitHub issues](https://github.com/korakot/anagatavamsa/issues).

## The Thai translation

The Thai translation was drafted by AI (Claude) from the Pāli above. It follows Minayeff's readings and was made with Norman's English translation (2006), the commentary extracts in Minayeff's footnotes and the Digital Pāli Dictionary. A second, independent AI pass checked the meaning verse by verse against the Pāli, and a third pass checked the Thai for readability. The 2000 Thai translation was used to compare meanings only, never copied. No scholar has checked it yet. Where a reading is open, the `note` column says so.

## Related editions

- พระมหาชนะ ธมฺมธโช (ภมรพล), *อนาคตวํส คัมภีร์อนาคตวงศ์ พระอริยเมตไตรย* (2000): Pāli in Thai script with a Thai translation, made from U Chit Tin & W. Pruitt's roman edition (1988).
- K. R. Norman, "The Anāgatavaṃsa Revisited", *JPTS* 28 (2006): a revised text with an English translation.

## Licence

[CC0 1.0](LICENSE): dedicated to the public domain. Use, copy, adapt and share freely, with no permission needed.
