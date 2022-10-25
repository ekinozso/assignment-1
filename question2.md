#Group 4's answer to question 2

**Question 2:** Please assign variables to the individual components of your favorite gene! (e.g.
promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene
by using the string concatenation operator, on the standard output! Note: Feel free to create a
fictional gene sequence by randomly filling in the gene component.

**Answer:**

```
Promoter = "TATATTTTTGGAGCCCGTATTAAG"
five_prime_UTR = "AAATTGCAAATCGTATATGG"
start_codon = "ATG"
exon1 = "GCATGAATGGGTACACA"
intron = "GGGGGTATACCTATA"
exon2 = "ACGCAAACATAGAGA"
three_prime_UTR = "TTTTTTTTTTTAAAAAGCGG"

my_fav_gene = promoter + five_prime_UTR +  start kodon + exon1 + \ 
              intron + exon2 + stop kodon + three_prime_UTR

print("My favorite gene sequence is as follows:")
print(my_fav_gene)
```
