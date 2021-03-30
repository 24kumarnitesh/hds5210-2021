Score: 50/50

One tip on reading CSV files is to use `next(csv_reader)` before you start looping through the rows in your CSV.  This will skip the header row.  I noticed how you were doing a test on `if age == 'age'` to determine if you were in hte header row.

Nice work!