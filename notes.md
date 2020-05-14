Geneious for Genomics Analysis
================
Poorani Subramanian
2020-02-25

  - [BCBB Science Support](#bcbb-science-support)
  - [Geneious online help](#geneious-online-help)
  - [Primer Design](#primer-design)
  - [CRISPR Site Finder](#crispr-site-finder)
  - [Switching from Vector NTI](#switching-from-vector-nti)
  - [Contact](#thanks)

#  BCBB Science Support	 

  - <bioinformatics@niaid.nih.gov>
  - [https://bioinformatics.niaid.nih.gov/services](https://bioinformatics.niaid.nih.gov/services)
  - Consultations, training, collaborations for bioinformatics
    ![](assets/img/image9.png)


#  Geneious at NIAID 

- Can install through Self-Service app
	- Need to also install the Key Server/K2 Client – *this provides the license*
- Technically, if you have K2 Client installed, you can also install newest version of Geneious through Geneious website
- NIAID has 30 "floating" licenses – 30 people can use simultaneously
	- If you ever notice that the license doesn't work or you get booted, note roughly the time, and email [bioinformatics@niaid.nih.gov](mailto:bioinformatics@niaid.nih.gov)
	- We can re-evaluate if we need more licenses
- If you need more computer power than your desktop/laptop allows, please let us know as well.

---
#  Geneious online help 

  - Tutorials - <https://www.geneious.com/tutorials/>
  - Manual - <https://assets.geneious.com/manual/2020.0/index.html>
  - Tips - <https://www.geneious.com/resources/tips-tricks/>
    

---
#  Primer Design 

  - Geneious uses Primer3 for primer design - v 2.3.7 modified
  - current version of Primer3 is 2.5.0 released Aug 2019
  - NC_007596
[2.5.0 released Aug 2019](https://github.com/primer3-org/primer3/releases)

---
#  Design New Primer Pair – other options 

  - Design for Sequencing – tile amplicons across a region
  - A mispriming library is a set of sequences (usually repeats) which
    the primers should not bind to. – Included libs are from Primer3

---
#  CRISPR site finder 

  - searches for gRNA sites in your selected sequences, and scores them based on on-target sequence features (activity score) and oﬀ-target interactions (specificity score).
  - target sequence <= 1000bp

---
#  CRISPR Site Finder - activity scoring

  - Activity scoring for Cas9 CRISPR
      - method from Doench et al. (2014): analyzes the one- and two-base
        features of the gRNA, as well as the GC content, to generate the
        score. Scores are between 0 and 1, with a higher score denoting
        higher expected activity.
      - ambiguous bases will not contribute to this score.
      - Not available for Cpf1 [Doench et
        al. (2014):](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4262738/)

---
#  CRISPR Site Finder - specificity scoring

 - Specificity scoring
   - https://assets.geneious.com/manual/2020.0/static/GeneiousManualse79.html

---
#  Switching from Vector NTI 

  - Exporting from Vector NTI: Download Exporting tool from ThermoFisher
    <https://www.thermofisher.com/us/en/home/life-science/cloning/vector-nti-software.html>
  - Importing into Geneious:
    <https://www.geneious.com/features/vector-nti-importer/>
      - Should be able to just drag your database over

---
#  Thanks\! 

  - <bioinformatics@niaid.nih.gov> - our group email – best to email
    here for help\!
  - <https://github.com/niaid/geneioustraining> – links to materials

    
