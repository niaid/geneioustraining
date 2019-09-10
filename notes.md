# Geneious an NIAID

  - [Installation](#installation)
  - [Why I Like Geneious](#why-i-like-geneious)
  - [Some of the available Tools and
    Workflows](#some-of-the-available-tools-and-workflows)
  - [When you Open Geneious for the First
    Time](#when-you-open-geneious-for-the-first-time)
  - [Primer Tutorial Detours](#primer-tutorial-detours)
  - [Plant Evo Tutorial Exercises](#plant-evo-tutorial)

## Installation

- Install it through Self Service
  - Also install K2Client.  May need to restart computer to get the "KeyServer" to start.
  - Once the KeyServer is started, you do not need to put in any license information when you open Geneious, but **you must be connected to the NIH network/VPN**.
- We are still trying to gauge how much interest and how many users we will have.
- NIAID has 30 floating licenses.  So, 30 people can use at the same time across the institute (we got special extra ones for this training). If there are more than 30 people using it simultaneously, you may get booted off.  If this happens, and it impedes your work, please email us at bioinformatics@niaid.nih.gov .  We would like to know if there is increased usage.
- If you find that you would like to use Geneious to analyze larger data sets or to do workflows that your computer is not powerful enough to complete in a timely manner, please let us know.  There is a server version of Geneious which allows you to connect to a remote server to do more computationally intensive tasks.  If there is interest in using this version, we could request licenses for it.

## Why I Like Geneious

- It's ok to use a GUI tool if it makes your life easier.
- A lot of the tools it implements, are ones that are considered the best or standard in the field - I use them anyway outside of Geneious on the command line or in Locus.
- You can make "workflows" or pipelines stringing together different steps easily.

## Some of the available Tools and Workflows

- [Sequence QC ](https://support.geneious.com/hc/en-us/articles/360003146291-NGS-Pre-Processing-and-Analysis)
- [Mapping and De Novo Assembly](https://support.geneious.com/hc/en-us/articles/360003146331-Mapping-and-De-Novo-Assembly)
- [Sequence Alignment](https://support.geneious.com/hc/en-us/articles/360003125292-Sequence-Alignment)
- [Interface to searching NCBI and NCBI-BLAST](https://support.geneious.com/hc/en-us/articles/360003146391-Searching-and-BLAST)
- [Sequence Analysis](https://support.geneious.com/hc/en-us/articles/360003146431-Sequence-Analysis) - including some metagenomics
- [Variant Calling and Expression Analysis](https://support.geneious.com/hc/en-us/articles/360003125672-Variant-Calling-and-Expression-Analysis) - RNAseq
- [Molecular Cloning and Primer Design](https://support.geneious.com/hc/en-us/articles/360003125692-Molecular-Cloning-and-Primer-Design)
- [Phylogenetics](https://support.geneious.com/hc/en-us/articles/360003146851-Phylogenetics)

### Plugins

- Geneious Prime -> Preferences -> Plugins and Features
- Not all the tools are installed with Geneious - can choose which extra ones you want
- [Plugins Website](https://www.geneious.com/plugins/) 
  - directory on the web with help, citations, and links
  - has some additional plugins not in the GUI
  - To install plugin from the web: Download gplugin file.  Then choose Geneious Prime -> Preferences -> Plugins and Features -> Install plugin from a gplugin file...
- Example, try installing MAFFT

## When you Open Geneious for the First Time

- It will ask you where you want to store your data.  You can choose default or wherever you would like.  They recommend NOT to store it in a "cloud" directory (like your OneDrive folder).  
- **Left panel is Sources** - data sources, both Local (stored on your computer) and remote (like NCBI)
  - "Sample Documents" has examples of different data formats
- Importing
  - Auto Detect usually works.  Sometimes if file extension is non-standard, may have to specify.
  - Example data in Geneious directory/Sample Importable Files
  - **Tip**: BEFORE you import, make sure you have created and selected the folder under Sources where you want the data to be imported to.  
  - Importing from NCBI - select database, search for accession (easiest) - KY888121
    - To save document locally, copy it to one of your Local folders
- If, after a while, your Geneious data folder seems unusually large, try erasing your Deleted Items.



## Primer Tutorial Detours

### Info and Provenance

1. Select DTU76545 -> Info
2. Properties & HIstory - provenance of data
3. After extracting PCR product, check info and history
4. Lineage - shows steps to produce file, and steps that may have been take afterwards

### Exporting documents

1. Select mammoth COX1 primers.
2. File -> Export -> FASTA

### Very simple workflow

1. Click on Workflows -> Manage Workflows
2. New Workflow
3. Add Step -> Add Recently Used Operation -> Test with Saved Primers
4. Add Step -> Add Recently Used Operation -> Extract PCR Product
5. Don't expose options you want to keep the same.  Export workflow to save.  Can run on different datasets - ensures parameters are always the same.  Keep for your records and share.

   

## Plant Evo Tutorial

- Has some built-in exercises

**Extra: Building a workflow**

- Can you build your own workflow which 
  - does the MSA and then builds the tree?
  - always uses the Jukes-Cantor distance and UPGMA to build the tree?
  - or uses MAFFT instead of MUSCLE? ([my solution](workflows/Align DNA with MAFFT and build tree with Jukes-Cantor distance and UPGMA method.geneiousWorkflow))
- Using existing workflow - modify with your parameters and then export - maybe most common use case
  - View/edit - Create editable copy
- From scratch to practice how to set up options










