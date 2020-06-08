# CIWD 3.0.0 data table

This table is a companion to the paper: 
[Common, intermediate and well-documented HLA alleles in world populations: CIWD version 3.0.0](https://www.ncbi.nlm.nih.gov/pubmed/31970929)

HLA. 2020 Jan 22. doi: 10.1111/tan.13811.

The format is CSV:

- **ALLELE** (as defined in the paper)
- **TOTAL**: C, I, R, WD (according to the paper)
- **AFA**,**API**,**EURO**,**HIS**,**MENA**,**NAM**,**UNK** (7 populations)

Example:
```A*01:01,C,C,C,C,C,C,C,C```


**Note**: The manuscript table has listings for some alleles with and without the word "total".  In these cases, the values associated with the "total" indication are used.  For instance `B*54:01 total` is common (reported 12,022 times) but in the paper `B*54:01` is listed as merely well documented (reported 6 times) because it is almost reported as `54:01:01G` or `54:01:01` which, according to the hierarchical nature of WHO nomenclature are contained in `54:01`.


**Note**: The “total” version in this dataset that the row represents the P group for that allele – including all alleles that roll up to that P group designation. For instance B*15:03 total (now represented as just ‘B*15:03’) includes B*15:03, B*15:03P, B*15:03:01G, B*15:03:01, B*15:03:01:01, B*15:03:01:02, B*15:103, B*15:220, B*15:03:02, B*15:03:03, B*15:03:04, and B*15:03:05.
Martin Maiers
mmaiers@nmdp.org
