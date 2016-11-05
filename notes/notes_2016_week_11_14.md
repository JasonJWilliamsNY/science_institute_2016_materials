## Virtual Class Notes - Introduction to PCR and PCR Virtual Lab

#### Week of November 14th, 2016

**Time:** Including viewing the lectures, doing the reading and questions, this should require 60-120 minutes of time. 


**Come up with your answer (50 words or less ea.) to the following short-answer questions**

Just give your best answer - 'right' or 'wrong' does not matter here. 

1. What is information?
2. What is a gene?
3. What is DNA and how does it relate to genes?
4. If you had to make a photocopy, write down everything you would need to make that copy.  

**Vocabulary**

Look up and define the following terms
1. Gene
2. Genome
3. Chain Reaction
   
### Lecture

Polymerase Chain Reaction (PCR) is one of the most important techniques in the molecular biology toolkit. PCR allows us to replicate a <u>specific</u> piece of DNA in the genome. Replicating a piece of DNA is the first step to analyzing it (via [DNA sequencing](https://en.wikipedia.org/wiki/Sanger_sequencing)). Replicated DNA is also often one of the first steps to editing DNA for subsequent experiments. 

[Lecture Link on Google Drive]()

**Resource Links**

- [Searching for DNA sequences before PCR](https://www.dnalc.org/view/15127-Tedious-process-of-early-gene-hunting-Mary-Claire-King.html)
- [Kary Mullis, explains PCR](https://www.dnalc.org/view/15140-Making-many-DNA-copies-Kary-Mullis.html)
- [2D PCR animation/guide](https://www.dnalc.org/view/15924-Making-many-copies-of-DNA.html)
- [3D PCR animation](https://www.youtube.com/watch?v=2KoLnIwoZKU)

**Post-lecture questions**

In the PCR reaction, what do the following components of the reaction do?
1. DNA polymerase
2. Nucleotides


### Virtual Laboratory Exercise: Finding PCR Primers

1. Go to OMIM (do you know what [OMIM](https://omim.org/about) is?); we will visit their search engine: *[OMIM](https://omim.org/)*
2. Search for a disease like 'parkinson disease' (choose another disease for your own work on this exercise)
3. From this search, you will get a list of results that are related to you query. Choosing 'parkinson disease' we will choose one of the results: [https://omim.org/entry/611139?search=heart%20disease&highlight=heart%20disease](https://omim.org/entry/611139?search=heart%20disease&highlight=heart%20disease)
    - **Tip:** On the right-hand side of your search results there are some additional links. Only choose search results where you see 'Gene Tests' for that result in the right-hand column. 
    - **Record:** When you click on your result, you should find the following information at the top of the page: "HGNC Approved Gene Symbol". Record and save that Gene Symbol - this is the name of the gene you found.
4. For your chosen gene, read the 'Description' section to learn a little about your gene. Scroll down to the 'Gene Function' section and you will see descriptions of several experiments the lead researchers to believe that this gene is associated with a gene. **Use the 'Gene Function' section to answer questions below.**
5. To find the sequence of the gene:
    1. After 'HGNC Approved Gene Symbol' the gene name should appear as a link. Click on this link. 
    2. You will be navigated to a 'HGNC' page. 
    3. Scrolling down to the 'External Links' section, under 'Nucleotide Sequences' look for and click on a link to GenBank. 
    4. Your GenBank page should look like [this example](https://www.ncbi.nlm.nih.gov/nuccore/L08850) for the Human AD amyloid gene.
    5. Near the name at the top of the GenBank page there is a link called 'FASTA'; click on that link and you should get a page [that looks like this](https://www.ncbi.nlm.nih.gov/nuccore/437364?report=fasta).  
    6. This is DNA sequence that is written in a special way called the [FASTA format](https://en.wikipedia.org/wiki/FASTA_format). 
    7. Starting with the '>' sign highlight that first line (which is the name of the sequence) followed by all of the DNA letters (nucleotides). 
    8. Copy this sequence to your clipboard and **Record** this sequence by saving it as a text file. 
6. Go to the [Primer3](http://bioinfo.ut.ee/primer3/) website. This website takes a DNA sequence in FASTA format, and helps select primers that within that DNA based on several factors:
    - There are two primers needed at the beginning and end of the DNA sequence 
    - Primers can't be too short (~ < 15 nucleotides) or too long (~ > 30 nucleotides)
    - Several other factors which we can learn about later
7. On the Primer3 website at the top of the page there is a box to paste in your DNA sequence. 
8. Below the box where you pasted your sequence, click the 'Pick Primers' button. Use your results, and other items you recorded above to answer the following questions:

**Lab Questions:**

1. What disease did you search for?
2. What was the name of the Gene you selected?
3. What can you say about how researchers determined this gene was involved in your disease?
4. What is the sequence of your Gene?
5. What were the left and right primers selected by Primer3 (Give the DNA sequence)
6. Given the primer start and end position (these are the numeric positions your primers align to), how much DNA sequence would be amplified by these primers (hint: subtraction is involved). 

**Supplementary Question: On a scale of 1-10, how difficult was this virtual class? What is the most interesting thing you learned?**



#### Assignment Due Date
Submit the pre- and post-lecture questions by email by 5:00PM November 21st. 