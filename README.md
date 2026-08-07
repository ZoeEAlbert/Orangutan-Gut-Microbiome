Code used for my dissertation "THE GUT MICRIOBIOME AS A POTENTIAL MODULATOR OF ENERGETIC STRESS IN BORNEAN ORANGUTANS (PONGO PYGMAEUS)"
The product of sequencing runs on the MinION that I used are POD5 files.
I first saved these files, and then re-basecalled them on MinKNOW software using high accuracy basecalling.
This produced FASTQ files that were manually combined by outer barcode into a single outer barcode folder on box.com. 
I then used Guppy on R to demultiplex our files.
Next, MetONTIIME was run on the SCC in order to separate the data into taxa. 
