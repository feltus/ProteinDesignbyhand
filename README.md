# Computational Practice: Design a protein de novo with a specific secondary structure
##  Lab Overview
If we could accurately predict protein structure, we would know the “shape” of the major tools that make up an organism. This would allow the in silico modeling of biomolecular systems and facilitate rational drug design.

If we knew how the tools change “shape” when DNA and epigenetic information changes relative to normal, we would have a better understanding of the biochemical mechanisms underlying phenotype and disease.

A first step in protein structure prediction is finding secondary structures that are s## le local conformations of a polypeptide due to the action of hydrogen bonding.   Here are three classes of protein secondary structure:

alpha-helices
* Spiral-like structure
* 3.6 amino acids per turn (short range interactions)
* H-bonds between residues i and i+4

beta-sheets
* Two or more beta-strands with zigzag conformation
* H-bonds between residues of adjacent strands
* H-bonds can be long range interactions

beta-turn
* A region of the protein involving four consecutive residues where the polypeptide chain folds back on itself by nearly 180 degrees 

In this lab you will design a protein with a fixed number of secondary structures.  The videos in this skill might help you find the propensity of amino acids in know secondary structures to help with your design.

##  Lab Objectives:
* Design a protein with a predicted number of secondary structures de novo

Follow these lab instructions:

###  Task A: 
Design a protein de novo.

Using what you know about secondary structures in general and amino acid propensity in secondary structures:

#### Step A. 
Design a protein from scratch that contains this secondary structure pattern: three beta-strands flanked by two alpha helices.   Save the protein sequence in FASTA format.  
#### Step B. 
Use Jpred4 software (http://www.compbio.dundee.ac.uk/jpred)  to see if your prediction was correct.  If you’re the protein was incorrectly designed, then please try again 😊.

###  Task B: 
(Optional) Human-assisted structure prediction.  

On your personal computer or the Linux Desktop, install Foldit, a gaming-based structure refinement program (https://fold.it/).  Do the tutorials if you want to learn more about protein folding and how humans can help find the optimal fold.
