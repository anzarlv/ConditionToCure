# Overview
## Purpose
Evaluate skills in handling biological and clinical data using modern data engineering tools and practices

## Description
Work with biological data that requires integration, transformation, and analysis using various technologies commonly used in bioinformatics

## Technical requirements
- Python 3.10 or higher
  
- Basic understanding of biological data formats and concepts
  
- RESTful services and working with web APIs
  
- Basic understanding of ontology, semantic formalism, and thesaurus such as MESH

## Goal
Create a data extraction protocol to retrieve information from clinicaltrials.gov

## Key output
Single function that accepts a str argument representing the "Conditiion or Disease", the exepcted output of the function is:

{
    "clinical_trials": [...],
    "indications": [...],
    "treatments": [...]
}
