# Board Game Analysis Scripts

## Scripts

- `empty_cells`: Gives the list of columns with the no. of empty cells in it.
- `preprocess`: Cleans the dataset, assigns missing IDs, normalizes fields.
- `analysis`: Computes correlation and finds most common mechanics/domains.

## How to Run

```bash
./empty_cells cleaned.txt
./preprocess cleaned.txt
./analysis cleaned.tsv
```
