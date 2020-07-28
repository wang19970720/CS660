# CS660 Homework Assignment 1
## Group Members
-Yan Li
-Chengyi Wang
-Smith Amornsaensuk



# Input
book

#### Implementation of page 75
python3 mr_base_inverted_indexing.py -r dataproc ./book/*
-1 min 44 sec

python3 mr_base_inverted_indexing.py -r dataproc ./book/* --num-core-instances 6
-1 min 42 sec

python3 mr_base_inverted_indexing.py -r dataproc ./book/* --num-core-instances 2 --instance-type n1-highcpu-4
-1 min 34 sec


#### Implementation of page 79
python3 mr_revised_inverted_indexing.py -r dataproc ./book/*
-1 min 41 sec

python3 mr_revised_inverted_indexing.py -r dataproc ./book/* --num-core-instances 6
-1 min 38 sec

python3 mr_revised_inverted_indexing.py -r dataproc ./book/* --num-core-instances 2 --instance-type n1-highcpu-4
-1 min 33 sec
