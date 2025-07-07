# TKLTA_Idioms_Annotated_10

TKLTA_Idioms_Annotated_10 is a multilingual collection of idiomatic expressions curated as part of the **Talkalotta Corpora**. The dataset aggregates ten annotated idioms for each of 68 languages and regional varieties. Every CSV file in this repository corresponds to one language or dialect and contains both linguistic metadata and example sentences for each idiom.

## Repository Structure
Each file follows the naming pattern `TKLTA_<CODE>_10_IDI_AN.csv`, where `<CODE>` is the language or dialect identifier. For example, `TKLTA_AFB_10_IDI_AN.csv` holds data for Gulf Arabic while `TKLTA_AUEN_10_IDI_AN.csv` contains Australian English idioms. The dataset covers a broad spectrum of varieties, including multiple Spanish dialects, Arabic dialects, regional languages of Europe, English variants, and others.

```
AEB  – Tunisian Arabic
AF   – Afrikaans
AFB  – Gulf Arabic
ANDA – Andalusian Spanish
ANDE – Andean Spanish
ANGR – Ancient Greek
AN   – Aragonese
ARAN – Aranese
ARA  – Modern Standard Arabic
ARY  – Moroccan Arabic
ARZ  – Egyptian Arabic
AST  – Asturian
AUEN – Australian English
BOES – Bolivian Spanish
BP   – Brazilian Portuguese
BZES – Venezuelan Spanish
...  (additional codes represent the remaining languages and dialects)
```

A total of 68 CSV files are provided. Each file has 11 rows: one header row followed by ten idiom entries.

## Column Description
While column labels vary slightly between files, they generally include:

1. **Idiom** – the idiomatic phrase in the target language.
2. **Syntactic Structure & Grammatical Form** – notes on syntax or fixed expression type.
3. **Figurative Meaning** – a concise contextual definition.
4. **Non-Idiomatic Equivalent** – a plain-language paraphrase.
5. **CEFR Level** – approximate difficulty from A1–C2.
6. **Usage Contexts** – typical situations where the idiom occurs.
7. **Register and Tone** – stylistic information (e.g., formal, colloquial, humorous).
8. **Cultural Origin or Historical Reference** – background about the idiom’s source.
9. **Phonetic Transcription (IPA)** – pronunciation key.
10. **First/Second/Third Example Sentence** – three example usages in context.

Below is a snippet from `TKLTA_AUEN_10_IDI_AN.csv`:

```
Idiom,Syntactic Structure & Grammatical Form,Figurative Meaning,Non-Idiomatic Equivalent,CEFR Level,Usage Contexts,Register and Tone,Cultural Origin or Historical Reference,"Phonetic Transcription (IPA, Australian English)",First Example Sentence,Second Example Sentence,Third Example Sentence
Flat out like a lizard drinking,Simile; fixed expression,Extremely busy or active,Very busy or working hard,B2,"Daily speech, workplace, humour","Colloquial, humorous",Australian rural idiom; evokes image of lizard rapidly lapping water in the heat,/flæt aʊt laɪk ə ˈlɪzəd ˈdrɪŋkɪŋ/,I’ve been flat out like a lizard drinking all week getting this project finished.,Sorry I didn’t call—been flat out like a lizard drinking at work.,"Between the kids and the chores, she’s flat out like a lizard drinking."
```

## Usage
These resources can be useful for linguistic research, idiom translation studies, or language learning materials. The CEFR tag and example sentences facilitate quick integration into educational content.

## License
The dataset is released under the [Creative Commons Attribution‑ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/). If you use any portion of the Talkalotta Corpora, please attribute as follows:

> "**TKLTA_Idioms_Annotated_10** by **Talkalotta**, part of the Talkalotta Corpora, licensed under CC BY-SA 4.0"

## Contributing
Pull requests that expand documentation or correct mistakes are welcome. When adding new idioms or languages, please maintain the existing CSV structure.

