## Lesson plan 11: Repositories

**FAIR elements:** All

**Primary audience(s):** Bachelor&#39;s, master&#39;s, PhD degree students

**Learning outcomes**

- Can explain what repositories are, what they are useful for, and how they help with FAIR
- Can identify and understand the different types of repositories
- Can explain what a trusted data repository is and how to find it, e.g. via re3data.org or FAIRsharing
- Can compare different certifications for data repositories, e.g. CoreTrustSeal, CLARIN certification
- Can articulate different criteria that can be used to choose a repository
- Can discover trusted repositories and identify those that are certified
- Can use a trusted repository to share research output

**Summary of tasks/actions:**

1. Introduce the concept of repositories.
   1. Explain the following:

      Repositories are used to store, document and publish all kinds of digital objects. They are storage locations for digital (and physical) objects which enable the separate publication and archiving of digital objects
      
   2. Discuss: Why use a repository?
   
      Data repositories can help make a researcher&#39;s data more discoverable and accessible, and lead to potential reuse. Using a repository can lead to increased citations of your work (22). Data repositories can also serve as backups during rare events where data are lost to the researcher and must be retrieved. Depending on the discipline requirements – publisher, funders, institutional policies, national policies – researchers may be required to store their data in certain repositories.
      
      Practical exercise: Check what you need to address with your local institutional requirements. Are you obliged to upload your research outputs locally?
2. FAIR principles and repositories
   1. Findability: Repositories can provide a persistent and unique identifier for data; help to add rich, clear and machine-readable metadata to data; make the data findable using web-based search engines
   2. Accessibility: Repositories can have open, free and standardised communication protocols with authentication and authorisation procedures; provide the existence of metadata independent of the availability of the data
   3. Interoperability: Repositories can use common semantic language, making data interoperable with applications or other workflows for analysis, storage and processing; help to provide metadata with vocabularies according to FAIR principles.
   4. Reusability: Repositories can promote data reuse; help to provide rich, accurate relevant metadata with a data usage licence, detailed provenance, and using common standards.
