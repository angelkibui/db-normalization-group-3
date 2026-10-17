# db-normalization-group-3

Construction project data, normalised from 1NF through 4NF.

| Folder | What this stage does |
| --- | --- |
| 1NF | Splits pipe-separated values and keeps source row references. |
| 2NF | Separates project, worker and supplier details from relationships. |
| 3NF | Moves client contacts and supervisor phones into their own tables. |
| BCNF | Checks that every determinant in the adopted dependency rules is a key. |
| 4NF | Checks that independent lists are stored in separate tables. |

Read **normalization_explanation.docx** for examples, keys, relationships and assumptions.

The 3NF, BCNF and 4NF folders each contain 12 CSVs. Their data and structures match because the 3NF design already meets the later requirements under the rules explained in the document. Skills, certifications and supplier phones were separated in the earlier stages.

The original 1NF and 2NF files are unchanged. File names keep the existing TableName_Stage.csv pattern.
