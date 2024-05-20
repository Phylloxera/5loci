# USDA-ARS 5loci BLAST Databases for GEAbash

## Cloning 5loci dbs
`git clone https://github.com/Phylloxera/5loci.git`
## Updating 5loci dbs
`cd 5loci; git pull https://github.com/Phylloxera/5loci.git`
## Example conducting a BLAST search against one of the 5loci dbs
`export BLASTDB=$BLASTDB:5loci/Colibactin_clb; blastn -task megablast -query <query fasta> -db Colibactin_clb \
-out <output file name> -num_threads <number of threads>`
