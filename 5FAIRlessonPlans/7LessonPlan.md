## Lesson plan 7: Data standardisation and ontologies

**FAIR elements:**

**Findable**

Standardisation of data identifiers makes data easier to find.

[**F1.** (Meta)data are assigned a globally unique and persistent identifier](https://www.go-fair.org/fair-principles/fair-data-principles-explained/f1-meta-data-assigned-globally-unique-persistent-identifiers/)

**Interoperable**

The data usually need to be integrated with other data. In addition, the data need to interoperate with applications or workflows for analysis, storage, and processing.

Interoperability is made easier through standardised representations of knowledge and by using standard variables that allow linking of data files, e.g. using standardised [date and time stamps](https://www.w3.org/TR/NOTE-datetime).

[**I1.** (Meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/)

[**I2.** (Meta)data use vocabularies that follow FAIR principles](https://www.go-fair.org/fair-principles/i2-metadata-use-vocabularies-follow-fair-principles/)

[**I3.** (Meta)data include qualified references to other (meta)data](https://www.go-fair.org/fair-principles/i3-metadata-include-qualified-references-metadata/)

**Reusable**

Domain-relevant community standards make data easier to understand and reuse.

[**R1.3.** (Meta)data meet domain-relevant community standards](https://www.go-fair.org/fair-principles/r1-3-metadata-meet-domain-relevant-community-standards/)

**Primary audience(s):** Bachelor&#39;s, master&#39;s, PhD degree students(without a knowledge management background)

**Learning outcomes:**

- Can explain aspects related to data interoperability and integration (standardisation in data and how data standards are used)
- Can explain aspects of data preparation and cleaning
- Can explain the roles of ontologies and vocabularies
- Can recognise the use of ontologies and vocabularies
- Can recognise the role of data standards in making data FAIR.
- Understands that different communities use different data standards and ontologies to improve the understanding and interoperability of their research data
- Can identify a few domain-relevant ontologies
- Understands usage scenarios of ontologies during data collection, data analysis and when making data available through repositories, APIs, etc.
- Knows how to act when an ontology does not exist or elements are missing in an existing ontology

**Summary of tasks/actions:**

1. Explain with easy and practical examples (from your discipline) how standardisation of data can be applied in research. Standardisation enables interoperability of data, common understanding of data and facilitates (interdisciplinary) reuse of data. Some simple examples are:
   1. Standard coding structures (e.g. use 1=male, 2=female systematically, and not sometimes 1=female, 2=male, or 0=male, 1=female)
   2. Standard units: degrees Celsius vs. degrees Fahrenheit; wind speed measured in m/s vs. knots/s, universal date and time stamps (19)
   3. Standard geospatial representations, e.g. WGD84
   4. Statistical Classification of Economic Activities in the European Community: [NACE](https://ec.europa.eu/eurostat/ramon/nomenclatures/index.cfm?TargetUrl=LST_NOM_DTL&amp;StrNom=NACE_REV2) code
   5. Universal system of (binomial) nomenclature and taxonomy to name and classify biodiversity, now also including DNA barcoding (20)
   6. Standards for dates and times ([ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html)), for countries ([ISO 3166](https://www.iso.org/iso-3166-country-codes.html)), for geographical names ([Getty Thesaurus](http://www.getty.edu/research/tools/vocabularies/tgn/))
2. You could also show an example of how not using standards makes things more difficult, or involves more work to clean and translate data, for example:
   1. Survey data where standardised responses are still captured as &#39;text&#39; rather than numerical codes (dataset with &#39;male&#39;, &#39;female&#39; rather than numeric codes)
   2. Datasets where units of variables are not defined, so it is not possible to say whether the temperature is in Celsius or Fahrenheit
   3. Any other example listed above where no standard was used in the dataset
3. Use examples of data standards in different disciplinary communities (see references)
   1. Help define data procedures, standards and guidelines by discipline. For example, are there guidelines for data processing, are there metadata standards, are there controlled vocabularies, ontologies and taxonomies, are there specialised data repositories used by the scientific community?
4. Describe what ontologies are and their function in the semantic web. Learn the various types of ontologies.

Interoperability is also part of teaching and adheres to the following principles:

- F2. Data are described with rich metadata – using ontologies is part of good metadata practice
- R1. Meta(data) are richly described with a plurality of accurate and relevant attributes – using ontologies is part of good practice for rich and precise descriptions
- R1.3. (Meta)data meet domain-relevant community standards – the same as the previous two bullet points

**References**

Use cases:

- BioSharing registry: [https://biosharing.org/](https://biosharing.org/)
- Specifications of Standards in Systems and Synthetic Biology: [https://doi.org/10.1515/jib-2018-0013](https://doi.org/10.1515/jib-2018-0013)
- Biodiversity standards:
  - Audubon Core: [https://www.tdwg.org/standards/ac/](https://www.tdwg.org/standards/ac/)
  - Darwin Core: [https://www.tdwg.org/standards/dwc/](https://www.tdwg.org/standards/dwc/)
  - Natural Collections Descriptions (NDC): [https://www.tdwg.org/standards/ncd/](https://www.tdwg.org/standards/ncd/)
  - GUID applicability statements: [https://github.com/tdwg/guid-as](https://github.com/tdwg/guid-as)
  - TDWG Access Protocol for information Retrieval (TAPIR): [https://www.tdwg.org/standards/tapir/](https://www.tdwg.org/standards/tapir/)
  - TDWG Standards Documentation Standard (SDS): [https://www.tdwg.org/standards/sds/](https://www.tdwg.org/standards/sds/)
  - Vocabulary Maintenance Standard (VMS): [https://www.tdwg.org/standards/vms/](https://www.tdwg.org/standards/vms/)
  - Global Genome Biodiversity Network (GGBN Data Standard): [https://www.tdwg.org/standards/ggbn/](https://www.tdwg.org/standards/ggbn/)
  - Access to Biological Collection Data (ABDC): [https://www.tdwg.org/standards/abcd/](https://www.tdwg.org/standards/abcd/)
  - Description Language for Taxonomy (DELTA): [https://www.tdwg.org/standards/delta/](https://www.tdwg.org/standards/delta/)
  - Structured Descriptive Data (SDD): [https://www.tdwg.org/standards/sdd/](https://www.tdwg.org/standards/sdd/)
  - Taxonomic Schema (TCS): [https://www.tdwg.org/standards/tcs/](https://www.tdwg.org/standards/tcs/)
- Agriculture data:
  - Dzale Yeumo E, Alaux M, Arnaud E et al. Developing data interoperability using standards: A wheat community use case [version 2; peer review: 2 approved]. F1000Research 2017, 6:1843. Doi: [https://doi.org/10.12688/f1000research.12234.2](https://doi.org/10.12688/f1000research.12234.2)
  - Wheat Data Interoperability Guidelines and Recommendations: [https://www.rd-alliance.org/groups/wheat-data-interoperability-wg.html](https://www.rd-alliance.org/groups/wheat-data-interoperability-wg.html) and [https://www.rd-alliance.org/group/working-and-interest-group-chairs-wheat-data-interoperability-wg/outcomes/wheat-data](https://www.rd-alliance.org/group/working-and-interest-group-chairs-wheat-data-interoperability-wg/outcomes/wheat-data)
  - Agrisemantics Working Group Recommendations: [https://www.rd-alliance.org/groups/agrisemantics-wg.html](https://www.rd-alliance.org/groups/agrisemantics-wg.html)
  - The eROSA Roadmap for a pan-European e-Infrastructure for Open Science in Agricultural and Food Sciences (led by INRA) significantly reflects outputs of several RDA groups, including Data Fabric&#39;s &quot;Recommendations for Implementing a Virtual Layer for Management of the Complete Life Cycle of Scientific Data&quot;.
  - The FAIRsharing Registry and Recommendations: Interlinking Standards, Databases and Data Policies: [https://www.rd-alliance.org/group/fairsharing-registry-connecting-data-policies-standards-databases-wg/outcomes/fairsharing](https://www.rd-alliance.org/group/fairsharing-registry-connecting-data-policies-standards-databases-wg/outcomes/fairsharing)

- Ocean data:
  - Ocean Data Standards and Best Practices: [https://www.oceandatastandards.org/](https://www.oceandatastandards.org/)
  - SeaDataNet Metadata Profile ISO 19115: [https://www.seadatanet.org/content/download/1855/file/CDI-profile-V10.0.1.pd](https://www.seadatanet.org/content/download/1855/file/CDI-profile-V10.0.1.pdf)

- [https://bartoc.org/](https://bartoc.org/)
- [https://asistdl.onlinelibrary.wiley.com/doi/epdf/10.1002/bult.2013.1720390211](https://asistdl.onlinelibrary.wiley.com/doi/epdf/10.1002/bult.2013.1720390211)

**Take-home tasks**

- Analyse the existing standards (general and/or by discipline) required in FAIR principles
- Study/Analyse the standards that apply in a particular discipline
- Standardise a dataset: choose a discipline, create or download a dataset and standardise it according to the scientific community
- Activities related to data standardisation tools:
  - OpenRefine tool (data clean, data transformation, data normalisation, etc.)
  - Data FAIRification tools: [https://fairplus.github.io/the-fair-cookbook/content/recipes/interoperability/rdf-conversion.html](https://fairplus.github.io/the-fair-cookbook/content/recipes/interoperability/rdf-conversion.html)

**(19)** Good example on standardising date time stamp in: Data Tree, module 2, topic 4, Data Handling and Formats: [Practicalities: Presentation: Data Handling and Formats (datatree.org.uk)](https://datatree.org.uk/mod/scorm/player.php?a=30&currentorg=00M2_T4_20181014_ORG&scoid=83)

**(20)** [Global Taxonomy Initiative (cbd.int)](https://www.cbd.int/gti/)