# New York State Prisons Disciplinary Records

This repository contains New York State [Department of Corrections and Community Supervision](https://doccs.ny.gov/) (DOCCS) disciplinary records, initially obtained through a lawsuit by the [New York Civil Liberties Union](https://www.nyclu.org/) (NYCLU), and subsequently provided by the NYCLU to The New York Times. It also contains structured data extracted from those records, as well as official documentation from DOCCS. The records were used for [this November 24, 2025 article in The Times](https://www.nytimes.com/2025/11/24/nyregion/ny-prison-guards-abuse-brutality.html).

## Records

This repository contains four main files:

- [original/DOCCS_Records_Redacted.pdf](original/DOCCS_Records_Redacted.pdf): A 60-page PDF listing DOCCS disciplinary cases and outcomes from January 2000 to mid-October 2020, as provided by DOCCS to NYCLU.
- [extracted-data/extracted-data.csv](extracted-data/extracted-data.csv): A structured data file, formatted as a CSV, containing all data that The New York Times was able to extract from the PDF above, provided for convenience. __The authoritative, primary source remains the PDF, and the PDF should be consulted to confirm anything observed in the CSV.__ Additional notes: 
    - This file represents a good-faith effort by The Times to accurately convert the records using programmatic methods, but it may contain inaccuracies; please contact `bianca.pallaro@nytimes.com` to report any such discrepancies. By using these records you agree not to hold The New York Times liable for any inaccuracies that may exist.
    - Some of the text in the PDF has been redacted; these redactions are not represented in the CSV file.
- [dictionaries/misconduct_databasecodes.pdf](dictionaries/misconduct_databasecodes.pdf): A PDF provided by DOCCS to NYCLU describing the fields/columns in the records.
- [dictionaries/misconduct-abbreviations.pdf](dictionaries/misconduct-abbreviations.pdf): A PDF provided by DOCCS to NYCLU explaining many of the abbreviations used in the records to describe misconduct types, dispositions, and penalties.


## License and Attribution

The New York Times is publishing these records for the benefit of the public.

The records obtained from DOCCS are public records and are released into the public domain. The [extracted-data/extracted-data.csv](extracted-data/extracted-data.csv) file, meanwhile, is released under the [Creative Commons Attribution-NonCommercial 4.0 International license](https://creativecommons.org/licenses/by-nc/4.0/legalcode) if they have questions about the scope of the license.
