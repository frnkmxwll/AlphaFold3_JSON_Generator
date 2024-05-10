# Streamline AlphaFold3 Protein Modeling with Easy JSON Generation
![image](https://github.com/frnkmxwll/AlphaFold3_JSON_Generator/assets/1188958/04cfb124-8243-4ad4-87b9-b8dd0df19744)

## Introduction

Simplify your AlphaFold3 protein structure prediction workflow with this convenient Google Sheets template. Effortlessly generate the required JSON input files for batched AlphaFold3 Server jobs, streamlining the process of defining your protein sequences, ions, ligands, DNA, and more. 

## Features

* **Intuitive Interface:** User-friendly Google Sheets environment for easy protein modeling setup.
* **JSON Automation:** Automatically generates AlphaFold3-compatible JSON files based on your inputs.
* **Customizable:** Define your protein sequences, ions, ligands, DNA, and other parameters.
* **Batch Processing Ready:** Designed to support batch job submission to the AlphaFold3 Server.
![image](https://github.com/frnkmxwll/AlphaFold3_JSON_Generator/assets/1188958/864cb6ea-c9ca-41b1-8a1e-0acbc5413b6a)


## Getting Started

1. **Make a Copy of the Template:** Access the template at [https://docs.google.com/spreadsheets/d/11ErTVFUwQ7eb6z7naL6iHcLU2AkLPF35lxFEtk9pqBo/edit#gid=0](https://docs.google.com/spreadsheets/d/11ErTVFUwQ7eb6z7naL6iHcLU2AkLPF35lxFEtk9pqBo/edit#gid=0) and create your own copy.
2. **Input Your Protein Data:** Fill in the necessary fields in "Protein Lookup Table" tab:
    * Protein Sequences: enter the single-letter amino acid sequence or paste in the contents of a FASTA file. Use only standard single letter codes (nonstandard ones like B, J, O, U and X are unsupported)
    * For ligands, or ions select the desired entity from the list of supported types. The three letter codes displayed in the UI come from Protein Data Bank’s Chemical Component Dictionary.
    * DNA sequences, if applicable
3. **Generate Your JSON:**  The template will automatically create a valid JSON file compatible with the Alpha Fold3 Server. Simply copy the resulting JSON in the "Final Job JSON:" cell and paste into a text file saved with a .JSON extension.
4. **Submit to AlphaFold3:** Follow the instructions on the AlphaFold3 Server ([https://golgi.sandbox.google.com/about](https://golgi.sandbox.google.com/about)) to submit your batch job using the generated JSON file.

## Notes

* Current template does not handle RNA sequences, nor post-translational modifications.
* The AlphaFold3 Server is a powerful tool for protein structure prediction. Using this Google Sheets template can help you to quickly set up and submit your modeling jobs. 
* For detailed instructions and guidance on AlphaFold3 and its usage, please refer to the official DeepMind documentation ([https://github.com/google-deepmind/alphafold](https://github.com/google-deepmind/alphafold)).

## Community

I welcome your feedback and contributions to improve this template! Feel free to raise issues or submit pull requests on this GitHub repository. Let's collaborate to make protein modeling more accessible.

## Disclaimer:

* This template is provided as a tool to assist with AlphaFold3 setup. Please exercise caution and review the generated JSON file carefully before submission.
* It is always recommended to consult established protein modeling resources and best practices to ensure the accuracy and interpretation of your modeling results.

**I hope this is a great starting point. Please let me know if you'd like any additions or changes to the content!** 
