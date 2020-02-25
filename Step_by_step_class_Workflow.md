**Primer design tutorial**

1.  \[Optional\] drag zipped tutorial over

2.  Start with exercise 5 design of PCR primer pairs
  
      - They have already downloaded sequences, etc.  But in real life,
        we would have to get the sequences into Geneious ourselves.

3.  Make a separate new folder - NIAID\_Training (File -\> New Folder)

4.  Search NCBI -\> Nucleotide for NC\_007596

5.  Drag sequence to NIAID\_Training

6.  Familiarize oursevels with the different tabs
  
      - Sequence view - zoom in to see letters
      
      - Annotations - tabular view
      
      - Text view - genbank file
      
      - Lineage - important later to trace your work
      
      - Info - can add specified metadata - and make your own fields
        with Edit
        
          - click on fields to edit

7.  Select COX1 gene - either in the picture or clicking annotation or
    searching

8.  Click Primers
  
      - Geneious uses Primer3 for primer design - v 2.3.7 modified
      
      - current version of Primer3 is [<span class="underline">2.5.0
        released Aug
        2019</span>](https://github.com/primer3-org/primer3/releases)
      
      - 3 options:
        
        1.  > Design New - design based on region
        
        2.  > Design with existing - forward primer already have - want
            > to make a reverse primer to go with it
        
        3.  > Design for Sequencing – tile amplicons across a region

9.  Design New - (Reset to Defaults for the Class - gear bottom left)
  
      - Task – generic
      
      - Included region checked - primers will bind inside the region,
        if you want specific sub-region, put that under target region -
        primers will not bind in this region
      
      - Product size – 200-300 (degraded DNA?) - optimal 250
      
      - Primer - Size Max 24 - Tm Min 54
      
      - Formula Santa Lucia is newer
        http://primer3.org/manual.html\#PRIMER\_TM\_FORMULA
      
      - Characteristics 0 Max Tm Difference 2
      
      - A mispriming library is a set of sequences (usually repeats)
        which the primers should not bind to. – Included libs are from
        Primer3
      
      - Click OK

10.  Click Save

11.  Click on Annotations to see primers and characteristics

12.  Click on primer set 5498 and 5747 - each primer -\> Extract - label
    COX1

13.  Click on the primer sequence in the sequence list at top look at
    different tabs including Lineage

14.  Test primer for specificity of other species - not as good as NCBI
    Primer BLAST

15.  File -\> Import -\> multiple files -\> GeneiousTraining
    
- DQ316068.gff3 and DQ316068.fasta (Asiatic elephant)
    
16.  Imports as single record

17.  Test the primers - select COX1 gene

18. Primers -\>Test with Saved Primers
  
      - Source current folder - Choose - select primers
      
      - Annotation - check all boxes
      
      - Region - Find primers that bind inside the selected region
      
      - Allow 2 mismatches - not same species - no mismatches in last
        5bp

19. Zoom in to each primer to see mismatches 

20. Click Save

21. Select both primers, then up top - Primers -\> Extract PCR product
  
      - Extract primer bases

22. Click on PCR product -\> Info -\> Show OPtions

23. Importing your own set of primers 
  
      - at least 3 column table - Name Sequence Description
      
      - tab-delimited or csv

24. File -\> Import -\> CSV/TSV sequence table - must be saved as .tsv
    or .csv (not .txt as in Excel)

25. Determine characteristics - will do Tm calculation

**Workflows**

1.  KY616974.1 - import genbank file or search NCBI

2.  Click on Workflows – Manage Workflows – New Workflow

3.  Build workflow - for each document (will run workflow on each
    document/sequence/object you have selected) - Test with saved primer
    - extract pcr product

**CRISPR Site Finder tutorial**

  - Good background info <https://www.addgene.org/guides/crispr/>

  - Note that activity (on-target) scoring methods for Cpf1 sites are
    not currently available.

  - Geneious manual chapter:
    <https://assets.geneious.com/manual/2020.0/static/GeneiousManualse79.html>

  - Cpf1 used for larger regions

  - Import yeastgenomes.geneious – will save as yeast\_genome folder

  - highlight all the sequence/chromosome files - annotations tab -
    search
    
      - trp1 and extract the gene

  - Click on TRP1 sequence – Cloning - CRISPR Site finder
    
      - Can change PAM sequence if needed – preview is below
