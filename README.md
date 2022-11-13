# Finnish and Hungarian Lexical Resources 

This repository contains several files which have been extracted from the [FULR](https://fulr.btk.ppke.hu) database.
These data were obtained using several algorithms and resources, and have been manually validated by speakers of Finnish and Hungarian.
The structure of the files and the applied methods can be found below.

## Files

The part-of-speech tags (wherever relevant) follow the guidelines of the [Universal Dependencies tagset](https://universaldependencies.org/u/pos/index.html).
If no part-of-speech tag can be provided, the field contains `_`.
The TSV files in this repository are constructed as follows:

### Translations

This file contains Finnish and Hungarian translation pairs with their part-of-speech tags.
In the first column, the Finnish lemma or phrase is displayed, in the second column, the Hungarian.
The third and fourth columns store part-of-speech tags, in the same order as the first two columns (part-of-speech tags first for the Finnish, then for the Hungarian word).

### Synonyms

Synonyms are listed in pairs. The first column contains the language code (either `fi` or `hu`),
while the second and third columns contain the two words or phrases that are synonyms. 

### Definitions

Two separate files contain the definitions, depending on the language `definitions_fi.tsv` and `definitions_hu.tsv`.
In the first column, the word or phrase is displayed, along with its part-of-speech tag (in the second column), while the definition appears in the third column.

### Example sentences

Two separate files contain the example sentences, depending on the language `example_sentences_fi.tsv` and `example_sentences_hu.tsv`.
In the first column, the word or phrase is displayed, along with its part-of-speech tag (in the second column), while the example (sentence) of that word appears in the third column.
Note: the example is not necessarily a sentence.


### Further information

For more information, please, visit the [FULR](https://fulr.btk.ppke.hu) website.

## Applied methods

- [Wiktionary Parser](https://github.com/ferenczizsani/wiktionary_parser)
- [WordNet Connector](https://github.com/ferenczizsani/connect_wordnets)
- [OPUS Extractor](https://github.com/ferenczizsani/opus_extractor)
- [wikt2dict](https://github.com/juditacs/wikt2dict)


## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

