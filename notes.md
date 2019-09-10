---
titleblock: Geneious Notes
toc: true
toc-depth: 2
---



## Geneious at NIAID

- Install it through Self Service
- We are still trying to gauge how much interest and how many users we will have.
- NIAID has 30 floating licenses.  So, 30 people can use at the same time across the institute (we got special extra ones for this training).  You do not need to put in any license information if you use Geneious installed from Self Service, but **you must be connected to the NIH network/VPN**.
- If there are more than 30 people using it simultaneously, you may get booted off.  If this happens, and it impedes your work, please email us at bioinformatics@niaid.nih.gov .  We would like to know if there is increased usage.
- If you find that you would like to use Geneious to analyze larger data sets or to do workflows that your computer is not powerful enough to complete in a timely manner, please let us know.  There is a server version of Geneious which allows you to connect to a remote server to do more computationally intensive tasks.  If there is interest in using this version, we could request licenses for it.

## Why I Like Geneious

- It's ok to use a GUI tool if it makes your life easier.
- A lot of the tools it implements, are ones that are considered the best or standard in the field - I use them anyway outside of Geneious on the command line or in Locus.
- You can make "workflows" or pipelines stringing together different steps easily.

## Some of the available Tools and Workflows

- Sequence QC 

### Plugins

- Geneious Prime -> Preferences -> Plugins and Features
- Not all the tools are installed with Geneious - can choose which extra ones you want
- [Plugins Website](https://www.geneious.com/plugins/) 
  - directory on the web with help, citations, and links
  - has some additional plugins not in the GUI
  - To install plugin from the web: Download gplugin file.  Then choose Geneious Prime -> Preferences -> Plugins and Features -> Install plugin from a gplugin file...

## When you Open Geneious for the First Time

- It will ask you where you want to store your data.  You can choose default or wherever you would like.  They recommend NOT to store it in a "cloud" directory (like your OneDrive folder).  
- Left panel - data sources, both Local (stored on your computer) and remote (like NCBI)
  - "Sample Documents" has examples of different data formats



## Primer Tutorial Detours

### Info and Provenance

1. Select DTU76545 -> Info
2. Properties & HIstory - provenance of data
3. After extracting PCR product, check info and history

### Exporting documents

1. Select mammoth COX1 primers.
2. File -> Export -> FASTA

### Very simple workflow

1. Click on Workflows -> Manage Workflows
2. New Workflow
3. Add Step -> Add Recently Used Operation -> Test with Saved Primers
4. Add Step -> Add Recently Used Operation -> Extract PCR Product
5. Don't expose options you want to keep the same.  Export workflow to save.  Then can run on different datasets - ensures parameters are always the same.
6. 













