## Autolinking for scholarly identifiers

Implemented as a liquid filter for the Jekyll static website generator. Add `jekyll-scholmd.rb` to the `_plugins`folder of your Jekyll site and include `{{ content | to_scholmd }}` in your template, e.g. default.html.

Currently supported identifiers:

* IGSN. [International Geosample Number](http://dokuwiki.gfz-potsdam.de/datawiki/doku.php?id=igsn:syntax)
* MGI identifiers for genetically modified mouse strains in the [Internal Mouse Strain Resource](http://www.findmice.org/about)
* ENA. [Genbank / ENA / DDBJ nucleotide sequences](http://www.ebi.ac.uk/ena/about/about)
* UniProt protein sequences from the [UniProt database](http://www.uniprot.org/help/about)
* PDB. [Protein Data Bank protein structure information](http://www.rcsb.org/pdb/static.do?p=home/faq.html)

Please open an issue for additional identifiers and/or improvements in the regex patterns used.