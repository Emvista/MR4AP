# MR4AP-wikipedia corpus (v0.2)

## Disclaimer

This corpus is supposed to grow in size.

## Repository contents

This repository hosts the **MR4AP-wikipedia** corpus v0.2. The `files` folder contains a subfolder per language. Each
subfolder contains the available JSON files. Those files present three main fields:
* `id`: the text id,
* `text`: the plain text,
* `rdf`: the corresponding RDF representation containing the annotations.

Each filename follows the following syntax `Wikipedia_article_name_in_French_language.json`. The `_language` part is
not used for French texts.

## How was this dataset created?

This dataset is the result of a manual annotation effort. What the annotators did was:
* Select 5 random Wikipedia articles in French,
* Manually annotate the first 3 sentences of each document using the INCEpTION tool,
* Automatically translate them into English, Spanish, Italian, and Modern Standard Arabic (MSA),
* Manually annotate them.

Not all the texts were annotated in each language. However, more texts in French were annotated. 
Here is an overview of the dataset's contents:

| Language  | Documents | Sentences |
|-----------|-----------|-----------|
| French    | 45        | 135       |
| English   | 4         | 12        |
| Italian   | 4         | 12        |
| MSA       | 4         | 12        |
| Spanish   | 1         | 3         |
| **Total** | **58**    | **174**   |

The annotation effort must continue! If you want to try MR4AP out, you can find:
* Extensive annotation guidelines [here](../../guidelines/guidelines.md),
* An INCEpTION practical guide [here](../../guidelines/guidelines.md#how-to-inception-a-practical-guide),
* The INCEpTION layers and tagsets [here]().

Feel free to reach out if you need any more information.
* bastien.giordano [at] emvista.com
* cedric.lopez [at] emvista.com

## Corpus statistics

These statistics take into account every annotated text in every language. For language-specific statistics, please
see the corresponding folders.

| Item                            | Number |
|---------------------------------|--------|
| Tokens                          | 4,851  |
| Avg tokens per sentence         | 24.93  |
| Nodes                           | 2,500  |
| Avg entities per document       | 23.30  |
| Avg dynamic events per document | 4.69   |
| Avg stative events per document | 10.73  |
| Relations                       | 2,438  |
| Avg relations per document      | 54.18  |