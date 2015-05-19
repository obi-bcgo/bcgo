BCGO_basis.owl imports following OWL files generated from Ontodog or OntoFox:

http://purl.obolibrary.org/obo/OBI_subset.owl		OBI_subset.owl (OBI_output.owl removed terms defined in external resources except IAO, replace PATO_0001237 by PATO_0002182 ('molecular entity') since subClass OBI term is 'DNA residue methylation'. Term PATO_0001237 and PATO_0001238 were merged to term PATO_0001241 and the URIs cannot be found in PATO anymore. If there are other subClasses, may need to simple the replacement by using PATO_0001241.  

(Domain of Terms need to be moved
BFO,CARO,CHEBI,CL,CLO,GO,NCBITaxon,OGMS,PATO,PR,REO,SO,UBERON,UO,RO)


Few terms are not in released version of OBI uploaded into the Ontobee server, these terms imported manually.

http://purl.obolibrary.org/obo/import_ChEBI.owl		ChEBI_output_option2.owl
http://purl.obolibrary.org/obo/import_CL.owl		CL_subset.owl (CL_output_option3.owl removed classes defined in external resources and remove or replace GO_0005623 'cell' by CL_0000000 'cell' which was defined as equivalent class in CL found on Dec 11, 2013)
http://purl.obolibrary.org/obo/import_CLO.owl		CLO_output_option2.owl
http://purl.obolibrary.org/obo/import_GO.owl		GO_output_option2.owl
http://purl.obolibrary.org/obo/import_NCBITaxon.owl	NCBITaxon_output_option2.owl
http://purl.obolibrary.org/obo/import_PATO.owl		PATO_output_option3.owl
http://purl.obolibrary.org/obo/import_PR.owl		PR_output_option2.owl
http://purl.obolibrary.org/obo/import_SO.owl		SO_output.owl (before v0.2 release, SO_input_option1 and SO_output_option1.owl was used)
http://purl.obolibrary.org/obo/import_UBERON.owl	start to use UBERON_output_option2.owl since using option 3 bring in many classes and axioms which might not be useful for BCGO and add unnecessary complexity
http://purl.obolibrary.org/obo/import_UO.owl		UO_output_option2.owl and replace UO_0000000 unit by IAO_0000003 measurement unit label, then delete UO_0000000
http://purl.obolibrary.org/obo/import_OBO.owl		OBO_output_option1.owl
http://purl.obolibrary.org/obo/import_EFO.owl		EFO_output.owl and replace EFO_0000408 disease by OGMS_0000031 disease, then delete EFO_0000408. 


Version of ontologies since May 19, 2015
-------------------------------------
OBI		2015-04-13
ChEBI		version 121
CL		2015-01-29
CLO		2015-04-25	
GO		2015-04-18
NCBITaxon	2013-01-24
PATO		2013-10-10
PR		44.0. (date:   05:01:2015 15:08)
SO		2015-02-19
UBERON	2015-03-15
UO		2014-04-09
EFO		version 2.58 (16th March 2015) 

in OBO file
===========
BTO		2013-12-04
ENVO	2015-02-02
ERO		2013-08-02
FMA		2013-08-27
OBCS	2015-04-17

Version of ontologies since May 04, 2014
-------------------------------------
OBI		2014-08-18
ChEBI		version 108
CL		2013-10-15
CLO		2013-11-06	
GO		2014-11-22
NCBITaxon	2013-01-24
PATO		2013-10-10
PR		42.0. (date:  08:07:2014 20:43)
SO		May 11 15:18:44 PDT 2004. version: $Revision: 1.45 (14:04:2011 13:58) 
UBERON		n/a
UO		2013-06-27
EFO		version 2.43 (15th December 2013 ) 
OBO		

Version of ontologies since Dec 11, 2013
-------------------------------------
OBI		2013-10-25
ChEBI		version 108
CL		2013-10-15
CLO		2013-11-06	
GO		2013-12-11
NCBITaxon	2013-01-24
PATO		2013-10-10
PR		38.0. (date: 14:10:2013 12:13)
SO		May 11 15:18:44 PDT 2004. version: $Revision: 1.45 (14:04:2011 13:58) 
UBERON		n/a
UO		2013-06-27
EFO		version 2.36 (15th May 2013) 
OBO		