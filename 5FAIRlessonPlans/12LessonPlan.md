## Lesson plan 12: Dealing with confidential, personal, sensitive and private data and ethical aspects

**FAIR elements:**

**Accessible**

Once the user finds the required data, they need to know how they can be accessed, possibly including authentication and authorisation.

[**A1.** (Meta)data are retrievable by their identifier using a standardised communications protocol](https://www.go-fair.org/fair-principles/542-2/)

[**A1.1.** The protocol is open, free, and universally implementable](https://www.go-fair.org/fair-principles/a1-1-protocol-open-free-universally-implementable/)

[**A1.2.** The protocol allows for an authentication and authorisation procedure, where necessary](https://www.go-fair.org/fair-principles/a1-2-protocol-allows-authentication-authorisation-required/)

[**A2.** Metadata are accessible, even when the data are no longer available](https://www.go-fair.org/fair-principles/a2-metadata-accessible-even-data-no-longer-available/)

**Reusable**

The ultimate goal of FAIR is to optimise the reuse of data. To achieve this, metadata and data should be well-described so that they can be replicated and/or combined in different settings.

[**R1.** (Meta)data are richly described with a plurality of accurate and relevant attributes](https://www.go-fair.org/fair-principles/r1-metadata-richly-described-plurality-accurate-relevant-attributes/)

[**R1.1.** (Meta)data are released with a clear and accessible data usage license](https://www.go-fair.org/fair-principles/r1-1-metadata-released-clear-accessible-data-usage-license/)

[**R1.2.** (Meta)data are associated with detailed provenance](https://www.go-fair.org/fair-principles/r1-2-metadata-associated-detailed-provenance/)

[**R1.3.** (Meta)data meet domain-relevant community standards](https://www.go-fair.org/fair-principles/r1-3-metadata-meet-domain-relevant-community-standards/)

**Primary audience(s):** Bachelor&#39;s, master&#39;s, PhD degree students

This lesson plan contains ideas for teaching students and researchers on how to deal with the FAIR principles in relation to data that cannot be shared publicly. There are data types that cannot be freely shared, such as confidential information regarding trade secrets, information about human participants, sensitive information about endangered species, data under contractual agreements that prevent data users from further sharing, and information with potential ethical implications. For the purposes of this lesson plan, we will refer to all such data as &#39;confidential data&#39;. Even though sharing confidential data is less straightforward than data that can be routinely shared, such data can nevertheless benefit from applying the FAIR principles so that researchers working with confidential data can benefit from work that has been done before in their domain.

Sharing confidential data will often come down to restricting access to a dataset. In this lesson plan, we provide lesson objectives and activities that can be done in class to discuss aspects worth considering when making confidential data findable and accessible for others.

Since countries have their own legislation and guidelines for working with confidential data of the types described above, we will not provide any formal definitions of these types of data here. The lesson plan is general enough to be adjusted to local legislation. The idea here is that readers who wish to use this lesson plan can adapt it in line with legislation applicable to the research context in which the students are working. The main message is that data which cannot be shared freely for one reason or another can still be made FAIR by adjusting the strategies implemented just enough to suit the circumstances and ensure compliance with local legislation and guidelines.

**Learning outcomes:**

General (confidential, personal, sensitive and private data):

- Can explain reasons for data protection (confidential, personal, sensitive or private data)
- Knows basic rules and legal regulations for sensitive data, e.g. GDPR
- Can list the requirements students need to meet when working with these types of data, adhering to applicable laws and regulations related to the research context
- Can analyse compliance to protect data appropriately
- Can apply mechanisms to protect data appropriately (concrete steps that researchers can take during the research lifecycle to protect the confidentiality of their research data where necessary)
- Can define different levels of data security (user, folder, files)
- Can explain and apply different methods of data protection (physical, password protection, encryption, etc.)
- Can use different levels of security for their own work
- Can identify which repositories may be used to archive/publish confidential data
- Can recognise that metadata of confidential data can be made public
- Knows that if a researcher wants to control access to an archived dataset, an organisational body and technical infrastructure need to be in place to deal with data access requests. Recognises that a set of criteria needs to be available on the basis of which access will be granted or denied
- Can recognise that it is possible to split up a dataset from a research project and store/archive/publish the separate parts with different access restrictions, e.g. one with confidential data (restricted access) and one with non-confidential data (publicly accessible, for example protocols, syntaxes)

Dealing with personal data:

- Knows that informed consent needs to be set up in a certain way to be able to publish/share personal data
- Knows that data repositories may require data to be de-identified to a certain extent before they may be uploaded there
- Can describe directly identifying attributes and detect them in data
- Can explain the difference between anonymisation and pseudonymisation
- Can anonymise/pseudonymise data by stripping identifying attributes
- Knows that for reasons of information security, a pseudonymised dataset and the corresponding key file should be archived separately

Dealing with ethical aspects:

- Recognises ethical aspects a researcher needs to take into account when planning to publish/share their data

**Summary of tasks/actions:**

General (confidential, personal, sensitive and private data):

1. Outline what research confidentiality means:
   1. Define research confidentiality and give examples of confidentiality requirements for sample projects involving human participants, industries, endangered species or protected natural resources.
   2. Let learners identify what types of data they are working with and how they should deal with them in terms of applicable legislation:
      1. Take the applicable legislation, protocols or guidelines for your country/region or discipline. Familiarise your students with the main principles, preferably communicated in such a way that it speaks to your audience, i.e. try to avoid explanations that are formulated in formal legal language, and relate these main principles to practical actions for your audience. The overview below lists some examples and is far from exhaustive, so make sure to discuss legislation relevant for your audience.
         1. Privacy legislation (see this [database on data protection and privacy laws of the world](https://www.dlapiperdataprotection.com/index.html) to find the relevant legislation for your lesson). Note that students need to take into account the legislation in the country of the institution they are affiliated to and to the country/countries in which they are carrying out their research
            1. Europe: [GDPR](http://data.europa.eu/eli/reg/2016/679/oj)
            2. Canada: [PIPEDA](https://www.priv.gc.ca/en/privacy-topics/privacy-laws-in-canada/the-personal-information-protection-and-electronic-documents-act-pipeda/pipeda_brief/)
            3. Australia: [Privacy Act 1988](https://www.legislation.gov.au/Series/C2004A03712)
            4. UK: Common law duty of confidentiality
      2. Medical legislation
         1. Netherlands: [WMO](https://wetten.overheid.nl/BWBR0009408/2021-05-26) (legal framework for medical scientific research)
         2. U.S.: [HIPAA](https://www.hhs.gov/hipaa/for-professionals/compliance-enforcement/index.html)
      3. Animal testing regulation
         1. Netherlands: [Wet op de dierproeven](https://wetten.overheid.nl/BWBR0003081/2019-01-01) (legal framework for research with animal testing)
   3. Ask students to discuss their own research projects in groups with a focus on the types of data they are collecting, how the relevant laws and regulations apply to them, and what this means for their workflow when it comes to making data available to others.
2. Explain the rationale behind the legislation, protocols and guidelines you discuss so that students understand why they are there and do not simply consider them boxes that need to be ticked. You can ask students to reflect upon the relevant requirements by producing statements and discussing them in the group.
3. Introduce security measures that students can take to protect research participants and sensitive data related to them:
   1. Prevent unauthorised access by means of reliable verification methods (passwords, two-factor authentication)
   2. Pseudonymisation of personal data
   3. Store key files in a location separate from other research data
   4. Encryption (full disk, folders, files)
   5. Grant access rights to those authorised to access the data
4. Ask students to search for repositories (at their institution or outside, use, e.g. [https://www.re3data.org/](https://www.re3data.org/)) that are suitable for archiving personal data. Instruct them to read the repository policies and to decide if they could use them to store/archive/publish their data. Let them share their results with the rest of the group so they can inform each other about potentially useful repositories.
5. Introduce the concepts of depositing data and providing a description of a dataset. Explain that even if a dataset cannot be shared because it contains confidential data, the metadata describing such a dataset can be made public. Show examples of such cases, for example:
   1. [Sagres ship meteorological data](https://rdm.inesctec.pt/dataset/nis-2021-002) (in INESC TEC research data repository)
   2. [The influence of screen time on sleep quality](https://easy.dans.knaw.nl/ui/datasets/id/easy-dataset:213884/tab/1) (in DANS Data Stations)
6. Practical issues around sharing confidential data (this task could be too advanced for bachelor&#39;s and master&#39;s degree students; it is up to the teacher/instructor to assess whether this part should be included or excluded):
   1. Explain practical aspects which need to be arranged if a researcher wants to have control over who has access to a dataset, both in a technical and organisational sense. Even though these things are often beyond a researcher&#39;s control, they do influence the choice of a repository and researchers need to be aware of these issues when they work with confidential data and are aiming to share their data in some way.
      1. Technical:
         1. The location where data are stored should have the option to restrict access so only authorised people can access the data.
         2. There should be a contact point where data access requests can be sent.
      2. Organisational:
         1. There needs to be someone who can receive data access requests and reply to them.
         2. There needs to be someone who has the authority to decide whether a data access request will be granted or denied.
         3. A set of criteria needs to be available as a decision-making basis for granting or denying access.
   2. Conduct an exercise in which researchers think about conditions under which they would like to share their data. First, give them some examples of conditions for reuse and let them formulate conditions they would like to work with afterwards. Examples of conditions (based on the Terms of Use of the [PsychData repository](https://www.psychdata.de/index.php?main=take&amp;sub=empfang&amp;lang=eng) and the [template for a data user agreement](https://open-brain-consent.readthedocs.io/en/latest/gdpr/data_user_agreement.html) from Open Brain Consent):
    1. Data may only be used for the purpose of academic research and instruction
    2. Data may not be forwarded to third parties
    3. Any publication based on the data must cite the dataset
    4. No attempts may be made to re-identify or contact participants
    5. Data needs to be stored in a secure work environment. Anyone reusing the data must provide the technical specification of the secure environment
    6. Data will only be provided when the applicant has approval for their research project from the Institutional Review Board of the applicant&#39;s institution
7. Explain the strategy of storing two separate datasets:
   1. Illustrate that in a research project, two data packages may emerge once the data are ready for storing and publishing: one containing the confidential data, and another containing the non-confidential materials that could be valuable to other researchers, for example protocols, syntaxes.
   2. Provide examples of such cases so students are presented with a tangible form of what a dataset with different access restrictions could look like:
      1. [FEM growth and yield data monocultures - Grand fir](https://doi.org/10.17026%2Fdans-xgg-3zrb) in DANS Data Station Life, Health and Medical Sciences. The plot data book, tree maps atlas and README file are publicly accessible, while access rights are required for the other files
      2. [European Quality of Life Survey](https://beta.ukdataservice.ac.uk/datacatalogue/series/series?id=200013#!/access-data) in UK Data Service. The integrated data file requires login, whereas the other files can be explored online without a login
 
   Dealing with personal data:
8. On setting up informed consent to be able to share data:
   1. Give examples of aspects that need to be included in an informed consent form to be able to share data at the end of a research project. You can use the examples provided here, or find examples relevant to your situation:
      1. The [Ultimate consent form](https://open-brain-consent.readthedocs.io/en/latest/ultimate.html) from Open Brain Consent, or the [GDPR edition](https://open-brain-consent.readthedocs.io/en/stable/gdpr/ultimate_gdpr.html)
      2. Tool [Research Data Management Language for informed consent](https://doi.org/10.5281/zenodo.4060460), Portage Network
   2. Ask students to take an informed consent template that is used in their department or suited to their discipline. Ask them to study the template and to find out if there are any statements about making data available to others after the project.
9. Familiarise students with instructions that repositories might have for de-identifying data before they may be uploaded there:
   1.  Give examples of repositories&#39; instructions to de-identify data to some extent. You can use the example provided here, or find examples relevant to your situation:
       1.  &#39;The practice of protecting confidentiality&#39; in the [Guide to Social Science Data Preparation and Archiving](https://www.icpsr.umich.edu/files/deposit/dataprep.pdf) - On p. 42-43 you can read how direct and indirect identifiers need to be treated when preparing a dataset for reuse.
   2.  Ask students whether they have a repository in mind in which they would like to deposit their data. Ask them to find out if this repository has any instructions on de-identifying data. Discuss the findings with the group.
10. On de-identifying data:
    1.  Where relevant, demonstrate the difference between pseudonymous and anonymous data.
    2.  Introduce background materials on pseudonymising and anonymising data, for example:
        1. [Anonymisation step-by-step](https://ukdataservice.ac.uk/learning-hub/research-data-management/anonymisation/anonymisation-step-by-step/), UK Data Service – Practical steps researchers can follow to find potentially identifiable information in their data, to assess the uniqueness of values in their data and the risks related to that, and to make the data less identifiable
        2. [Pseudonymisation in small-scale quantitative research](https://www.lcrdm.nl/files/lcrdm/2019-12/LCRDM%20Basic%20Steps%20Pseudonymization%202019.pdf) – This overview presents nine basic steps for pseudonymising data
        3. Report [Dealing with pseudonymization and key files in small-scale research](https://www.lcrdm.nl/files/lcrdm/2019-12/LCRDM%20Pseudonymization%20and%20key%20files_ENG_online.pdf) – This report describes the nine steps from the overview above in a more detailed way
        4. [Guide to Social Science Data Preparation and Archiving](https://www.icpsr.umich.edu/files/deposit/dataprep.pdf) – On p. 42-43 you find concrete steps for de-identifying data
        5. [Anonymisation section](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/5.-Protect/Anonymisation) in the CESSDA Data Management Expert Guide – This section provides practical steps for making data about people less identifiable
        6. [Anonymisation postcard](https://www.lcrdm.nl/files/lcrdm/2020-01/Anonymization%20-%20reference%20card%20for%20researchers.pdf) – This postcard illustrates that even with very little and general information, individuals can be identified, depending on the context
        7. [Privacy risks matrix](https://www.lcrdm.nl/files/lcrdm/2020-01/LCRDM%20Risk%20management%20for%20research%20data%20about%20people.pdf) – The matrix on p. 4-5 explains the risk levels for re-identification of data about people. P. 6 provides examples of various levels of de-identification
        8.  [Brain MRI data sharing guide](https://doi.org/10.5281/zenodo.3822289) (and see the [interactive version](https://www.dorienhuijser.com/MRIsharingguide/) as well) – This guide provides MRI researchers with practical information about the implications of the GDPR for MRI research. On slide 8 you can find practical advice on how to de-identify MRI data; some of the methods discussed there can be applied to other types of data as well.

        Based on these sources (or other relevant sources), explain what it means for data to be pseudonymous and anonymous (depending on the applicable legislation) and, based on that, help students to find out which steps can be taken to pseudonymise data and to determine if their data can be anonymised.
    3. Show examples of strategies and tools that are available for pseudonymising and anonymising data, for example:
       1. [Anonymising qualitative data](https://ukdataservice.ac.uk/learning-hub/research-data-management/anonymisation/anonymising-quantitative-data/), UK Data Service – Advice on how to de-identify various types of qualitative data: text, transcripts and audio-visual data
       2. [Anonymising quantitative data](https://ukdataservice.ac.uk/learning-hub/research-data-management/anonymisation/anonymising-qualitative-data/), UK Data Service – Advice on how to de-identify quantitative data, for example by removing or aggregating variables or reducing the precision of a variable
       3. [Amnesia Anonymization tool](https://amnesia.openaire.eu/) – A data anonymisation tool that removes identifying information from data, both by removing direct identifiers and transforming indirect identifiers to avoid unique values in a dataset.  
       Ask students to discuss in groups which de-identification techniques are useful for their own research data.
11. Illustrate that in the case of pseudonymised data, a key file may exist which enables people to link direct identifiers to the research data again. Explain that, for security reasons, this key file should be stored in a different location to the file(s) with the research data, making it difficult to link the two files.
 
    Dealing with ethical aspects:
 
 12. Explain that sharing or publishing data should not harm individuals, which could for example be the case if the data have been collected among vulnerable groups, or when individuals have a unique set of circumstances. Refer students to the ethics committee or review board in their institution to help them assess if data sharing or data publishing could potentially be problematic for the participants involved.

**Materials/Equipment**

- Computer/laptop
- Internet/browser

**References**

***Useful links***

- [Database on data protection and privacy laws of the world](https://www.dlapiperdataprotection.com/index.html)

***Background information on personal data in research***

- [Research data risk matrix](https://doi.org/10.5281/zenodo.4060448)
- [Anonymization postcard](https://www.lcrdm.nl/files/lcrdm/2020-01/Anonymization%20-%20reference%20card%20for%20researchers.pdf), LCRDM (Dutch National Coordination point for RDM)
- [Privacy risks matrix](https://www.lcrdm.nl/files/lcrdm/2020-01/Anonymization%20-%20reference%20card%20for%20researchers.pdf), LCRDM
- [Basic steps for pseudonymization](https://www.lcrdm.nl/files/lcrdm/2019-12/LCRDM%20Basic%20Steps%20Pseudonymization%202019.pdf), LCRDM
- [Pseudonymization report](https://www.lcrdm.nl/files/lcrdm/2019-12/LCRDM%20Pseudonymization%20and%20key%20files_ENG_online.pdf), LCRDM
- [Research Data Management Language for informed consent](https://doi.org/10.5281/zenodo.4060460), Portage Network

***Guides***

- [Brain MRI data sharing guide](http://doi.org/10.5281/zenodo.4740126)
- [CESSDA Data Management Expert Guide \&gt; Anonimysation](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/5.-Protect/Anonymisation), Consortium of European Social Science Data Archives
- [Guide to Social Science Data Preparation and Archiving](https://www.icpsr.umich.edu/files/deposit/dataprep.pdf), ICPSR (Inter-university Consortium for Political and Social Research)
- [Learning hub on Research Data Management](https://ukdataservice.ac.uk/learning-hub/research-data-management/) with advice on anonymisation, UK Data Service
- [Anonymising qualitative data](https://ukdataservice.ac.uk/learning-hub/research-data-management/anonymisation/anonymising-quantitative-data/), UK Data Service
- [Anonymising quantitative data](https://ukdataservice.ac.uk/learning-hub/research-data-management/anonymisation/anonymising-qualitative-data/), UK Data Service
- [Anonymisation step-by-step](https://ukdataservice.ac.uk/learning-hub/research-data-management/anonymisation/anonymisation-step-by-step/), UK Data Service
- Guide [Publishing and sharing sensitive data](https://www.ands.org.au/__data/assets/pdf_file/0010/489187/Sensitive-Data-Guide-2018.pdf), Australian National Data Service
- [RDM Guidance for COVID-19](https://portagenetwork.ca/tools-and-resources/rdm-guidance-for-covid-19/?cn-reloaded=1) including data sharing, Portage Network
- [Code of Conduct Toolkit for GODAN](https://www.godan.info/codes) (Global Open Data for Agriculture &amp; Nutrition)
- [Human Participant Research Data Risk Matrix](https://doi.org/10.5281/zenodo.4060448), Portage Network

***Tools***

- [Amnesia Anonymization tool](https://amnesia.openaire.eu/)
- Registry of Research Data Repositories [https://www.re3data.org/](https://www.re3data.org/)

***Use cases***

- [Sagres ship meteorological data](https://rdm.inesctec.pt/dataset/nis-2021-002) (in INESC TEC research data repository)
- [The influence of screen time on sleep quality](https://doi.org/10.17026%2Fdans-zmv-3mha) (in DANS Data Stations)
- [FEM growth and yield data monocultures – Grand fir](https://doi.org/10.17026%2Fdans-xgg-3zrb) in DANS Data Station Life, Health and Medical Sciences.
- [European Quality of Life Survey](https://beta.ukdataservice.ac.uk/datacatalogue/series/series?id=200013#!/access-data) in UK Data Service

***Templates***

- [Data User Agreement](https://open-brain-consent.readthedocs.io/en/latest/gdpr/data_user_agreement.html), Open Brain Consent
- [Ultimate consent form](https://open-brain-consent.readthedocs.io/en/latest/ultimate.html), Open Brain Consent
- [Ultimate consent form - GDPR edition](https://open-brain-consent.readthedocs.io/en/stable/gdpr/ultimate_gdpr.html), Open Brain Consent

**Take-home tasks**

1. Ask students to take the informed consent template they intend to use and then discuss it with a privacy expert in their institution, adjusting as and where necessary to be able to publish/share data in the way they envision at the end of their project.
2. Ask students to have a close look at their own data and determine if they can be anonymised and, if so, if the anonymised result is still worth publishing/sharing.
3. Ask students to practice pseudonymisation and anonymisation techniques with a sample of their dataset so they learn how these techniques affect their data.
