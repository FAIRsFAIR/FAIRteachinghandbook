## 6.5 Support infrastructure

Resources and infrastructure are required to enable FAIR data practices within a higher education institution. However, some of the requirements in FAIR can be met through open-source solutions so as to maximise potential reuse of data. Investment in both staffing and platforms is recommended to enable academics to optimise FAIR data.

**Systems for storage, backup and collaboration**

Researchers increasingly depend upon technological platforms and tools throughout the data lifecycle. Data, metadata and other artefacts of the research process, including ontologies, software, documentation and papers, all need to be stored in environments where they are backed up and made available for collaboration with partners while being appropriately protected. A common backup method used for research data is the &#39;3-2-1 rule&#39; which involves three copies of the research data being saved: two locally and one off-site. These technical environments may be locally available in a higher education institution or delivered through other services such as cloud computing, including hosting by third parties using a variety of open source or proprietary technologies. Whatever the selected technical infrastructure, investment is required to enable academics to optimise FAIR data to maximise their potential for reuse.

In addition to backup and restoration services that safeguard researchers against data loss, theft, or failure of computers or storage media, and against accidental deletion or unintentional changes to the data, appropriate access management is vital. Authentication (identification and login) and authorisation (permissions control) mechanisms can facilitate collaboration and data sharing within teams. Access control is also critical to protect sensitive data, e.g. personal information about data subjects, as this has both legal and ethical implications.

Questions about storage, backup and data security are included in many DMP templates issued by funders. Institutions should therefore supply their researchers with information on how their services meet the requirements to help them write their DMPs.

**Repository services**

Research data repositories are key pieces of infrastructure needed in the research data lifecycle to enable FAIR. They provide a persistent identifier, make the descriptive metadata available, and give access to the data (if applicable). Some repositories offer preservation, which is covered in the following section.

Repositories offer supporting services for the deposit of and access to information vital to research data. A repository or archive may focus on research datasets, but also provide services covering metadata, ontologies, software, etc. These repositories can provide technical infrastructure for ongoing storage, resource discovery and access to (meta)data with persistent identifiers assigned to support citations, credit and vital links between &#39;digital objects&#39; that support interoperability.

For researchers, these repositories provide both a source of data for reuse, and a reliable location for the results of their work. The underlying principles of FAIR are central to the role of repositories, but different repositories offer varying services and degrees of compliance with the expectations of FAIR data. It is important to note that data which are FAIR at the point of deposit in a repository may not remain so without active curation and preservation. Repositories can enable FAIR data by continuing to manage the data formats, e.g. through emulation of ongoing migration to long-term formats. They should also manage the supporting technologies and associated metadata and ontologies as they change over time. The FAIRsFAIR project has developed a [capability/maturity](https://doi.org/10.5281/zenodo.5471568) approach that aligns repository capability with the requirements for enabling FAIR data over time. Repositories that support more specialised metadata, e.g. disciplinary or domain-specific, will be able to support more sophisticated resource discovery.

Many institutions run their own institutional repositories, but there are a large number of repositories available elsewhere. Some disciplines or domains have dedicated national or multinational repositories.

From a researcher&#39;s point of view, the choice of repository should depend upon the level of support required by their data types and that offered by the repository. These can range from basic storage to resource discovery and on to managing access and use of sensitive data, supporting the peer review of data associated with publications or services involving digital preservation.

The [OpenAIRE repository guide](https://www.openaire.eu/opendatapilot-repository-guide) advises users to check the availability of a suitable repository in this order:

1. The best choice (if available) is to use an established, dedicated (external) data archive or repository that caters specifically to the research domain to preserve the data according to recognised discipline-specific standards.
2. The second-best choice is to use institutional data repositories.
3. If the above are not viable options, a cost-free data repository should be used.

Dedicated disciplinary repositories are more likely to support community (meta)data standards that will make data more interoperable and more FAIR in general. Institutional repositories may offer integration with local support services, but this may be more generic and therefore less likely to use community standards and rich/specific metadata. Up-to-date lists of available registered data repositories can be found at [re3data](https://www.re3data.org/) and [FAIRsharing](https://fairsharing.org/databases/).

Free-of-charge public repositories are good alternatives for small institutions with limited resources. Three of the more widely known and free to use data repositories are:

- [Zenodo](https://zenodo.org/) – An open access data, software and publication repository for researchers who want to share multidisciplinary research results. It is suitable for all types of research data. It is free to use and has guaranteed funding from the EU for the foreseeable future. Runs on open-source software.
- [Harvard Dataverse](https://dataverse.harvard.edu/) – An open access repository for research data, code and related material. Open to data from all disciplines worldwide. Runs on open-source software.
- [Figshare](https://figshare.com/) – An open access repository that provides DOIs and Creative Commons Licences for all datasets. Runs on proprietary software.

Relying purely on external services does not help when developing institutional capacities in this dynamic field, for example in regard to digital preservation. As a result, higher education institutes should invest in their own data repositories if funding/resources are available. A detailed guide on considerations in relation to setting up a data repository was developed by the DCC: [Where to keep research data](https://www.dcc.ac.uk/guidance/how-guides/where-keep-research-data). Integrating institutions in the emerging global research support infrastructure requires awareness and engagement with initiatives like the [European Open Science Cloud](https://eosc-portal.eu/).

Institutions can provide their researchers with guidance in navigating the world of repositories. Combining a multi-purpose institutional repository with advice on the selection of [suitable special purpose repositories](https://www.openaire.eu/opendatapilot-repository-guide) elsewhere for suitable datasets is a way forward for many institutions.

**Digital preservation**

While most repositories have at least some features that can be used to ensure long-term FAIRness of datasets, thorough digital preservation requires a specific set of organisational, technical and digital object management abilities based on mature standards and assessment processes. Repositories that reach these standards may be certified as &#39;trustworthy digital repositories&#39; (TDR) to signify that they offer active preservation of data and metadata to maintain their value to their community of users over time. Initiatives include the [CoreTrustSeal](https://www.coretrustseal.org/) and the [nestor Seal](https://www.langzeitarchivierung.de/Webs/nestor/EN/Zertifizierung/nestor_Siegel/siegel.html). The FAIRsFAIR project has developed a [capability/maturity](https://doi.org/10.5281/zenodo.5471568) approach that aligns TDR capability with the requirements for enabling FAIR data over time

Digital preservation as defined by the _OAIS reference model_ (CCSDS 2012) ensures that data are secure, findable and usable for as long as needed. Not only do many research funders require datasets to be made available for up to ten years, or in perpetuity, it is also best practice and in the interest of both the institute and individual researchers to ensure that generated research data remain accessible after a period of time, even if the software and technology in use at that time are now outdated.

The [*DPC Rapid Assessment Model*](https://www.dpconline.org/digipres/implement-digipres/dpc-ram) (DPC 2021) has been designed to perform rapid benchmarking of an organisation&#39;s digital preservation capacity. This includes tools and considerations when making a business case to implement digital preservation as well as procurement and training. The DPC also hosts the [Digital Preservation Handbook](https://www.dpconline.org/handbook) (DPC 2015) which offers plenty of advice on how institutions can develop their capacities in this area.

**Learn more:**

- Lesson Plan 8: [Persistent identifiers (PIDs)](../5FAIRlessonPlans/8LessonPlan.md)
- Lesson Plan 11: [Repositories](../5FAIRlessonPlans/11LessonPlan.md)

---
