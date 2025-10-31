#!/bin/bash
files=$(ls -l | grep "^-" | wc -l)
dirs=$(ls -l | grep "^d" | wc -l)
echo "Number of files: $files"
echo "Number of directories: $dirs"