3. Different types of repositories:
   1. Identify discipline-specific vs. cross-discipline repositories: Repositories can be classified according to various aspects. In most cases, they are distinguished by whether they are discipline-specific, cross-discipline/generic, computing centre-based, or institutional. Discipline-specific or disciplinary repositories offer the benefits of visibility in the research community, research data management expertise, specialised tools, and are already established services in some disciplines. However, not all academic subject areas have established discipline-specific repositories.
   
      Examples of free-to-use discipline-specific repositories:
      - [ICPSR](https://www.icpsr.umich.edu/web/pages/about/) for the social sciences
      - [PANGAEA](https://pangaea.de/) for Earth and space science data
      - [Crystallography Open Database (COD)](http://www.crystallography.net/) for chemistry &amp; crystallography
  
      For interdisciplinary research, assignment of the resulting data to a subject area may be difficult. Cross-disciplinary/generic repositories offer a solution here as they accept data regardless of data type, format, content, or disciplinary focus. In some cases, however, they do not curate the data or offer other forms of quality control. This responsibility lies with the author/depositor. Examples of cross-disciplinary, generic repositories that are free to use:
      - [ZENODO](https://zenodo.org/) (free to use, open source)
      - [Figshare](https://figshare.com/) (free to use)
  
     1. Institutional repositories are often free of charge and can be used for all of the institution&#39;s own subject areas. Many universities support research data management on campus through a central service. Research data services staff can be an excellent source of research data management support, including repository selection, and can help you comply with funder, publisher, and university requirements. Additionally, High Performance Computers (HPC) have infrastructure to support research using models and simulations, which may be involved in generating and/or analysing high-volume data. The IT operations team at the organisation may have recommendations for data management, storage and preservation.
4. Discuss how to choose a data repository
   1. When selecting a repository, consider these factors:
      - Choose a repository early on when you start your data project. This can help you with efficiently structuring and preparing your data when it comes time to share it.
      - Consider how FAIR a repository is in terms of the services it offers you (23).
        - The repository provides persistent identifiers, e.g. Digital Object Identifiers or DOIs. This is essential as it supports citation and linking to other research outcomes, e.g. papers, and grants.
      - Landing pages are provided for the digital objects with metadata that helps others find them, determine what they are, relate them to publications, and cite them. This allows your research to be more discoverable, reusable, and trackable via download statistics.
      - Responds to community needs, is preferably certified as a &#39;trustworthy data repository&#39; (e.g. [Core Trust Seal](https://www.coretrustseal.org/why-certification/certified-repositories/)), and addresses long term sustainability.
      - Is ideally internationally recognised, commonly used and endorsed by the respective community.
      - Matches your particular data needs, e.g. formats accepted; access, backup and recovery, and sustainability of the service. Most of this information should be contained within the data repository&#39;s policy pages.
      - Offers clear terms and conditions that meet legal requirements, e.g. for data protection, and allow reuse without unnecessary licensing conditions, e.g. restricted vs. open.
      - Provides guidance on how to cite the data that has been deposited.
      - Whether the repository charges for its services.
   2. There are a number of resources to help choose a repository. This chart is designed to assist researchers in finding a cross-disciplinary/generic repository should no discipline-specific repository be available to preserve their research data: [https://doi.org/10.5281/zenodo.3946719](https://doi.org/10.5281/zenodo.3946719)
   3. Discuss using a catalogue for data repositories: In order to find an appropriate repository, the cross-disciplinary directory re3data ([https://www.re3data.org](https://www.re3data.org/)) can be used. This is the outcome of a DFG-funded (Deutsche Forschungsgemeinschaft – German Research Foundation) project that lists German and international repositories for research data, with more than 2,580 entries at present. Another option is the RDA-endorsed FAIRsharing ([https://fairsharing.org/databases/)](https://fairsharing.org/databases/) which interlinks repositories, (meta)data standards and policies.
   4. For managing sensitive data, see [lesson plan 12](12LessonPlan.md) on &#39;Dealing with confidential, personal, sensitive and private data and ethical aspects&#39;.
5. **There is a wealth of data repositories out there. How do I find and choose an appropriate repository?**
   1. You can find a suitable repository by consulting [FAIRsharing](https://fairsharing.org/databases/) and [re3data.org](https://www.re3data.org/). Here you can select the discipline, type of data, and/or country. It is also possible to filter by very detailed criteria, for example, for repositories that charge a fee for data upload or where data use is restricted. Filtering by software is also an option and can be helpful if you are using an application programming interface (API) with a programming language/library, e.g. [Zenodo API and Python](https://developers.zenodo.org/?python), [R and Dataverse](https://www.rdocumentation.org/packages/dataverse/versions/0.3.8).
   2. Discuss with the class how to select a FAIR-aligned repository. Some infrastructure providers offer overviews of how their services enable FAIR.   
   Zenodo offers an overview of how the service responds to the FAIR principles: [https://about.zenodo.org/principles/](https://about.zenodo.org/principles/).  
 Figshare also published a statement paper on how it supports the FAIR principles: [https://knowledge.figshare.com/publisher/fair-figshare](https://knowledge.figshare.com/publisher/fair-figshare).
6. Apply your knowledge:
   1. Based on the &#39;How to choose a repository&#39; section and [OpenAire&#39;s guidance](https://www.openaire.eu/opendatapilot-repository-guide), use [FAIRsharing](https://fairsharing.org/databases/) or [re3data](https://www.re3data.org/) to find a trustworthy repository in political science. What did you find?
   2. From the &#39;FAIR principles and repositories&#39; section, use the [Zenodo Sandbox](https://sandbox.zenodo.org/) to upload test data, e.g. an example text file, and assign a licence. What did you find?
7. Take-home task:
   1. Understand how you can connect your research for better discovery. Read more about your digital presence: [https://data.agu.org/resources/digital-presence](https://data.agu.org/resources/digital-presence)

**Materials/Equipment**

- Computer/laptop
- Internet/browser
- Access for different repositories, e.g. credentials

**References**

- OpenAIRE (n.d.) How to select a data repository? Accessed 23 July 2021. [https://www.openaire.eu/opendatapilot-repository-guide](https://www.openaire.eu/opendatapilot-repository-guide).
- Biernacka, Katarzyna, Maik Bierwirth, Petra Buchholz, Dominika Dolzycka, Kerstin Helbig, Janna Neumann, Carolin Odebrecht, Cord Wiljes, and Ulrike Wuttke. _Train-the-Trainer Concept on Research Data Management_ (version 3.0). Zenodo, 2020.[https://doi.org/10.5281/zenodo.4071471](https://doi.org/10.5281/zenodo.4071471).
- Piwowar, Heather A., Vision, Todd J. &#39;Data reuse and the open data citation advantage&#39; _PeerJ_ 1:e175 (2013).[https://doi.org/10.7717/peerj.175](https://doi.org/10.7717/peerj.175).
- USGS (n.d.) Repositories. Accessed 23 July 2021.
[https://www.usgs.gov/products/data-and-tools/data-management/repositories](https://www.usgs.gov/products/data-and-tools/data-management/repositories)
- Library Carpentry (n.d.) Library Carpentry - FAIR Data and Software. Accessed 23 July 2021. [https://librarycarpentry.org/lc-fair-research/07-assessment/index.html](https://librarycarpentry.org/lc-fair-research/07-assessment/index.html)
- AGU (n.d.) Data &amp; Software for Authors. Accessed 23 July 2021. [https://www.agu.org/Publish-with-AGU/Publish/Author-Resources/Data-and-Software-for-Authors](https://www.agu.org/Publish-with-AGU/Publish/Author-Resources/Data-and-Software-for-Authors)
- COPDESS (2021) _Enabling FAIR Data - FAQs - Selecting a (FAIR) repository._ Accessed 24 June 2021. [http://www.copdess.org/enabling-fair-data-project/enabling-fair-data-faqs/#1\_Selecting\_a\_Repository](http://www.copdess.org/enabling-fair-data-project/enabling-fair-data-faqs/#1_Selecting_a_Repository).
- Stall, Shelley, Martone, Maryann E., Chandramouliswaran, Ishwar, Crosas, Mercè, Federer, Lisa, Gautier, Julian, Hahnel, Mark, Larkin, Jennie, Lowenberg, Daniella, Pfeiffer, Nicole, Sim, Ida, Smith, Tim, Van Gulick, Ana E., Walker, Erin, Wood, Julie, Zaringhalam, Maryam, &amp; Zigoni, Alberto. (2020). _Generalist Repository Comparison Chart._ Zenodo. [https://doi.org/10.5281/zenodo.3946719](https://doi.org/10.5281/zenodo.3946719)

---
