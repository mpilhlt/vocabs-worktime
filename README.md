[![DOI](https://zenodo.org/badge/453994489.svg)](https://zenodo.org/badge/latestdoi/453994489) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

# MPILHLT Concepts of Work Regulations

## Description

This repository contains a systematic taxonomy used to describe various aspects of (non-state) working regulations such as contracts and company regulations. It was developed beginning in 2021, in order to annotate full texts of such regulations in the context of the project [Non-state law of the economy. The normative order of industrial relations in the metal industry from the Empire to the early years of the Federal Republic of Germany](https://www.lhlt.mpg.de/research-project/non-state-law-of-the-economy) at [Max Planck Institute for Legal History and Legal Theory](https://www.lhlt.mpg.de/en), Frankfurt.

The `*.ttl` files encode the taxonomy it as a [SKOS](https://www.w3.org/TR/skos-reference/) vocabulary in [turtle (ttl) format](https://www.w3.org/TR/turtle/).

We have decided to split the scheme into a series of separate taxonomies for *actions*, *physical objects and spaces*, *prescriptive aspects*, *reflexive and meta-aspects*, *regulation terms* and *social roles*, respectively. Thus, each taxonomy manages concepts about the things of the same "kind" (and it is easier to integrate it into a working environment where you want to access different aspects in isolation using different commands or GUI buttons). The `worktime_regulation.ttl` reflects an earlier stage of the scheme where everything was still integrated in one big taxonomy. It misses some concepts and alternative labels that the other, more up-to-date, files have been augmented with.

*Last revision: September 2023, v0.0.4.*

## URLs

The homepage of the vocabularies is at <https://w3id.org/mpilhlt/vocabs-worktime>.
Individual concepts and concept schemes are at <https://w3id.org/mpilhlt/worktime[_subvoc]/[version/][id]> (where `subvoc` is an optional component if you want to refer to one of the narrower concept schemes, the optional `version` is a specific version of the respective vocabulary -- or "latest", which is also the default if you don't specify a version -- and `id` is the optional identifier of the concept or concept scheme).

The source files for these vocabularies are maintained at <https://github.com/mpilhlt/vocabs-worktime/>, and deposited to the research data repository zenodo at <https://zenodo.org/record/8386361> ([DOI:10.5281/zenodo.8386360](10.5281/zenodo.8386360.)).

## Contributors

As authors, we suggest to credit the following contributors: [Peter Collin](https://www.lhlt.mpg.de/collin/en), [Matthias Ebbertz](https://www.lhlt.mpg.de/ebbertz/en), [Polina Solonets](https://www.lhlt.mpg.de/2854913/polina-solonets), [Benjamin Spendrin](linkedin.com/in/benjamin-spendrin-0210bb236), [Tim-Niklas Vesper](https://www.lhlt.mpg.de/vesper/en), [Andreas Wagner](https://www.lhlt.mpg.de/wagner/en) and [Johanna Wolf](https://www.lhlt.mpg.de/wolf/en). Encoding the scheme in SKOS was done by Andreas Wagner.

## License

The classification scheme(s) can be reused without restrictions as they are released in the public domain with a [CC-0](https://creativecommons.org/public-domain/cc0/) license. (But we would obviously be glad if the project or the authors were mentioned when you use the vocabularies.)

[![License: CC0-1.0](https://licensebuttons.net/l/zero/1.0/80x15.png)](http://creativecommons.org/publicdomain/zero/1.0/)
