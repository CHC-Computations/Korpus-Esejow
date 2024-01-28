![alt text](https://github.com/CHC-Computations/Harmonize/blob/main/logo-1.png?raw=true)
# Corpus of Essays (Korpus Esejów; KE)
![alt text](https://github.com/CHC-Computations/Korpus-Esejow/blob/main/eseje1.png?raw=true)

The Corpus of Essays (KE) is a collection of texts covering Polish scientific and literary essays from the 20th and 21st centuries (1931-2022). It collects works by Polish literary scholars and literary scholars. All published texts are for the internal use of the Institute of Literary Research due to copyright restrictions.

## Contributors

**Institute of Literary Research of the Polish Academy of Sciences**, [www.ibl.waw.pl](https://ibl.waw.pl/)

## Corpus design
The collected texts come from different sources.
- subcorpus of literary essays
- subcorpus of scientific essays.

### Balancing criteria

*to be added*

### Limitations

- imprecise definition of the population – there is no complete list of essay publications, and the lists that can be compiled from available bibliographic data are not exhaustive
uneven availability of publications in digital form
- copyright – licenses prevent the use of certain texts in corpus work

### Statistics

The corpus contains 717 texts.

<p align="center">
  <img src="KE_Number of texts by decade.png" alt="Number of texts by decade" width="65%">
</p>

<p align="center">
  <img src="KE_Number of texts by type.png" alt="Number of texts by type" width="65%">
</p>

## Access

All texts are published in .txt format for the internal use of the Institute of Literary Research due to copyright restrictions.

### Metadata

The description of the corpus texts includes the following metadata:
```
identifier
type
title
author
source
source_date
publication_date
```
The table with metadata is presented [here](https://github.com/CHC-Computations/Korpus-Esejow/blob/main/KE_resources.csv).

## Use in the [GoLEM service](https://chrc.clarin-pl.eu/files/golem)

Graph Literary Machine Explorer (GoLEM) is a system for advanced analysis and visualization of the connections between terms, entities, and vocabularies (topics) in scientific texts, primarily in texts in the field of literary studies, in synchronous and diachronic dimensions.
GoLEM will offer the possibility to work on ready-made corpora or corpora uploaded by the user. A KDL will be made available as part of the service.
The following services are envisaged:
- Entity analysis: entity recognition and time-varying frequency analysis, analysis of relationships between entities in selected textual wholes (sentence, paragraph, whole document, user-defined window) and between texts or sub-corpus highlighted based on metadata; the processing pipeline will include separation of footnotes and bibliography, recognition of correlations, NEDs, and NELs (disambiguation of names of people and places)
- Analysis of terms/concepts: recognition of literary and literature terms (eventually also terms from other disciplines) and analysis of their frequency of occurrence in the corpus, in individual texts and sub-corpus taking into account changes over time, analysis of changes in the meaning of terms over time and within different sub-corpus
- Vocabulary analysis: semi-supervised topic modeling, LDA including literary entities and terms, "contextualized" topic modeling using language models.

## License

All texts in this collection are protected by copyright and may not be redistributed. The corpus was created for the internal work of IBL PAN.

![alt_text](https://github.com/CHC-Computations/Harmonize/blob/main/Zrzut%20ekranu%202022-12-19%20o%2017.48.49.png?raw=true)
