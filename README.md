# Phosphate/Sulphur starvation-induced trends
[Epic phosphate starvation overview](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1399-3054.2010.01356.x)

This section compares transcriptomes from plants exposed to phosphate deficiency, the trends in remodeling and differential expression of gene groups.

## Plants/data used

### Eutrema Pi Library
| Expression | Up-regulated | Down-regulated |
|:-----------|--------------|---------------:|
| Root       | 313          | 439            |
| Shoot      | 1.688        | 854            |

### [Oat](https://academic.oup.com/jxb/article/69/15/3759/4995034)
SRA: PRJNA355647

This experiment looks at the roots alone, apparently have >9000 2.0 fold + transcripts when exposed to low phosphate.

Plants were either exposed to 100 uM (Pi sufficient) or 1 uM (Pi deficient) KH2PO4

Shit it's a hexaploid, I'm not doing this. Have to use *de novo* for read assembly...

| Expression | Up-regulated | Down-regulated |
|:-----------|-------------:|---------------:|
| Root       | 7,817        | 1,554          |

### [Chinese fir](https://www.mdpi.com/1999-4907/8/11/420/htm)
No read data, not a single SRR. None. Zilch.

Analysis did no include total differentially expressed genes between treatments. Sketch AF.


### [Wheat](https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-14-77)
Wheat can be diploid (wild), tetraploid or hexaploid (cultivated) :weary:

DDBJ Sequence Read Archive (Accession No. DRA000737).

| Expression | Up-regulated | Down-regulated |
|:-----------|-------------:|---------------:|
| Root       | 1,004        | 892            |
| Shoot      | 2,833        | 1,382          |

 Apparently *TaIPS1* is 341-fold higher in roots and 13-fold higher in shoots (confirmed by qRT-PCR)

### [Rice](https://www.sciencedirect.com/science/article/pii/S017616171100383X)

A microarray analysis of rice genes, from leaves of plants grown under 32 uM P (Pi deficient) and 320 uM P (Pi sufficient)

| Expression | Up-regulated | Down-regulated |
|:-----------|:-------------|:---------------|
| Shoot      | 8,043        | 12,990         |

Doubltful results, are there that many differentially expressed genes with respect to 10x the difference in phosphate treatment?

### [Chickpea](https://europepmc.org/article/med/28628240)

A nodule transcriptome study after inoculating with bacteria and growing plant under 5 uM P (Pi deficient) and 500 uM P (Pi sufficient).

Does not have a Pi deficient-only treatment..

### [Arabidopsis](https://bmcplantbiol.biomedcentral.com/articles/10.1186/1471-2229-12-62)

Different *Arabidopsis* than the 1-3 day experiment, the plants were grown in no added phosphate (Pi deficient) and 1.75 mM sodium phosphate (Pi sufficient). 

Expression data was collected through micro- and tiling-arrays.

| Expression | Up-regulated | Down-regulated |
|:-----------|-------------:|---------------:|
| Root IPR   | 310          | 110            |
| Root PPR   | 47           | 50             |
| Root LPR   | 420          | 320            |
| **Total Root**| 777       | 930            |
| Shoot IPR  | 69           | 1              |
| Shoot PPR  | 18           | 2              |
| Shoot LPR  | 23           | 69             |
| **Total Shoot** | 110     | 72             |

### [*PHO1* mutant suppresses PSR](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1365-313X.2010.04442.x)

Reduced shoot P is not the result of Pi deficiency but is result of extensive gene expression reprogramming triggered by Pi deficiency.

Plants grown in 1.25 mM Pi (control), hydroculture 5 uM Pi (Pi deficient) and hydroculture 1 mM Pi (Pi sufficient). 



