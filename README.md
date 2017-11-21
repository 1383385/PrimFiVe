# PrimFiVe
Automated multiplexable primer designing and verification pipeline.

**USAGE**

Straightforward usage. Simply select the GenBank file with features and select the feature you wish to have specific sequencing primers against. Or select the FASTA file and PrimFiVe will do the rest.                               

Common Issues:                                                                                                            
Issue 1: Warning: No sequences written to output file "Link/to/your/feature/file.fasta"                                   
Solution: Make sure the GenBank file has that feature listed that you have requested.                                     
For example, if you selected "exon" as the feature and the GenBank file lacks that feature, this error will be triggered.
Issue 2: PRIMER_ERROR=thermodynamic approach chosen, but path to thermodynamic parameters not specified
Solution: Put the "primer3_config" folder that comes with the Primer3 package in the "/opt/" directory.


For any query/ suggestion please feel free to contact:
Aditya Singh
Ph.D. Scholar
Haemat-Onco Unit
Advanced Paediatrics Centre
Postgraudate Institute of Medical Education and Research
Chandigarh, India, 160012
aditya.onco@gmail.com
