Ontology terms from external ontologies were extracted using the OntoDog or OntoFox tools and made some edits when needed before imported these OWL files into the bcgo.owl or bcgo_basis.owl. The details of imported files see below.

- <b>OBI</b>: http://purl.obolibrary.org/obo/bcgo/OBI_subset.owl (filename: OBI_subset.owl)
	<br>This OWL file is generated from OBI_output.owl:
    - Removed terms defined in external resources except IAO. The terms with following prefix need to be moved:
BFO,CARO,CHEBI,CL,CLO,GO,NCBITaxon,OGMS,PATO,PR,REO,SO,UBERON,UO,RO
  	- Replaced PATO_0001237 with PATO_0002182 ('molecular entity') since subClass OBI term is 'DNA residue methylation'. Term PATO_0001237 and PATO_0001238 were merged to term PATO_0001241 and the URIs cannot be found in PATO anymore. If there are other subClasses, may need to simple the replacement by using PATO_0001241.  

- <b>ChEBI</b>: http://purl.obolibrary.org/obo/bcgo/import_ChEBI.owl (filename: ChEBI_output_option2.owl)

- <b>CL</b>: http://purl.obolibrary.org/obo/bcgo/import_CL.owl (filename: CL_subset.owl)
	<br>This OWL file is generated from CL_output_option3.owl
	- Removed classes defined in external resources
    - Removed or replaced GO_0005623 'cell' with CL_0000000 'cell' which was defined as equivalent class in CL found on Dec 11, 2013
	- Replaced BFO_0000053 with RO_0000053 and BFO_0000056 with RO_0000056

- <b>CLO</b>: http://purl.obolibrary.org/obo/bcgo/import_CLO.owl (filename: CLO_output_option2.owl)
  	- Replaced [EFO:disease](http://www.ebi.ac.uk/efo/EFO_0000408) with [OGMS:disease] (http://purl.obolibrary.org/obo/OGMS_0000031), then delete EFO:disease

- <b>GO</b>: http://purl.obolibrary.org/obo/bcgo/import_GO.owl (filename: GO_output_option2.owl)

- <b>NCBITaxon</b>: http://purl.obolibrary.org/obo/bcgo/import_NCBITaxon.owl (filename: NCBITaxon_output_option2.owl)

- <b>PATO</b>: http://purl.obolibrary.org/obo/bcgo/import_PATO.owl (filename: PATO_output_option3.owl)

- <b>PR</b>: http://purl.obolibrary.org/obo/bcgo/import_PR.owl (filename: PR_output_option2.owl)

- <b>SO</b>: http://purl.obolibrary.org/obo/bcgo/import_SO.owl (filename: SO_output.owl)
  <br>Note: before v0.2 release, SO_input_option1 and SO_output_option1.owl was used

- <b>UBERON</b>: http://purl.obolibrary.org/obo/bcgo/import_UBERON.owl (filename: UBERON_output_option2.owl)
  <br>Note: using option 3 bring in many classes and axioms which might not be useful for BCGO and add unnecessary complexity

- <b>UO</b>: http://purl.obolibrary.org/obo/bcgo/import_UO.owl (filename: UO_output_option2.owl) 
  - replaced UO_0000000 unit with IAO_0000003 measurement unit label, then delete UO_0000000

- <b>EFO</b>: http://purl.obolibrary.org/obo/bcgo/import_EFO.owl (filename: EFO_output.owl)
  	- Replaced [EFO:disease](http://www.ebi.ac.uk/efo/EFO_0000408) with [OGMS:disease] (http://purl.obolibrary.org/obo/OGMS_0000031), then delete EFO:disease

- <b>OBO</b>: http://purl.obolibrary.org/obo/bcgo/import_OBO.owl (filename: OBO_output_option1.owl)
  <br>Ontology terms are not in the ontologies listed above.
   
- <b>Manual import</b>: http://purl.obolibrary.org/obo/bcgo/externalByHand.owl (filename: externalByHand.owl)
  <br>Few terms imported manually.

<b>Version of ontologies used by BCGO since May 19, 2015</b>
Ontology | Version
--|--
OBI | 2015-04-13
ChEBI | version 121
CL | 2015-01-29
CLO | 2015-04-25	
ENVO | 2015-02-02
GO | 2015-04-18
NCBITaxon | 2013-01-24
OBCS | 2015-04-17
PATO | 2013-10-10
PR | 44.0. (date:   05:01:2015 15:08)
SO | 2015-02-19
UBERON | 2015-03-15
UO | 2014-04-09
BTO | 2013-12-04
EFO | version 2.58 (16th March 2015) 
ERO | 2013-08-02
FMA | 2013-08-27

<b>Version of ontologies used by BCGO since May 04, 2014</b>
Ontology | Version
--|--
OBI | 2014-08-18
ChEBI | version 108
CL | 2013-10-15
CLO | 2013-11-06	
GO | 2014-11-22
NCBITaxon | 2013-01-24
PATO | 2013-10-10
PR | 42.0. (date:  08:07:2014 20:43)
SO | May 11 15:18:44 PDT 2004. version: $Revision: 1.45 (14:04:2011 13:58) 
UBERON | n/a
UO | 2013-06-27
EFO | version 2.43 (15th December 2013 ) 	

<b>Version of ontologies used by BCGO since Dec 11, 2013</b>
Ontology | Version
--|--
OBI | 2013-10-25
ChEBI | version 108
CL | 2013-10-15
CLO | 2013-11-06	
GO | 2013-12-11
NCBITaxon | 2013-01-24
PATO | 2013-10-10
PR | 38.0. (date: 14:10:2013 12:13)
SO | May 11 15:18:44 PDT 2004. version: $Revision: 1.45 (14:04:2011 13:58) 
UBERON | n/a
UO | 2013-06-27
EFO | version 2.36 (15th May 2013) 

