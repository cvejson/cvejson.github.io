# JSON Schema for CVE ID JSON File Format

CVE JSON is the JSON representation of CVE ID entries and related information provided by CVE Naming Authorities.

CVE JSON is well suited to represent a single vulnerability and its attributes in a machine readable standard format.

This project aims to incorporate improvements to develop the next proposed version of the specification.

## Proposed JSON Schema specification development rules:

1. Improvements shall be classified as "Additions", "Deletions", "Modifications".
	* Additions and Deletions may not require changes to existing JSON producers and consumers.
	* Modifications change the semantics and meanings of the specification and a JSON producer or consumer may need changes.

2. Each proposed modification shall contribute to an up-converter. This should help convert a set of CVE JSON documents from and previous version to the next version.

3. Make use of the JSON schema Validation keywords to specify constrains.

4. Validation rules that can not be represented in JSON schema shall be listed as number rules.

5. Schema version is upgraded to release candidate (RC) status at known cadence of __ (6?) months, if there have been changes that have accumulated over that period. CVE JSON producers and consumers are expected to test 

6. Schema version in release candidate (RC) status becomes the official version after ___ (3) months.
