# SARS-CoV-2-mutation-rate-model-using-biopython
This is not a scientific mode but a representation of it and i don't recommend it to be used for scientific purposes because this model has to be validated in real time which may take time.

```
1. Open in Jupyter Notebook.
2. Install the packages in the First cell.
3. (Optional) I recommend you to enable the code folding because the genome sequences are pretty big (29903 bytes).
```
### Things to be done
- [x] Collect Gnome Sequences - **Done** (Only 5 countries)
- [x] Calculate the Avg Size of 5 Genomes - **Done**
- [x] Calculate the Pairwise score or Similarity between genomes - **Done** (Needleman-Wunsch Algorithm)
- [x] Calculate the mutation rate by comparing the base pairs - **Done**
- [ ] Create a model for Recombinant adeno-associated virus (rAAV) to accept two RNA genomes and simulate the stability - **Nope**
- [ ] Compare SARS-CoV-2 with MERS and SARS, if possible find the differentiated sequence with other strains - **Nope**
- [ ] Will be added in the future.

### Analysis
- There is no equivalent to execution, we are reverse engineering a CAD format
- Static analysis, looking at the DNA, protein structure prediction, FLIRT signatures, etc...
- Simulation doesn't seem to work yet
- Tons of in system dynamic analysis, but the tools are crap
- Runs more like FPGA code, all at once, no serial execution (what are the FPGA re tools?)

### Let's Work together
Pm me: zeroerror.444@gmail.com

### References
- Collect Genomes form here: [NIH](https://www.ncbi.nlm.nih.gov/genbank/sars-cov-2-seqs/)
- Coronavirus Pathogenesis -- https://www.sciencedirect.com/science/article/pii/B9780123858856000092
                              https://www.futuremedicine.com/doi/pdf/10.2217/fvl-2018-0008
- TextBooks and Miscellaneous Stuff
*Molecular Biology of the Cell*
1. https://ocw.mit.edu/courses/biology/7-012-introduction-to-biology-fall-2004/index.htm
2. https://ocw.mit.edu/courses/biology/7-014-introductory-biology-spring-2005/index.htm

### Other Things
This is a project came out of curiosity and if you are expert in micro biology or molecular biology feel free raise an issue if you find anything odd.Thank you.
