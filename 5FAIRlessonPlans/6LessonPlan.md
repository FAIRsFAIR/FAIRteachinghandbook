## Lesson plan 6: Metadata

**FAIR elements**:

**Findable**

The first step in (re)using data is to find them. Metadata and data should be easy to find for both humans and computers. Machine-readable metadata are essential for automatic discovery of datasets and services, so this is an essential component of the [FAIRification process](https://www.go-fair.org/fair-principles/fairification-process/).

[**F1.** (Meta)data are assigned a globally unique and persistent identifier](https://www.go-fair.org/fair-principles/fair-data-principles-explained/f1-meta-data-assigned-globally-unique-persistent-identifiers/)

[**F2.** Data are described with rich metadata (defined by R1 below)](https://www.go-fair.org/fair-principles/fair-data-principles-explained/f2-data-described-rich-metadata/)

[**F3.** Metadata clearly and explicitly include the identifier of the data they describe](https://www.go-fair.org/fair-principles/f3-metadata-clearly-explicitly-include-identifier-data-describe/)

[**F4.** (Meta)data are registered or indexed in a searchable resource](https://www.go-fair.org/fair-principles/f4-metadata-registered-indexed-searchable-resource/)

**Accessible**

Once the user finds the required data, she/he/they need to know how they can be accessed, possibly including authentication and authorisation.

[**A1.** (Meta)data are retrievable by their identifier using a standardised communications protocol](https://www.go-fair.org/fair-principles/542-2/)

[**A1.1.** The protocol is open, free, and universally implementable](https://www.go-fair.org/fair-principles/a1-1-protocol-open-free-universally-implementable/)

[**A1.2.** The protocol allows for an authentication and authorisation procedure, where necessary](https://www.go-fair.org/fair-principles/a1-2-protocol-allows-authentication-authorisation-required/)

[**A2.** Metadata are accessible, even when the data are no longer available](https://www.go-fair.org/fair-principles/a2-metadata-accessible-even-data-no-longer-available/)

**Interoperable**

The data usually need to be integrated with other data. In addition, the data need to interoperate with applications or workflows for analysis, storage, and processing.

[**I1.** (Meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation.](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/)

[**I2.** (Meta)data use vocabularies that follow FAIR principles](https://www.go-fair.org/fair-principles/i2-metadata-use-vocabularies-follow-fair-principles/)

[**I3.** (Meta)data include qualified references to other (meta)data](https://www.go-fair.org/fair-principles/i3-metadata-include-qualified-references-metadata/)

**Reusable**

The ultimate goal of FAIR is to optimise the reuse of data. To achieve this, metadata and data should be well-described so that they can be replicated and/or combined in different settings.

[**R1**](https://www.go-fair.org/fair-principles/r1-metadata-richly-described-plurality-accurate-relevant-attributes/)[. (Meta)data are richly described with a plurality of accurate and relevant attributes](https://www.go-fair.org/fair-principles/r1-metadata-richly-described-plurality-accurate-relevant-attributes/)

[**R1.1**](https://www.go-fair.org/fair-principles/r1-1-metadata-released-clear-accessible-data-usage-license/)[. (Meta)data are released with a clear and accessible data usage license](https://www.go-fair.org/fair-principles/r1-1-metadata-released-clear-accessible-data-usage-license/)

[**R1.2**](https://www.go-fair.org/fair-principles/r1-2-metadata-associated-detailed-provenance/)[. (Meta)data are associated with detailed provenance](https://www.go-fair.org/fair-principles/r1-2-metadata-associated-detailed-provenance/)

[**R1.3**](https://www.go-fair.org/fair-principles/r1-3-metadata-meet-domain-relevant-community-standards/)[. (Meta)data meet domain-relevant community standards](https://www.go-fair.org/fair-principles/r1-3-metadata-meet-domain-relevant-community-standards/)

**Primary audience(s)**: Bachelor&#39;s, master&#39;s, PhD degree students

**Learning outcomes:**

- Can describe types of metadata
- Can recognise metadata formats
- Can identify metadata standards
- Can use metadata standards to describe resources
- Can explain what metadata registries are
- Can search and find data and metadata standards in registries
- Can articulate metadata of different types to describe a resource
- Can write metadata in a relevant format
- Can appraise the usefulness of metadata standards to describe a resource

**Summary of tasks/actions:**

1. Metadata are &#39;data about data&#39;
   1. Present and describe the different types of metadata (can present the whole list, or pick specific elements relevant to your audience).
      1. Metadata are:
         1. standardised
         2. structured
         3. machine- and human-readable
         4. a subset of documentation
   2. Documentation (descriptive and/or technical info)
   3. Controlled vocabularies and ontologies
   4. Persistent identifiers (PIDs)
   5. Licences
2. Learn syntax of example metadata standards:
   1. Dublin Core is general and applicable to all datasets on a project level; on a data level there are discipline-specific standards to branch into such as:
       1. Data Documentation Initiative (DDI) – social science
       2. Ecological Metadata Language (EML) – ecology
       3. Flexible Image Transport System (FITS) – astronomy
   2. Minimum information standards
3. Use metadata catalogues/registries and search for suitable standards

Metadata form the core of machine- and human-readable descriptions of data, be they technical information or annotations, and cover all aspects of the FAIR principles. Metadata is an umbrella term that includes file formats, ontologies and licences, and documentation in general. For each of the principles, metadata can be used at different granularities and domain specificity, with more general metadata not providing as much usefulness and value to the underlying data than domain-specific metadata.

**References**:

- Metadata for Machines workshops
  - General information: [https://www.go-fair.org/how-to-go-fair/metadata-for-machines/](https://www.go-fair.org/how-to-go-fair/metadata-for-machines/)
    - Example: Metadata for Machines workshops, including material. These were funded by the Dutch research foundation ZonMw in support of their COVID-19 research programme: [https://osf.io/bhzf8/](https://osf.io/bhzf8/)
  - [Handbook of Metadata, Semantics and Ontologies](https://books.google.es/books?hl=en&amp;lr=&amp;id=mgS3CgAAQBAJ&amp;oi=fnd&amp;pg=PR5&amp;dq=metadata+typology+&amp;ots=kPQwq65xF3&amp;sig=nW4SNn4sw8Y0MVxT1mA0dXYHGbU&amp;redir_esc=y#v=onepage&amp;q=metadata%20typology&amp;f=false)
- [FAIR Cookbook](https://w3id.org/faircookbook), recipes for hands-on FAIRifications in the Life Sciences.
- [FAIRsharing](https://fairsharing.org/) resource to discover (meta)data standards (and which repositories implement them)

**Take-home tasks**:

- Create the metadata for a dataset
  - Search for standards in catalogues like:
    - [https://rdamsc.bath.ac.uk/](https://rdamsc.bath.ac.uk/)
    - [http://rd-alliance.github.io/metadata-directory/](http://rd-alliance.github.io/metadata-directory/)
    - [FAIRsharing data and metadata standards](https://fairsharing.org/standards/)
    - [https://lov.linkeddata.es/dataset/lov/](https://lov.linkeddata.es/dataset/lov/)
  - How to create a metadata profile or template
    - [FAIRplus example](https://fairplus.github.io/the-fair-cookbook/content/recipes/interoperability/creating-minimal-metadata-profiles.html)
- Encode the data in a dataset using controlled vocabularies/ontologies
  - [FAIRsharing terminology artifacts](https://fairsharing.org/standards/)
  - Jacob et al. [_Making experimental data tables in the life sciences more FAIR: a pragmatic approach_](https://doi.org/10.1093/gigascience/giaa144)GigaScience, Volume 9, Issue 12 2020

**Exercises:**

- [LEGO® Metadata for Reproducibility game pack - Enlighten: Publications](http://dx.doi.org/10.36399/gla.pubs.196477)

---
