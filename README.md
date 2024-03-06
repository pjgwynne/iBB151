# iBB151
Metabolic model of B. burgdorferi B31

iBB151.xml is in SBML format (version 3.1). COBRA doesn't seem to like the excel document so I use the .xml for COBRA analysis. There are two versions: 'archive' is one that was attached to the initial publication, and 'updated' seems to fix a reported error trying to import to the latest version of COBRA.

iBB151.xlsx is in excel format. I use this for RAVEN, but the .xml should also work.

Both of these can be analysed in Matlab using either COBRA or RAVEN. The excel file is much easier to browse.

iBB151_essential.xgmml is a cytoscape network layout for browsing pathways.

cytoscape is found here: https://cytoscape.org/

RAVEN is found here: https://github.com/SysBioChalmers/RAVEN

COBRA is found here: http://opencobra.github.io/

(Note that both RAVEN and COBRA are to be opened in a Matlab environment)

A detailed methods document describing the generation and analysis of iBB151 is found in methods.doc
