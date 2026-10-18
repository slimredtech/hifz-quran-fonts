# Hifz Planner: Quran page fonts

The 604 page fonts of the **Madinah mushaf (Hafs, 1421 AH print, 15 lines per page)**, as
published by the **King Fahd Glorious Quran Printing Complex** (KFGQPC) in its "QCF V2" series.
Each font draws one page of the mushaf.

The [Hifz Planner](https://slimredtech.github.io/hifz-docs/) app downloads them from the
[release of this repository](../../releases/tag/qcf-v2-1421h), so that its page reader does not add
200 MB to the app's download.

## Files

The release `qcf-v2-1421h` holds 604 files, `QCF2001.ttf` (page 1) to `QCF2604.ttf` (page 604),
about 200 MB in total.

- **Unmodified.** Every font is byte for byte the file published by KFGQPC. Only the file names
  differ: `p1.ttf` became `QCF2001.ttf`, which is the font's own internal name.
- **Checked.** `SHA256SUMS` lists the SHA-256 of every file. The app also checks each download
  before it uses it.

Source: the [Quranic Universal Library](https://qul.tarteel.ai/resources/font/249) (Tarteel), which
publishes these fonts from KFGQPC.

## Terms of use

The fonts belong to the King Fahd Glorious Quran Printing Complex, Madinah
(<https://qurancomplex.gov.sa>). KFGQPC allows them to be used, copied and distributed free of
charge, on these conditions:

- do not modify, alter, translate or reverse-engineer them;
- do not sell them;
- credit the King Fahd Glorious Quran Printing Complex.

They are provided as they are, without any warranty. This repository is not affiliated with or
endorsed by KFGQPC or Tarteel.

## Contact

Questions or problems: open an issue in this repository.
