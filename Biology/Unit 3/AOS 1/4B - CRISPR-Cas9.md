---
aliases:
  - CRISPR-Cas9
---
The CRISPR-Cas9 system naturally occurs as an **adaptive immune system** in prokaryotes.

CRISPR stands for **Clustered Regularly Interspaced Short Palindromic Repeats**.
## Acquiring the Spacer

- Cas1-Cas2 recognise a **PAM sequence** (Protospacer adjacent motif, NGG) & cleave a **protospacer** (~20–26bp) upstream leaving sticky ends
- The protospacer is inserted at the **5' (leader) end** of a **CRISPR array**
- PAM sequences are ==not== part of the CRISPR array, thus Cas9 does not check bacterial DNA. Cas1-Cas2 do not cleave bacterial DNA due to them not cutting DNA with [[chi sites]] & the high density of [[chi sites]] in bacterial DNA
## CRISPR-Cas9 Formation 

1. The CRISPR array is **transcribed** into a single long **pre-crRNA**
2. Unprocessed **tracrRNA** anneals to the **repeat regions** of pre-crRNA
3. RNA processing enzymes (RNase) cleave the pre-crRNA into **cr:tracrRNA** by cleaving the strand between complexes.
4. cr:tracrRNA becomes **gRNA** when bound by Cas9 (through the **scaffold sequence**).

## CRISPR-Cas9 Activation

1. CRISPR-Cas9 scans DNA for a PAM sequence
2. Once found, it compares the **spacer sequence** of the gRNA to a sequence upstream of the PAM, a protospacer, on the strand **opposite** the PAM sequence
3. If they are complementary, Cas9 cleaves both strands of DNA ~4bp upstream of the PAM leaving **blunt ends**.

## CRISPR-Cas9 in Genetic Engineering

In a laboratory, scientists will manufacture synthetic guide RNA to direct Cas9 to cut anywhere the scientists want. This is called **sgRNA** as it is made up of a **single RNA polymer** removing the need for separate tracrRNA & crRNA.