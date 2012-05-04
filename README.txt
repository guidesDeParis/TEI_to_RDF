README

This repository holds files for converting TEI/XML encoded text documents into RDF/XML through XSL transformations. The RDF triples generated from the transform are subject_predicate_object relations within the TEI document. 

xslt/tei_bare_to_rdf.xsl
________________________

This XSLT file is for transforming files that are marked up with TEI tags conforming to the TEI_Bare schema, the minimum tagset for a TEI encoding (see http://www.tei_c.org/Guidelines/Customization/ for details of different TEI customisations and corresponding schemas).

This XSLT extracts RDF triples from TEI_bare conformant documents. The vocabulary for the predicates used in these RDF triples is largely drawn from the Dublin Core model for expressing metadata information about a document (see http://dublincore.org/ ).

xslt/tei_bare_example.xml and xslt/tei_bare.rng
_________________________     -----------------
Sample TEI-bare files, for testing