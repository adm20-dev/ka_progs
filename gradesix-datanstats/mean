#!/bin/zsh
# ac 16 DEC 23
# script to calculate mean
# input: cli params like so "1 2 3 4 5"
# outpu: echo mean cli

array=($@)
sum=0
count=0

for item in "${array[@]}"; do
	sum=$(( "$item" + sum ))
	count=$(( count + 1 ))
done

echo "Number of elements in set"
echo $count
echo "Sum of elements"
echo $sum
echo "Mean of elements"
echo $(( sum / count ))
