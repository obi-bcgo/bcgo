BCGO_basis.owl imports following OWL files generated from Ontodog or OntoFox:

http://purl.obolibrary.org/obo/OBI_subset.owl		OBI_subset.owl (OBI_output.owl removed terms defined in external resources except IAO, (replace OGMS_0000022 by OGMS_0000063 since wrong ID was used in OBI, issue was fixed, not need to make this change anymore), need to replace PATO_0001237 and PATO_0001238 by PATO_0002182 since these two terms were merged in PATO and the term is not in PATO anymore. No need to worry about it now since the terms were not used in defining any OBI or IAO terms)
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
http://purl.obolibrary.org/obo/import_EFO.owl		EFO_output.owl and replace EFO_0000408 disease by OBI_1110055 disease, then delete EFO_0000408. 




Version of ontologies on Dec 11, 2013
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