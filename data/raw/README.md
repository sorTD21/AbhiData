## Data Links

Obtained the data from
https://rrndb.umms.med.umich.edu/static/download/

Files are from version 5.6, released in 2019

Links to downloaded files

* [rrnDB-5.6_pantaxa_stats_RDP.tsv.zip](https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.6_pantaxa_stats_RDP.tsv.zip)
* [rrnDB-5.6_pantaxa_stats_NCBI.tsv.zip](https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.6_pantaxa_stats_NCBI.tsv.zip)
* [rrnDB-5.6_16S_rRNA.fasta.zip](https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.6_16S_rRNA.fasta.zip)
* [rrnDB-5.6.tsv.zip](https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.6.tsv.zip)

## Automating the Downloads

Automated downloading the last zip file by-
`wget --directory-prefix=data/ --no-clobber https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.6.tsv.zip`

Unzip the downloaded zip file to the same directory
`unzip -n -d data/ data/rrnDB-5.6.tsv.zip`
