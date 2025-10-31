#!/bin/bash
read -p "Enter a number: " n
echo "Multiplication table of $n:"
for ((i=1; i<=10; i++))
do
  echo "$n x $i = $((n * i))"
done
