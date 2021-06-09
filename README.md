# yeast-rnaseq
# yeast-rnaseq
hisat2-build Saccharomyces_cerevisiae.R64-1-1.dna.toplevel.fa yeast \t
hisat2 -x ../reference/yeast -U ./SRR1916154.1_1.fastq >yeast_3b_strain2 \t
samtools view -o *.bam  *.sam \t
samtools sort yeast_3b_strain2.bam -o yeast_3b_strain2.srt.bam \t
