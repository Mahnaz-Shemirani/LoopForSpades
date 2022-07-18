
#Loop For Spades for assembly R1 and R2


for i in {1..N}

do

spades.py --careful --cov-cutoff 5(value) --pe1-1 '/RESOURCE PATH/NAME${i}___R1.fastq.gz' --pe1-2_ _'_/RESOURCE PATH/NAME${i}__R2.fastq.gz' -o /DESTINATION PATH/NAME${i}
__
done


#Example

#pair reads of EC (NAME) strats from 1 to 2019 along with being at the directory where the files exist, therefore RESOURCE PATH is eliminates

for i in {1..2019}

do

spades.py --careful --cov-cuoff 5 --pe1-1 EC${i}__R1.fastq.gz --pe1-2 EC${i}__R2.fastq.gz -o /media/mahnaz/spades_out/EC${i}__

done

