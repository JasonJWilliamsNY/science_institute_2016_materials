## Virtual Lab: Sequencing and Analysis of Mitochondrial DNA

#### Week of December 2nd, 2016

In this virtual laboratory, we will start to understand how DNA is sequenced and how we can analyze that sequence to generate hypotheses and conclusions. 

###Homework
Answer pre- and post-lecture questions and lab questions. 


**Time:** Including viewing the lectures, doing the reading and questions, this should require 60-120 minutes of time. 


**Pre-Lecture Questions:**
Come up with your answer (50 words or less ea.) to the following short-answer questions. Just give your best answer - 'right' or 'wrong' does not matter here. 

1. Why is the sequence (order) of DNA nucleotides important - how would you explain this to a 5th grader?


**Resource Links**

- Review how PCR works: [2D PCR animation/guide](https://www.dnalc.org/view/15924-Making-many-copies-of-DNA.html)
- See how Sanger sequencing works: [Sanger sequencing](https://www.dnalc.org/resources/animations/sangerseq.html)
- See how cycle sequencing (replaced Sanger) works: [Cycle sequencing](https://www.dnalc.org/resources/animations/cycseq.html)


### Lecture

DNA Sequencing allows us to "read" the nucleotides of a DNA sample. There are many ways different ways to sequence DNA and the technology has improved so much that what used to take decades of work and millions of dollars can be done in a few days for under a thousand dollars. 

For the type of sequencing done with our classroom samples, we need to first obtain a high quality sample of a relative short piece (~1000bp) of DNA. To do this, we used PCR (i.e. the PCR reaction using very specific primers allowed us to copy a short, specific region of DNA). We will learn how DNA Sequencing works and start the process of looking at our own DNA. 

Lecture Video: [Link]()

Other Lecture Links:

- [Human Genome](https://www.ncbi.nlm.nih.gov/projects/genome/guide/human/index.shtml)
- [Genome Sequencing Costs](https://www.genome.gov/sequencingcosts/)


**Post-Lecture Questions:**
1. What do the following components of the sequencing reaction do?
    - PCR product/template
    - sequencing primer
    - DNA polymerase
    - ddnpts 
2. What type of gel is used in the sequencing electrophoresis and why do we use this type of gel?
3. Why do we use ddntps that are fluorescently labeled?
4. What is a chromatogram?
5. Is the base calling process perfect?


### Virtual Laboratory Exercise: Examine your mitochondrial DNA

**Pre-requisite:** You must sign up for a CyVerse account and request access to **DNA Subway**:

1. Visit the user portal at: [https://user.cyverse.org/](https://user.cyverse.org/)
2. Register for a CyVerse account using your YUHSG email account
3. Check your email for an account confirmation link and follow the confirmation instructions. 
4. Log in to [User Management](https://user.cyverse.org/dashboard/) and open the Apps & Services tab.
5. Go to the Available Services section at the bottom.
6. Find "DNA Subway" and click Request Access. 
7. You may need to fill in some information and you can indicate that you are using DNA Subway in School. 

**Note:** If you have trouble with anything in the registration process please email me. If there are difficulties, you will still be able to use DNA Subway as a guest until we resolve the issue. 

#### Analyzing MT DNA with DNA Subway

##### Viewing Sequence

1. Login to [DNA Subway](http://dnasubway.iplantcollaborative.org/) using your CyVerse account. If you have trouble getting an account, you can click 'Enter as Guest'
2. Once you are logged in click the blue square 'Determine Sequence Relationships'
3. Under 'Select Project Type' choose 'mtDNA'
4. Under 'Select Sequence Source' choose 'Import trace files from DNALC'
5. Select the entry for tracking number **10-355424637**, 11/29/2016, Jason Williams. 
6. Click 'Select All' to add the available sequences, then click 'Add selected files.'
7. Under 'Name Your Project' enter "Mitochondrial DNA Lab, Nov. 2016", then click 'Continue'
8. On the DNA Subway screen you will see various analysis steps, click on 'Sequence Viewer' to view your DNA Sequence. 
9. Clicking on the name of any sequence in the Sequence Viewer will allow you to view that sequence's chromatogram readout. Answer lab question 1
10. Exit the 'Sequence Viewer' window

##### Cleaning Sequence

1. Click on 'Sequence Trimmer' to run the tool, then click again to view the result. Answer lab question 2
2. Exit the 'Sequence Trimmer' window

##### Find Sequence Matches

1. Click on the 'BLAST' tool. 
2. Next to the name of your sequence click 'BLAST'; use the result to answer lab question 3. 
3. Exit the 'BLAST' window

##### Compare sequences

**Lab Questions:**
1. Click on 'Select Data'
2. Click on 'Select All' and the click on 'Save Selections'
3. Click on 'MUSCLE' to run the tool, click again to view the results. 
2. In the 'Alignment Viewer' window click 'Trim Alignment'
3. Click on the 'ATGC' box to view details of the sequence comparison. Answer the remaining lab questions. 

1. Approximately how many basepairs of good sequence did your experiment produce?
2. What does the 'Sequence Trimmer' tool do?
3. According to the BLAST tool, what species does your sequence match to?
4. The 'Consensus' sequence in the alignment viewer is the sum of all of the nucleotides we are comparing - e.g. the for every nucleotide, in all of the sequences we are comparing, if an individual sequence and the consensus are the same we see no nucleotide letter in the individual sequences' row. If there is a difference, we will see what nucleotide the sequence has compared to the sequence. 
    a.  What types of changes do you see between the consensus and your sequence? List them all in order by writing what the consensus nucleotide is, and what your nucleotide change is (this question will be demonstrated in our lecture video).  
