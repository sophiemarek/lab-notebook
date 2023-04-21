# lab-notebook
lab notebook for gen 711 

4/21

mkdir trimmed_fastq

conda activate genomics

git version

git clone https://github.com/sophiemarek/poop-project.git

cd poop-project

touch testfile.txt

echo 'a test' > testfile.txt

cp /tmp/gen711_project_data/fastp-single.sh ~/fastp-single.sh

chmod +x ~/fastp-single.sh

head ~fast.sh

./fastp-single.sh 150 /tmp/gen711_project_data/FMT_3/fmt-tutorial-demux-1/ trimmed_fastq

./fastp-single.sh 150 /tmp/gen711_project_data/FMT_3/fmt-tutorial-demux-2/ trimmed_fastq
