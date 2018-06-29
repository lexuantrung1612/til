** First example: auto split a single CSV file into multiple files of 200 lines each
`split -l 200 split_me.tsv`
** Example 2: split into files of 1MB each, and add a '.csv' extension to all of them
`split -b 1m split_me.csv`
