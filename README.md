# metacomp
A search algorithm that compares meta data of two strings, text or files and uses the meta data table to faster evaluate any differences. Any other search algorithm can be implemented after this check.

## Complexity
The time complexity to generate the meta -ata is O^(n). The time for actual comparion is m where m is the number of parameters in the meta-data.

## Parameters for the meta-data
- Count of characters
- Count of lowercase, uppercase characters
- Count of numbers
- Count of special characters
- File SHA-1 comparison

## How to use
Pass two text files as arguements e.g.
```console
./metacomp "file1" "file2"
```
The algorithm will let you know if the search was successful or not and why.
