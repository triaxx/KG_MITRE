# KG_MITRE

Knowledge graph experiments using:

- MITRE ATT&CK
- CVE
- CWE

KG_M (procedures): 2 separate graphs: (i) MITRE ATT&CK graph (techniques with description but no embedding model included, sepearete procedure node with description), (ii) CVE(CISA, NVD from 2015, OSV) + CWE

KG_MITRE_v1.1 CVE (All): MITRE <- CAPEC -> CWE -> CVE

KG_MITRE_v2.0 YearFilteredCVE: MITRE <- CAPEC -> CWE -> CVE (CVE from 2000)
