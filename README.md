# BLAST-Based-Sequence-Identification
# Identify an Unknown Biological Sequence Using NCBI BLAST

## Tool Used
NCBI BLAST

---

## Step 1: Observe the Given Sequence

**Selected Sequence:** Sequence 1

**Observation:**
- The sequence contains only A, T, G, and C.
- No amino acid letters (such as M, L, K, F, W) are present.

**Prediction:**
This sequence is a **DNA sequence**.

---

## Step 2: Choose the Correct BLAST Program

Since the sequence is DNA, the appropriate BLAST tool used is:

- **BLASTn (Nucleotide BLAST)**

BLAST website:  
https://blast.ncbi.nlm.nih.gov

---

## Step 3: Paste the Sequence into BLAST

Steps followed:
1. Open BLASTn
2. Paste the given DNA sequence into the “Enter Query Sequence” box
3. Keep all parameters at default settings
4. Click on **BLAST**
5. Wait for the results to load

---

## Step 4: Identify the Best Match

From the BLAST results, the top hit was recorded.

**Results:**
- Gene Name: Glycoprotein (GP) gene
- Organism: Zaire ebolavirus
- Database Used: Nucleotide collection (core_nt)
- Percentage Identity: 100%
- E-value: 4e-109

**Interpretation:**
- An E-value close to 0 indicates a very strong match
- A 100% identity confirms reliable identification of the sequence

---

## Step 5: Verify Using Alignment

**Alignment Observations:**
- Complete matching regions
- No significant gaps or mismatches observed

**Conclusion:**
Yes, the alignment supports that this is the same gene.

---

## Step 6: Identify the Biological Function

**Biological Role:**
- The glycoprotein (GP) gene of Zaire ebolavirus is responsible for viral attachment and entry into host cells.
- It plays a key role in viral infectivity and pathogenicity.

**Functional Category:**
- Disease-related
- Viral entry and host interaction

---

## Step 7: Classification & Interpretation

- Sequence Type: Gene
- Organism Type: Virus
- Classification: Viral genome
- Conservation: Conserved within Ebola virus species

---

## Step 8: Final Conclusion

The given unknown sequence is identified as a gene from Zaire ebolavirus.
BLAST analysis shows a percentage identity of 100% and an E-value of 4e-109,
indicating a very strong and reliable match.

---

## BLAST Result Screenshot

![BLAST Result Screenshot](blast_result.png)
