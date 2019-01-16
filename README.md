# my_exam
touch~/.bash_profile(t)
open~/.bash_profile(we can take some information from omgenomics.com/bash-intro)
$cd~/desktop
$mkdir my_folder
$ls(show the result)
cd my_folder/
$cd ..
$cd my_folder/
$ls
$cd ../..
$touch my_file.txt
$ls
$open my_file.txt
$nano my_file.txt(cntrl x and enter)
$open my_file.txt(we also take information from same as the above)
$cat my_file.txt
$head my_file.txt(only top 10)
head -n 5 my_file.txt
$less -s my_file.txt
$cat my_file.txt
$cat my_file.txt | cut-f 2
$cat my_file.txt | awk '{$1=$1;print}'ofs='\t' |cut -f 2
$cat my_file.txt |cut -f 2 |uniq -c
$$cat my_file.txt |cut -f 2 |sort
$cat my_file.txt |cut -f 2 |sort |uniq -c
$cat my_file.txt |cut -f 2 |sort|uniq -c|sort -k1,1n
$cat my_file.txt |cut -f 2|sort|uniq -c|sort -k1,1nr
$history
$sort --help
$man uniq/sort
