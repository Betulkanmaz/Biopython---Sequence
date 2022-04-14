# Biopython---Sequence
Alphabet Module and Basic Operations. 

# Bioinformatics?
  The mathematical, statistical and computing methods that aim to solve biological problems using DNA and amino acid sequences and related information is known as Bioinformatics.
# Science of Bioinformatics?
  The mathematical, statistical and computing methods that aim to solve biological problems using DNA and amino acid sequences and related information is known as Bioinformatics.
  
# Biopython?
  Biopython is a large open-source application programming interface (API) used in both bioinformatics software development and in everyday scripts for common bioinformatics tasks. Basically, Biopython is a collection of python modules that provide functions to deal with DNA, RNA & protein sequence operations such as reverse complementing of a DNA string, finding motifs in protein sequences, etc. It provides lot of parsers to read all major genetic databases like GenBank, SwissPort, FASTA, etc., as well as wrappers/interfaces to run other popular bioinformatics software/tools like NCBI BLASTN, Entrez, etc., inside the python environment. It has sibling projects like BioPerl, BioJava and BioRuby.
  
  # Biopython Sequence
    A sequence is series of letters used to represent an organism’s protein, DNA or RNA. It is represented by Seq class. Seq class is defined in Bio.Seq module.
    Each Seq object has two important attributes −
      * data − the actual sequence string (AGCT)
      * alphabet − used to represent the type of sequence. e.g. DNA sequence, RNA sequence, etc. By default, it does not represent any sequence and is generic in nature.
   
 # Alphabet Module
    Seq objects contain Alphabet attribute to specify sequence type, letters and possible operations. It is defined in Bio.Alphabet module.Alphabet module provides below classes to represent different types of sequences. Alphabet - base class for all types of alphabets.
      * SingleLetterAlphabet - Generic alphabet with letters of size one. It derives from Alphabet and all other alphabets type derives from it.
      * ProteinAlphabet − Generic single letter protein alphabet.
      * NucleotideAlphabet − Generic single letter nucleotide alphabet.
      * DNAAlphabet − Generic single letter DNA alphabet.
      * RNAAlphabet − Generic single letter RNA alphabet.
      
    Biopython module, Bio.Alphabet.IUPAC provides basic sequence types as defined by IUPAC community.
