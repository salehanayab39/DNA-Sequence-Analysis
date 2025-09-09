# DNA Sequence Analysis (GC Content & Start Codons)

This is a beginner-friendly Python project for analyzing simple DNA sequences.  
It performs two basic tasks:  
1. Calculates the **GC content** (percentage of G and C bases in a sequence).  
2. Checks whether each sequence starts with the **start codon (ATG)**.  

---

## Example Input
```python
dna_sequences = [
    "ATGTCAGG",
    "ATGCGCAA",
    "TTACCGGA",
    "ATGTTGGG",
    "GGCGCCTA"
]## Example Output                                                                                                                                                                         Sequence: ATGTCAGG | GC Content: 50.00% | Start Codon: Yes
Sequence: ATGCGCAA | GC Content: 62.50% | Start Codon: Yes
Sequence: TTACCGGA | GC Content: 50.00% | Start Codon: No
...## How to Run  

Make sure you have **Python 3** installed on your computer (check with `python --version`). First, clone this repository using `git clone https://github.com/your-username/DNA-sequence-analysis-gc-content-start-codons.git` and then navigate into the project folder with `cd DNA-sequence-analysis-gc-content-start-codons`. Finally, run the Python file using `python dna_analysis.py` and the output will be printed in your terminal.                                                                                                                            ## License  

This project is licensed under the MIT License – you are free to use, modify, and distribute it, provided proper credit is given.
