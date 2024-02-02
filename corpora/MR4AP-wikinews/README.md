# MR4AP-wikinews corpus

## Disclaimer

This corpus is supposed to grow in size.

## Repository contents

This repository hosts the **MR4AP-wikinews** corpus. The `files` folder contains the available JSON files. 
Those files present three main fields:
* `id`: the text id,
* `text`: the plain text,
* `rdf`: the corresponding RDF representation containing the annotations.

## How was this dataset created?

This dataset is the result of a manual annotation effort. What the annotators did was:
* Select random French [Wikinews](https://fr.wikinews.org/wiki/Accueil) articles,
* Manually annotate the first 5 sentences of each document using the INCEpTION tool.

The annotation effort must continue! If you want to try MR4AP out, you can find:
* Extensive annotation guidelines [here](../../guidelines/guidelines.md),
* An INCEpTION practical guide [here](../../guidelines/guidelines.md#how-to-inception-a-practical-guide),
* The INCEpTION layers and tagsets [here](../../guidelines/inception_settings).

Feel free to reach out if you need any more information.
* bastien.giordano [at] emvista.com
* cedric.lopez [at] emvista.com

## Corpus statistics

| Item                            | Number |
|---------------------------------|--------|
| Tokens                          | 1,629  |
| Avg tokens per sentence         | 23.96  |
| Nodes                           | 958    |
| Avg entities per document       | 41.62  |
| Avg dynamic events per document | 14.00  |
| Avg stative events per document | 14.08  |
| Relations                       | 1,022  |
| Avg relations per document      | 78.62  |