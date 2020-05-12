# Coronapaper-March-2020
This is a repository of the Copasi files corresponding to the models in Westerhoff and Kolodkin (2020) NPJSBA

Figure reconstruction
This file describes how the main figures of the paper can be obtained by using the uploaded computer programs.
Contents
Figure 1.	1
Figure 2	1
Figure 3	2
Figure 4	2
Figure 5	3
Figure 6.  Strong then soft better than soft then strong	3


Figure 1.
The construction of the diagram for the model of the COVID-9 epidemics used the open access CellDesigner software (v4.4; Systems Biology Institute, http://celldesigner.org/index.html).  The picture was stored as PNG file (Figure 1 PNG), PDF (Figure 1 pdf) and as HTML (Figure 1 HTML) file.

Figure 2
Figure 2 was obtained by using the Copasi files: 
Wff1Corona_Lux_2020-03-20_1340 intermittentGwork full lockdown effect of socialdistancing Fig 3 also Fig 2WORK2A copied to ‘Figure 2 sdf=1’
Wff1Corona_Lux_2020-03-20_1340 intermittentGwork full lockdown effect of socialdistancing Fig 3 also Fig 2WORK2B copied to ‘Figure 2 sdf=2.2’
Wff1Corona_Lux_2020-03-20_1340 intermittentGwork full lockdown effect of socialdistancing Fig 3 also Fig 2WORK2C copied to ‘Figure 2 sdf=10’
which are all the same except for the setting of the parameter ‘Government_induced_isolation_factor’ where the pre-multiplier was set to 1, 2.2 or 10, for the ‘without government action’, ‘factor 2.2 social distancing’ and ‘complete lockdown’, respectively (the 141/141 is a historical artifact in the model):
 
The Copasifiles all have time steps of 1 day in order to keep the excel file manageable.  The files have a complex title because they are capable of many other features that are not utilized here, but will be utilized in other figures of the paper. 
Each file calculates for one parameter setting, i.e. either without government action ('WORK2A'), with factor 2.2 social distancing ('WORK2B') or with complete lockdown ('WORK2C').  The text files are output from the computation of the figure ‘% dead, #infected_tested and #symptoms_not_tested versus time (days)’, but then only retaining ‘% corona dead’ (Fig. 2B) and ‘infected tested’ (Fig. 2A): Confusingly the final figures entitled 2A and 2B each show one aspect for the three cases (e.g., this ‘2A’ does not correspond to the ‘New2A’).  This is what the excelfile achieves.  This excel file has been copied to ‘Figure 2 Excel’.

Figure 3
The data were obtained by running the file Figure 3 Copasi (copy of ‘Wff1Corona_Lux_2020-03-20_1340 intermittentGwork full lockdown effect of socialdistancing Fig 3 also Fig 2WORK2A’ )   for various social distancing factors, again by using the pre-multiplier (1. in the expression below) of the expression for the ‘Government_induced_isolation_factor’:
 
The resulting data were captured manually in the excelfile  ‘Fig 3. Government measure versus resultsNEW’, copied to ‘Figure 3 Excel’.

Figure 4
Filename: Wff1Corona_Lux_2020-03-20_1340 intermittentGwork full lockdown effect of socialdistancing Fig 3 also Fig 2WORK2A.cps,   renamed to Figure 4 Copasi
Settings:
Time fraction  lockdown = 0.7  for Fig 4B and 0.55 for Figure 4A
Lockdown duration = 7
Government_induced_isolation_factor = premultiplier 10:  
Excel file: Fig4ANewWff1Corona_Lux_2020-03-20_1340 intermittentGwork full lockdown effect of socialdistancing Fig 4 intermittentWORK and Fig4BNewWff1Corona_Lux_2020-03-20_1340 intermittentGwork full lockdown effect of socialdistancing Fig 4 intermittentWORK   renamed to Figure 4A Excel and Figure 4B Excel.

Figure 5
Figure 5 files. Full lockdown setting except that the social distancing factor is modulated as a function of symptoms-tested
Excel file: Fig NEW 5 inf tested, govern,  % dead, sympt testedtext copied to ‘Figure 5 Excel’
Copasi file: Wff1Corona_Lux_2020-03-20_1340 intermittentGwork full lockdown effect of socialdistancing Fig 5 adaptive  copied to ‘Figure 5 Copasi’.

Figure 6.  Strong then soft better than soft then strong
Copasi filename: Previously called ‘Fig S4 attempts at strong then soft and vice versa.’ Now copied to ‘Figure 6 Copasi.cps’. Global quantities ‘first social distancing factor factor’ and ‘second social distancing factor factor’  were set to 10 and 2, or 2 and 10 respectively and then a time integration was run, data saved into excel files and combined.  Excel file: Figure 6 Excel.









