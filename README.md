# ChemicalFingerprints


This is a simple java package that uses [CDK](https://cdk.github.io/) library to extract fingerprint representations of chemicals from their SMILES strings.

## How to use?

java -jar fingerprinter.jar inputfile option

java -jar fingerptinter.jar "test.txt" 2 (for Pubchem) 

format your input file as,

ID < tab > SMILES
ID < tab > SMILES


## Fingerprints
*  [Fingerprinter](https://cdk.github.io/)  0
*  [PubchemFingerprint](https://cdk.github.io/) 1
*  [MACCS](https://cdk.github.io/) 2
*  [ExtendedFingerprint](https://cdk.github.io/) 3
