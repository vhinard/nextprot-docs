This new release of neXtProt incorporates expression and subcellular location experimental information from release 13 of the Human Protein Atlas (HPA). As a consequence, 360 additional protein entries now have expression data based on IHC.

COSMIC v71 has also been integrated as part of this release resulting in the inclusion of 312290 additional variants. In COSMIC, each sample is described using four fields: 'Primary site', 'Site subtype', 'Primary histology' and 'Histology subtype'. We have created a mapping, named the 'Cosmosaurus', between COSMIC and the NCI Thesaurus with the help of the COSMIC biocurators. The Cosmosaurus treats each distinct combination of these four fields as a synonym (SY) for a NCI entry, defined by its NCI Thesaurus term (ID) and accession (AC). The diseases associated with variants from the COSMIC database are now displayed in the medical view. The 'Cosmosaurus' can be downloaded from: [ftp://ftp.nextprot.org/pub/current_release/mapping/cosmosaurus.txt](ftp://ftp.nextprot.org/pub/current_release/mapping/cosmosaurus.txt).

Finally, several changes concerning the evidences supporting annotations have gone into effect in this release. In UniProtKB, individual evidences include a mandatory evidence type, represented by a code from the Evidence Codes Ontology (ECO) - this ECO term is now displayed in neXtProt. The source of the data, usually another database record that is represented by the database name and record identifier, is also displayed. When there is no source for the UniProtKB evidence, the UniProtKB reference number linking to the corresponding entry is provided. An additional change implemented in this release is the display of the quality at the level of individual evidences. ECO terms and the quality of evidences are now also found in the XML export files and the XSD has been changed accordingly.