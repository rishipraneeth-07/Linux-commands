#!/bin/bash
read -p "Enter a number: " n
fact=1
i=$n
while [ $i -gt 1 ]
do
  fact=$((fact * i))
  i=$((i - 1))
done
echo "Factorial of $n is $fact"
