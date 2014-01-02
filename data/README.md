# pK<sub>a</sub> Cooperative Data

These are datasets from the Cooperative, including both experimental data and computational predictions.

## Contents

### ISA-TAB-format data
[ISA-TAB data](isa-tab) - Cooperative data provided in [ISA-TAB](http://isa-tools.org/) format.

### Redox potentials

Experimental redox potential data was collected from the literature by the Gunner group as [supplementary information](Zhong2009-supporting.pdf) for their publication:  Zheng Z and Gunner MR. Analysis of the electrochemistry of hemes with E<sub>m</sub>s spanning 800 mV. Proteins, 75, 719-734, 2009. DOI:[10.1002/prot.22282](http://dx.doi.org/10.1002/prot.22282)

### Experimental pKa data on various proteins

Experimental pKa data was collected by the Gunner group as [supplementary information](Song2009-supporting.pdf) of their publication:  Song, Y., Mao, J., and Gunner, M. R. (2009) MCCE2: Improving Protein pKa Calculations with Extensive Side Chain Rotamer Sampling J. Comp. Chem. 30, 2231-2247. DOI:[10.1002/jcc.21222](http://dx.doi.org/10.1002/jcc.21222)

The pKa values summarized in pKa data collected from the literature spreadsheet were collected by the Marilyn Gunner lab from various literature sources. The pKas are listed in the [attached spreadsheet (Excel format)](S3-benchmark-protein-list-1101.xls) and the associated proteins and references are discussed in detail in the following table.

| Protein | Exp pKa ref | PDB | Method | # of Models | Ligands kept | Ligands deleted |
| ------- | ----------- | --- | ------ | ----------- | ------------ | --------------- | 
| Ribonuclease a-sarcin precursor | [1, 2] | 1DE3 | NMR | 20 | | |
| Apo E2 | [3] | 1LE2 | X-ray | 1 | | |
| Apo E3 | [4] | 1NFN | X-ray | 1 | | |
| Apo E4 | [3] | 1GS9 | X-ray | 1 | | |
| B1 Domain of protein G | [5] | 1GB1 | NMR | 60 | | |
| | | 1PGA | X-ray | 1 | | |
| | | 1PGB | X-ray | 1 | | |
| B2 Domain of protein G | [5] | 2IGH | NMR | 24 | | |
| | | 1IGD | X-ray | 1 | | |
| | | 2IGD | X-ray | 1 | | |
| Barnase | [6-10] | 1A2P | X-ray | 3 | | Surface Zn |
| | | 1B2X | X-ray | 3 | | | Surface Zn |
| | | 1BNR | NMR | 20 | | |
| | | 1FW7 | NMR | 20 | | |
| Pancreatic trypsin inhibitor precursor (BPTI) | [11, 12] | 1BPI | X-ray | 1 | | Surface PO4 |
| | | 1JV8 | NMR | 23 | | |
| | | 4PTI | X-ray | 1 | | |
| Calbindin D9k | [13] | 1KQV | NMR | 30 | | LA(III) not affecting benchmarked residues |
| | | 1KSM | NMR | 1 | | LA(III) |
| | | 1IG5 | X-ray | 1 | | Mg |
| | | 4ICB | X-ray | 1 | | Ca |
| Cardiotoxin A5 | [14] | 1KXI | X-ray | 2 | | |
| CD2d1 | [15] | 1HNG | X-ray | 2 | | |
| Chymotrypsin | [16] | 2TGA | X-ray | | | Ca |
| Chymotrypsin Inhibitor 2 | [17] | 2CI2 | X-ray | 1 | | |
| | | 2SNI | X-ray | 1 | | Ca, only chain I is used |
| | | 3CI2 | NMR | 20 | | |
| Cyclophilin | [18] | 2CPL | X-ray | | | |
| | | 1OCA | NMR | 20 | | |
| Epidermal growth factor | [19] | 1EGF | NMR | 16 | | |
| | | 1EPG | NMR | 1 | | |
| | | 1EPH | NMR | 10 | | |
| | | 1EPI | NMR | 1 | | |
| | | 1EPJ | NMR | 5 | | |
| FKBP | [18] | 1FKS | NMR | | | | |
| fungal beta cryptogein | [20] | 1BEG | NMR | 18 | | |
| | | 1BEO | X-ray | 1 | | |
| | | 1BXM | X-ray | 1 | | ERG |
| hen egg white lysozyme | [21-23] | 1E8L | NMR | 50 | | |
| | | 1LSE | X-ray | 1 | | |
| | | 4LZT | X-ray | 1 | | NO3 |
| human DNA polymerase lambda lyase domain | [24] | 1NZP | NMR | 8 | | |
| | | 1XSN | X-ray | 1 | | |
| MutT | [25] | 1PPX | NMR | 20 | | 8OG, MO2 |
| | | 1MUT | NMR | 15 | | |
| Myoglobin – horse | [26, 27] | 1DWR | X-ray | 1 | HEM | CMO,SO4 |
| | | 1WLA | X-ray | 1 | HEM | SO4 |
| | | 1YMB | X-ray | | HEM | SO4 |
| Myoglobin – sperm whale | [26, 28] | 1MYF | NMR | 12 | HEM | |
| | | 1A6K | X-ray | 1 | HEM | SO4 |
| | | 1A6M | X-ray | 1 | HEM | Oxy,SO4 |
| phage T4 lysozyme | [29] | 2LZM | X-ray | 1 | | |
| phage T4 lysozyme M102K mutant | [30] | 1L54 | X-ray | 1 | | |
| Phosphonoacetaldehyde hydrolase | [31] | 1FEZ | X-ray | 4 | | Mg, WO4 |
| | | 1RQL | X-ray | 2 | | Mg, VSO |
| RNase A | [32, 33] | 2AAS | NMR | 32 | | |
| | | 7RSA | X-ray | 1 | | TBU |
| | | 9RAT | X-ray | 1 | | |
| | | 3RN3 | X-ray | 1 | | SO4 |
| RNase H1 | [34, 35] | 1RCH | NMR | 8 | | |
| | | 1GOA | X-ray | 1 | | |
| | | 2RN2 | X-ray | 1 | | |
| RNase SA | [36] | 1C54 | NMR | 20 | | |
| | | 1LNI | X-ray | 2 | | GOL,SO4 |
| | | 1RGG | X-ray | 2 | | SO4 |
| RNase T1 | [37-40] | 1IYY | NMR | 24 | | |
| | | 1I0V | X-ray | 1 | | ADP,MG,POB |
| | | 1BVI | X-ray | 4 | | 2GP,Ca |
| | | 1RGA | X-ray | 1 | | 3GP, Ca, G |
| Sea anemone neurotoxin III | [41] | 1ANS | NMR | 28 | | |
| snake erabutoxin b | [42] | 1ERA | NMR | 1 | | |
| | | 1FRA | NMR | 14 | | |
| | | 3EBX | X-ray | 1 | | SO4 |
| Staphylococcal Nuclease | [43] | 1STY | X-ray | | | | |
| Streptomyces Subtilisin Inhibitor | [44] | 2SIC | X-ray | 1 | | Ca |
| | | 3SIC | X-ray | 1 | | Ca |
| | | 5SIC | X-ray | 1 | | Ca |
| | | 3SSI | X-ray | 1 | | |
| Sso7d | [45] | 1JIC | NMR | 1 | | |
| | | 1SSO | NMR | 1 | | | 
| | | 1BBX | NMR | 2 | | |
| | | 1C8C | X-ray | 1 | Not used in this study due to the methylated residue 1 and disordered CTR | |
| Thioredoxin (reduced) | [46] | 1ERT | X-ray | 1 | | |
| | | 3TRX | NMR | 1 | | |
| | | 4TRX | NMR | 33 | | |
| Thioredoxin (oxidized) | [46] | 1ERU | X-ray | 1 | | |
| | | 1AUC | X-ray | 1 | | |
| Turkey ovomucoid inhibitor | [47, 48] | 1OMT | NMR | 50 | | |
| | | 1OMU | NMR | 50 | | | 
| | | 1PPF | X-ray | 1 | BMA,FUC,GAL,GLC,MAN,NAG – complex structure | |
| | | 1TUR | NMR | 12 | | |
| | | 1TUS | NMR | 12 | | |
| Tyrosin phosphatase | [49, 50] | 1BVH | NMR | 15 | | |
| | | 1DG9 | X-ray | 1 | EPE | |
| | | 1Z12 | X-ray | 1 | VO4 | |
| | | 1Z13 | X-ray | 1 | MOO | |
| | | 1PNT | X-ray | 1 | PO4 | |
| Xylanase BA | [51] | 1H4G | X-ray | 2 | FXP,SO4 | |
| | | 1H4H | X-ray | 4 | XYP,XYS, residue 1 changed from Glu to Gln | |
| | | 1QH6 | X-ray | 2 | FXP | | 
| | | 1QH7 | X-ray | 2 | XYP | |
| Xylanase BC | [52] | 1BVV | X-ray | 1 | DFX,XYP | |
| | | 1C5H | X-ray | 1 | | | 
| | | 1XNB | X-ray | 1 | SO4 | |

References:

1. Perez-Canadillas, J.M., et al., Biochemistry, 1998. 37(45): p. 15865-76.
2. Garcia-Mayoral, M.F., et al., Biochemistry, 2003. 42(45): p. 13122-33.
3. Lund-Katz, S., et al., J Lipid Res, 2001. 42(6): p. 894-901.
4. Lund-Katz, S., et al., J Biol Chem, 2000. 275(44): p. 34459-64.
5. Khare, D., et al., Biochemistry, 1997. 36(12): p. 3580-9.
6. Oliveberg, M., V.L. Arcus, and A.R. Fersht, Biochemistry, 1995. 34(29): p. 9424-33.
7. Loewenthal, R., J. Sancho, and A.R. Fersht, J Mol Biol, 1992. 224(3): p. 759-70.
8. Loewenthal, R., et al., J. Mol. Biol., 1993. 232: p. 574-583.
9. Mossakowska, D.E., K. Nyberg, and A.R. Fersht, Biochemistry, 1989. 28(9): p. 3843-50.
10. Sali, D., M. Bycroft, and A.R. Fersht, Nature, 1988. 335(6192): p. 740-3.
11. March, K.L., et al., Biochemistry, 1982. 21(21): p. 5241-5251.
12. Richarz, R. and K. Wuthrich, Biochemistry, 1978. 17: p. 2263-2269.
13. Kesvatera, T., et al., J Mol Biol, 1996. 259(4): p. 828-39.
14. Chiang, C.M., et al., Biochemistry, 1996. 35: p. 9177-9186.
15. Chen, H.A., et al., Biochemistry, 2000. 39(23): p. 6814-24.
16. Markley, J.L. and I.B. Ibanez, Biochemistry, 1978. 17(22): p. 4627-40.
17. Tan, Y., et al., J. Mol. Biol., 1995. 254: p. 980-92.
18. Yu, L. and S.W. Fesik, Biochim Biophys Acta, 1994. 1209(1): p. 24-32.
19. Kohda, D., T. Sawada, and F. Inagaki, Biochemistry, 1991. 30: p. 4896-4900.
20. Gooley, P.R., et al., J Biomol NMR, 1998. 12(4): p. 523-34.
21. Bartik, K., C. Redfield, and C.M. Dobson, Biophys J, 1994. 66(4): p. 1180-4.
22. Kuramitsu, S. and K. Hamaguchi, J Biochem (Tokyo), 1980. 87(4): p. 1215-9.
23. Takahashi, T., H. Nakamura, and A. Wada, Biopolymers, 1992. 32: p. 897-909.
24. Gao, G., et al., Biochemistry, 2006. 45(6): p. 1785-94.
25. Harris, T.K., et al., Biochemistry, 2000. 39(7): p. 1655-74.
26. Kao, Y.H., et al., Biophys J, 2000. 79(3): p. 1637-54.
27. Papa, S., et al., Ann N Y Acad Sci, 1992. 671: p. 345-358.
28. Bashford, D., et al., Biochemistry, 1993: p. 8045-8056.
29. Anderson, D.E., W.J. Becktel, and F.W. Dahlquist, Biochemistry, 1990. 29(9): p. 2403-8.
30. Dao-pin, S., et al., Biochemistry, 1991. 30(49): p. 11521-9.
31. Zhang, G., et al., Biochemistry, 2002. 41(45): p. 13370-7.
32. Rico, M., et al. Proceedings of the 2nd International Meeting. 1991. Sant Feliu de Guixols, Girona, Spain.
33. Baker, W.R. and A. Kintanar, Arch Biochem Biophys, 1996. 327(1): p. 189-99.
34. Oda, Y., M. Yoshida, and S. Kanaya, J Biol Chem, 1993. 268(1): p. 88-92.
35. Oda, Y., et al., Biochemistry, 1994. 33(17): p. 5275-84.
36. Laurents, D.V., et al., J Mol Biol, 2003. 325(5): p. 1077-92.
37. Koumanov, A., et al., Eur Biophys J, 2001. 30(3): p. 198-206.
38. Spitzner, N., et al., Eur Biophys J, 2001. 30(3): p. 186-97.
39. Inagaki, F., et al., J Biochem (Tokyo), 1981. 89(4): p. 1185-95.
40. Giletto, A. and C.N. Pace, Biochemistry, 1999. 38(40): p. 13379-84.
41. Norton, R.S., et al., Biochem J, 1993. 293 ( Pt 2): p. 545-51.
42. Inagaki, F., et al., Eur J Biochem, 1978. 89(2): p. 433-42.
43. Lee, K.K., C.A. Fitch, and E.B. Garcia-Moreno, Protein Sci, 2002. 11(5): p. 1004-16.
44. Fujii, S., K. Akasaka, and H. Hatano, J Biochem (Tokyo), 1980. 88(3): p. 789-96.
45. Consonni, R., et al., Biochemistry, 2003. 42(6): p. 1421-9.
46. Forman-Kay, J.D., G.M. Clore, and A.M. Gronenborn, Biochemistry, 1992. 31(13): p. 3442-52.
47. Schaller, W. and A.D. Robertson, Biochemistry, 1995. 34(14): p. 4714-4723.
48. Swint-Kruse, L. and A.D. Robertson, Biochemistry, 1995. 34(14): p. 4724-4732.
49. Zhou, M.M., J.P. Davis, and R.L. Van Etten, Biochemistry, 1993. 32(33): p. 8479-86.
50. Tishmack, P.A., et al., Biochemistry, 1997. 36(39): p. 11984-94.
51. Betz, M., et al., Biochemistry, 2004. 43(19): p. 5820-31.
52. Joshi, M.D., A. Hedberg, and L.P. McIntosh, Protein Sci, 1997. 6(12): p. 2667-70.

### Experimental pKa data for staph nuclease

#### DATA FROM THE GARCIA-MORENO LAB, JOHNS HOPKINS U., August 2009

This [annotated summary (Excel format)](pKaReleaseJul09.xls) only describes ionizable groups in staphylococcal nuclease whose pKa values have been published or which were released for the Telluride Workshop in July 2009. 

REMINDER:  All of the pKa values reported for the internal groups were measured in the &Delta;+PHS form of nuclease (a stable variant that is is more than twice as stable as the wild type).  All the NMR experiments for proteins with internal ionizable groups were also performed with variants of the &Delta;+PHS protein.  In contrast, some crystal structures were obtained with the &Delta;+PHS and some with the PHS forms.  We usually set crystal trays for variants in both PHS and &Delta;+PHS backgrounds and we use whichever crystals we obtain first.  We have several cases where we have structures of the same variant in the PHS and in the &Delta;+PHS backgrounds and the structures are identical.  In fact, the only case where the microenvironment and conformation of the internal side chain is not identical in the PHS and &Delta;+PHS backgrounds is for the variant with Lys-66, described below.

1. Residue: all His. pKa = (see papers). Relevant PDB: 1stn or 1snc or 3bdc or 1ey8. **COMMENTS**: The pKa values of the four histidines have been measured many times.  Best among the early values are those by John Markley’s group.  Note that the structures listed above correspond to different forms of nuclease.  1stn is the structure of the free wild type, 1snc is the structure of the wild type protein with Ca2+ and an inhibitor known as pdTp.  1ey8 corresponds to the structure of a hyperstable form known as PHS, and 3bdc corresponds to another hyperstable form, known as &Delta;+PHS.  The pKa values of histidines residues measured more recently in our lab can be found in the following papers.  Pay particular attention to the papers by Lee et al (2002, Biochemistry 41: 5656-5667; 2002 Protein Science 11: 1004-1016), which measured the distance dependence and salt sensitivity of pairwise Coulomb interactions with NMR spectroscopy, and the paper by Baran et al (2008, J. Mol. Biol. 379: 1045-1062), which measured interactions in a complex cluster that includes His-121 and His-124.
2. Residue: All Asp and Glu pKa = (see papers). Relevant PDB: 3bdc.  **COMMENTS**: The pKa values of all Asp and Glu residues can be found in the paper by Castaneda et al that has been published in Proteins: Structure, Function and Bioinformatics very recently.  These pKa values were measured with NMR spectroscopy with the &Delta;+PHS form of nuclease because this form of SNase is acid insensitive and stays folded in the range of pH where the majority of the Asp and Glu residues titrate.  Values were measured under conditions of both high and low ionic strength.  Note that the pKa of Asp-21 is unusually high and very difficult to reproduce with any computational method. We have recently completed a study of the interactions and determinants of pKa values of Asp and Glu in the complex cluster in the active site, consisting of residues 19, 21, 40 and 43 (i.e. the active site).  This paper will be sent out for review within the next 3 months.
3. Residue:  Lys-38. pKa ≥ 10.4. Relevant PDB: 2rks. **COMMENTS**: The crystal structure of this protein was obtained in the PHS background under cryogenic conditions.  The properties of Asp, Lys and Glu at position 38 have been described in papers by Harms et al (2008 Protein Science 17: 833-845; 2009 J. Mol. Biol., 389: 34-47).  In pH titrations monitored by far-UV CD and Trp fluorescence there was no obvious evidence of conformational changes coupled to changes in pH.  Similarly, NMR experiments showed no evidence of relaxation.  This is a case where the structure in solution is probably slightly different than the structure in the crystal.  In less than 1 ns of MD simulation this protein relaxes into a state in which Lys-38 has contact with water.  Note that Lys-38 makes an ion pair with Glu-122; the pKa of Lys-38 is insensitive to the presence of this carboxylic group.  You should be able to reproduce this.
4. Residue:  Glu-38.  pKa =  6.8.  Relevant PDB:  3d6c.  **COMMENTS**: The crystal structure of this protein was obtained in the PHS background under cryogenic conditions. The properties of Asp, Lys and Glu at position 38 have been described in papers by Harms et al (2008 Protein Science 17: 833-845; 2009 J. Mol. Biol., 389: 34-47). In pH titrations monitored by far-UV CD and Trp fluorescence there was no obvious evidence of conformational change coupled to the ionization of Glu-38.  Similarly, NMR experiments showed no evidence of relaxation.   We have measured interactions between some of the ionizable groups at position 38 and surface ionizable groups. This is described in the papers.
5. Residue:  Lys-66.  pKa =  5.6.  Relevant PDB:  2snm or 3hzx. **COMMENTS**: The crystal structure of this protein was obtained in wild type background at room temperature (2snm) and in the &Delta;+PHS background under cryogenic conditions (3hzx).  We also have a structure in the PHS background, which is more like 2snm than 3hzx.   pH titrations monitored by far-UV CD and Trp fluorescence show evidence of a local conformational change coupled to the ionization of Lys-66.  This was confirmed with NMR experiments showing that in the range of pH where Lys-66 is ionized, the majority of the protein is intact and native-like, but the region from 62 to 70 (approx) has entered into the intermediate exchange regime, consistent with a local conformational reorganization (i.e. local unfolding) or local increase in fluctuations.
6. Residue:  Glu-66. pKa =  8.5. Relevant PDB:  1u9r. **COMMENTS**: The crystal structure of this protein was obtained in the PHS background under cryogenic conditions.  The behavior of this protein in the far-UV CD and Trp fluorescence and in NMR spectroscopy experiments is comparable to that of the variant with Lys-66.
7. Residue:  Asp-66.  pKa =  8.7.  Relevant PDB:  2oxp. **COMMENTS**: The crystal structure of this protein was obtained in the PHS background under cryogenic conditions.  The behavior of this protein in the far-UV CD and Trp fluorescence and in NMR spectroscopy experiments is comparable to that of the variant with Lys-66.
8. Residue:  Lys-92.  pKa =  5.3.  Relevant PDB:  1tt2. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.  pH titrations monitored by far-UV CD and Trp fluorescence suggest that the ionization of Lys-92 triggers global unfolding of this protein.  This was confirmed with NMR spectroscopy experiments showing behavior consistent with slow exchange between two forms of the protein, one of them showing the loss of dispersion characteristic of unfolded proteins.
9.  Residue:  Glu-92.  pKa =  9.0.  Relevant PDB:  1tr5 or 1tqo. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic (1tqo) or room temperature (1tr5) conditions.  The effects of pH on the structure of this protein are comparable to those described for the variant with Lys-92.
10. Residue:  Asp-92.  pKa =  8.1.  Relevant PDB:  2oeo. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.  The effects of pH on the structure of this protein are comparable to those described for the variant with Lys-92.
11. Residue:  Lys-25. pKa =  6.3. Relevant PDB:  3erq. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.  This is an interesting case where pH titrations monitored by far-UV CD and Trp fluorescence showed no evidence of any conformational change coupled to the ionization of Lys-25, whereas the NMR spectroscopy experiments suggest that a small part of the protein enters into the intermediate exchange regime when Lys-25 is charged.  This is consistent with increased fluctuations or local conformational reorganization.
12. Residue:  Glu-25. pKa =  7.5. Relevant PDB:  3evq. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions. pH titrations monitored by far-UV CD and Trp fluorescence suggest that the ionization of Glu-25 triggers local conformational reorganization.  This has not been examined further with NMR spectroscopy.
13. Residue:  Lys-36. pKa =  7.2. Relevant PDB:  3eji. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.  Neither the pH titrations monitored by far-UV CD and Trp nor the NMR spectroscopy experiments (e.g. HSQC measured as a function of pH) fluorescence show any clear indication of conformational change coupled to the ionization of this group.
14. Residue:  Lys-62. pKa =  8.1. Relevant PDB:  3dmu. **COMMENTS**: The crystal structure of this protein was obtained in the PHS background under cryogenic conditions.  pH titrations monitored by far-UV CD and Trp fluorescence revealed no obvious conformational change coupled to the ionization of Lys-62.  The NMR spectroscopy experiments suggest that upon ionization of Lys-62 the protein enters into slow exchange with a minor component.  Note that the spectra suggest that the majority of the protein is not affected by the ionization of Lys-62.  This is one protein for which we have measured the pKa values of surface carboxylic groups – we know which Asp and Glu residues are affected by the ionization of Lys-62.  Those data will be sent out for publication in a month or two. The results are very interesting.  These are the types of constraints that you should aim to reproduce correctly in your calculations.
15.  Residue:  Arg-66.  pKa ≥  10.5. Relevant PDB:  3heh. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.   This is a structure that was not deposited until recently and the protein was not included in Table II of the document that was released in January 2009. It is an interesting case that you should pay close attention to.  pH titrations monitored by far-UV CD and Trp fluorescence show no evidence of conformational change; however, the HSQC of this protein show that it is more like a molten globule with little well-defined structure.  In the crystal structure the protein is domain-swapped through the N terminal beta strand.  No evidence of swapping was found by analytical ultracentrifugation or static light scattering.  More recently, using SAXS, we have detected an increase in Rg relative to the &Delta;+PHS background protein.  Note that the stability of the protein is marginal, consistent with what was observed with NMR.
16. Residue:  Lys-72. pKa =  8.6. Relevant PDB:  2rbm. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.  Neither the pH titrations monitored by far-UV CD and Trp nor the NMR spectroscopy experiments (e.g. HSQC measured as a function of pH) fluorescence show any clear indication of conformational change coupled to the ionization of this group.
17. Residue:  Glu-72. pKa =  7.3. Relevant PDB:  3ero. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.   In pH titrations monitored by far-UV CD and Trp fluorescence there was no evidence of conformational change coupled to the ionization of this group.  This has not been corroborated with NMR spectroscopy.
18. Residue:  Arg-72. pKa ≥  10.5. Relevant PDB:  3d8g. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions. In this as in the other four variants with internal Arg reported in this list, we cannot detect a shift in pKa at pH 10.5, which is the highest pH we can study. In pH titrations monitored by far-UV CD and Trp fluorescence there was no evidence of conformational change coupled to changes in pH.  This has not been corroborated with NMR spectroscopy.
19. Residue:  Arg-90. pKa ≥  10.5. Relevant PDB:  3dhq. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.  In this as in the other four variants with internal Arg reported in this list, we cannot detect a shift in pKa at pH 10.5, which is the highest pH we can study. In pH titrations monitored by far-UV CD and Trp fluorescence there was no evidence of conformational change coupled changes in pH.  This has not been corroborated with NMR spectroscopy.
20.  Residue:  Glu-91. pKa =  7.1. Relevant PDB:  3d4d. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.  In pH titrations monitored by far-UV CD and Trp fluorescence there was no evidence of conformational change coupled to the ionization of this group.  This has not been corroborated with NMR spectroscopy.
21. Residue:  Lys-103. pKa =  8.2. Relevant PDB:  3e5s. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.  Neither the pH titrations monitored by far-UV CD and Trp nor the NMR spectroscopy experiments (e.g. HSQC measured as a function of pH) fluorescence show any clear indication of conformational change coupled to the ionization of this group.
22.  Residue:  Lys-104    pKa =  7.7. Relevant PDB:  3clf. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions.   pH titrations monitored by far-UV CD and Trp fluorescence suggest that the ionization of Lys-104 triggers a local conformational change, but there is no clear evidence of this in HSQC spectra measured as a function of pH.  This does not necessarily mean that the change is not taking place.  We’ll have to look harder.
23.  Residue:  Arg-109    pKa ≥  10.5. Relevant PDB:  3d4w. **COMMENTS**: The crystal structure of this protein was obtained in the &Delta;+PHS background under cryogenic conditions. In this as in the other four variants with internal Arg reported in this list, we cannot detect a shift in pKa at pH 10.5, which is the highest pH we can study. In pH titrations monitored by far-UV CD and Trp fluorescence there was no evidence of conformational change coupled to changes in pH.  This has not been corroborated with NMR spectroscopy.
24. Residue:  Lys-125     pKa =  6.2. Relevant PDB:  3cle. **COMMENTS**: The crystal structure of this protein was obtained in the PHS background under cryogenic conditions.  According to pH titrations monitored by far-UV CD and Trp fluorescence the ionization of Lys-125 is coupled to a local conformational change.  HSQC measured with NMR spectroscopy as a function of pH corroborate this; they indicate that a small part enters into intermediate exchange regime, consistent with local unfolding or conformational change or increase in fluctuations.