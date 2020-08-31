# LoopForSpades


for i in {1..N}
do
spades.py --careful --cov-cutoff 5(value) --pe1-1 '/RESOURCE PATH/NAME${i}_R1.fastq.gz' --pe1-2 '/RESOURCE PATH/NAME${i}_R2.fastq.gz' -o /DESTINATION PATH/NAME${i}
dome


#Example
#I have pair reads of EC (NAME) strats from 1 to 2019 and I'm at the directory where the files are, so I don't give RESOURCE PATH

for i in {1..2019}
do
spades.py --careful --cov-cuoff 5 --pe1-1 EC${i}_R1.fastq.gz --pe1-2 EC${i}_R2.fastq.gz -o /media/mahnaz/spades_out/EC${i}
done

