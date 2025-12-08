---
title: Data Management Plan
layout: about
permalink: /dmp.html
---

# Data Management Plan

### Project Description

This digital collection uses CollectionBuilder, an open-source framework for creating digital collection websites from metadata stored in Google Sheets and digital objects hosted on GitHub. Our project documents early representations of queer identities in popular entertainment through photographs, postcards, sheet music, and artistic renderings of male and female impersonators from approximately 1880–1934. The collection aggregates materials from multiple GLAM repositories including the Digital Transgender Archive, New York Public Library Digital Collections, JD Doyle Archives, and Queer Music Heritage Archive. 

By bringing together these dispersed archival materials in a single, searchable interface, the project serves LGBTQ+ community members, educators, students, and researchers seeking primary source materials that document queer visibility in mainstream entertainment during periods of social repression. The CollectionBuilder platform offers interpretive visualization features including timeline views, geographic mapping, and subject browsing while maintaining long-term sustainability through static site generation. The site is freely available online with no authentication barriers, hosted on GitHub Pages, and accessible to anyone with internet access.

### Roles and Responsibilities*

Data management responsibilities are distributed across five specialized roles. The Project Manager coordinates activities, leads quality reviews, manages Google Drive, and submits deliverables. The Collection Development Manager makes final decisions about object inclusion and writes collection descriptions. The Object Preservation Manager oversees storage organization, establishes file naming standards, and ensures backup copies exist. The Metadata Manager coordinates cataloging of all 21 objects, ensures adherence to the metadata application profile with 21 defined fields, and maintains the master spreadsheet. The Repository Manager validates technical requirements, manages GitHub setup, and troubleshoots platform issues.

If team members become unavailable, the Project Manager assumes Repository Manager duties with Object Preservation Manager guidance, and the Metadata Manager assumes Project Manager coordination. All members access complete materials through Google Drive and GitHub.

### Methodology and Project Workflow

Our data lifecycle is designed to support consistency, quality control, and reliable access:

- **Week 1–2: Selection and acquisition.** The Collection Development Manager identifies performers and candidate objects in GLAM repositories. The Object Preservation Manager downloads the highest-resolution files and applies the file naming standard (`performer_archive_objecttype_description_year.jpg`).
- **Week 2–3: Metadata creation and standardization.** The Metadata Manager coordinates description of each object in a shared Google Sheets metadata spreadsheet, following the Metadata Application Profile (MAP) and data dictionary. Required fields are completed and normalized (dates, locations, rights statements).
- **Week 3–4: Quality review and technical integration.** The Project Manager leads quality checks for completeness, spelling, field consistency, and controlled vocabularies. The Repository Manager syncs the metadata CSV and objects to GitHub, configures CollectionBuilder settings, and verifies that visualizations (map, timeline, browse views) render correctly.
- **Week 5 and beyond: Publication and maintenance.** Once the site is published via GitHub Pages, the team performs periodic checks for broken links, display errors, and metadata issues. Updates are made in Google Sheets and pushed to GitHub via CSV exports.

Backups and quality control are embedded throughout this workflow. Google Drive maintains working copies of the metadata and documentation; GitHub provides version-controlled backups of code, configuration, and CSVs. Any corrections identified during quality review or later use are documented in Google Drive and committed to the repository.

### Anticipated Data

The collection consists of 21 JPEG files, including 10 sheet music covers, 7 photographs, 2 postcards, 1 painting reproduction, and 1 advertisement. The metadata CSV is under 1 MB, and documentation files total 2–3 MB. Complete project size, including the CollectionBuilder codebase, is approximately 50–70 MB.

All objects are historical materials from circa 1870–1930. Rights status uses RightsStatements.org URIs: 18 objects are “Copyright Undetermined” (http://rightsstatements.org/vocab/UND/1.0/) and 3 are “No Copyright - United States” (http://rightsstatements.org/vocab/NoC-US/1.0/). The CollectionBuilder site and our original metadata, documentation, and data dictionary are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0), enabling reuse with attribution.

Objects were acquired through systematic research using GLAM resources to identify performers, then downloading highest-resolution files from institutional repositories. Files were renamed using our standard convention:  
`performer_archive_objecttype_description_year.jpg`.

All access copies are stored as JPEGs, following Library of Congress format recommendations for web-delivered images. While many source repositories may also provide TIFFs or other preservation formats, we use JPEGs to ensure that all objects load quickly and reliably in a browser and on lower-bandwidth connections.

### Documentation and Metadata

The collection has produced a significant amount of metadata that has been tracked, documented, and applied in accordance with a group-developed Metadata Application Profile (MAP). The MAP ensures that users cataloging items in the collection know what information to include and how to format it, resulting in consistent description across all items. This consistency supports clarity, browsability, and reproducibility, while ensuring the collection remains usable and accessible to its intended audience.

The guidelines also ensure that all metadata meets CollectionBuilder’s data entry and formatting standards so the site can function properly. For reference, the CollectionBuilder documentation on CSV metadata and metadata formatting was used to inform and maintain these standards. Users can access the metadata via the “Data” section on our collection website, where the metadata CSV is made available for viewing and download, and via the item pages that display fielded metadata for each object.

### Storage and Backup

We use a three-tier storage and backup strategy:

1. **Google Drive (working storage).**  
   A shared Google Drive serves as the primary working environment for the project team. It follows a simple, documented folder structure:  
   - `/objects` – JPEG image files for all 21 objects  
   - `/metadata` – the CollectionBuilder CSV, MAP, and data dictionary  
   - `/documentation` – project notes, planning documents, and assignment materials  

   This structure makes it easier for team members to locate specific materials and ensures that working files remain organized.

2. **GitHub repository (version-controlled storage).**  
   The GitHub repository hosts the CollectionBuilder configuration, metadata CSV, and a copy of the objects in the expected `objects/` directory. Git version control allows us to track changes, revert to prior versions, and document updates to both code and data.

3. **GitHub Pages site (public access).**  
   The built CollectionBuilder site is deployed via GitHub Pages as static web content. Although this environment is primarily for access, it also functions as another copy of the HTML-rendered data.

Individual team members may keep local copies of files on their personal computers while actively working on the project, but Google Drive and GitHub are considered the authoritative storage locations.

### Data Sharing

Our data is shared through the public-facing CollectionBuilder website hosted by GitHub Pages. The site provides:

- Item pages that display JPEG images of each object and their associated metadata fields.
- Browse, map, and timeline views that allow users to explore the data by subject, date, and location.
- A link to the project’s metadata CSV and documentation in GitHub for users who want to reuse or analyze the data.

We are making available:

- Web-optimized JPEG image files of the objects.
- The metadata CSV describing each object.
- Supplemental documentation, including the Metadata Application Profile and data dictionary.

Others may want to reuse our data to conduct historical research into American vaudeville, queer performance history, or media representation, or for personal and academic projects. Reuse must align with the rights information explicitly recorded in the metadata fields and the licenses provided by the holding institutions. Editing access to the Google Drive is restricted to the project team; external collaborators who need working access can contact the Drive administrator for coordination.

### Period of Data Retention

During Fall 2025, all components are actively maintained across the three storage tiers described above. The metadata spreadsheet is updated as needed, with changes exported to CSV and synced to GitHub. Quality reviews identify and correct errors throughout the term.

The GitHub repository will likely remain accessible indefinitely, as CollectionBuilder’s static architecture requires no ongoing server maintenance. If GitHub discontinues free hosting, any member of the team can fork the repository or migrate the static site to an alternative platform. If UO accounts are deactivated, the Project Manager will coordinate a transfer of ownership to personal accounts at least 30 days in advance. If team members become unavailable, documented procedures stored in Google Drive enable another member to continue maintenance with minimal disruption.

### Licensing and Ethical Issues

The photos and artwork we used were drawn from public collections that we cite in our metadata, and we included all rights information provided by the originating institutions. Each item’s rights status is represented using RightsStatements.org URIs and, where appropriate, accompanied by a descriptive rights note.

Our own contributions—original metadata, documentation, and the site configuration—are licensed under CC BY 4.0, allowing reuse with attribution. The underlying images are either designated as public domain or “No Copyright - United States,” or have “Copyright Undetermined” status but are made available by the holding institutions for educational and research use. Users are expected to follow the rights statements and institutional guidelines linked on each item.

We intentionally avoided images that depict Indigenous communities, enslaved people, children, patients, or institutionalized individuals. However, there remains an ethical risk that images of female and male impersonators could be taken out of context or used to stereotype marginalized communities. Making these materials more discoverable in a public collection increases both their educational value and the possibility of misuse, such as using sensitive historical imagery in marketing or divorced from critical context. We mitigate this risk through careful description, proper attribution, and linking back to the holding institutions’ collections and rights frameworks.

---

### Appendix 

#### Data Dictionary

The data dictionary, created and agreed upon by group consensus, followed standards from both CollectionBuilder and other authorities, such as TGN (Thesaurus of Geographic Names) and RightsStatements.org. Our naming standards conform to the guidelines set by these authorities to ensure consistency. Each field in the dictionary specifies which authority it refers to. The only field that employed a pick list was the subject field since the nature of this field was very project-specific.

| Field Name        | normalized_field_name | Definition | Example |
|-------------------|-----------------------|-----------|---------|
| Object ID         | objectid              | As defined by CollectionBuilder documentation and standards, the field that CollectionBuilder uses to identify each object. Please do not include the file format. | bertsavoy_cbm_memorial_1923 |
| Filename          | filename              | This field will be the digital object’s filename, including the file extension, or a full URL to a file hosted externally to your project. | img101_b6_photographs_01.jpg |
| Title             | title                 | A title is a word or phrase that names or designates something, such as a book, artwork, document, or piece of media. | Bert Savoy - Calla Lillies |
| Creator           | creator               | As defined by CollectionBuilder documentation, “the creator property designates an entity primarily responsible for making the resource” (CollectionBuilder Documentation). | Charles Demouth |
| Date              | date                  | The date indicates a point of time associated with the object. | 1927; 1927-03-26; 1927-03 |
| Description       | description           | “An account of the object” per CollectionBuilder Documentation and DublinCore standards, either generated by Collection Managers or as defined by the source. | Postcard of the Memorial Gymnasium on the University of Idaho campus in Moscow, Idaho. |
| Subject           | subject               | A term or phrase that describes the topic or content of a resource, often used to support discovery, classification, and retrieval. | Karyl Norman; Bert Savoy; Vesta Tilley |
| Location          | location              | This field designates a geographic location to which the item is tied. | New York (United States); Hollywood (California, United States); Cincinnati (Ohio, United States); Unknown |
| Source            | source                | The source field designates a related source collection or resource from which the object is derived. | PG 5, University of Idaho Library Special Collections and Archives |
| Identifier        | identifier            | The identifier field is used to preserve the unique identifier assigned to the object by the object’s (usually physical) source collection. | ASC.2012.53 |
| Type              | type                  | An object’s type distinguishes between types of image, sound, text, etc., using a one- or two-value input. | Image; Still Image |
| Format            | format                | As defined by CollectionBuilder documentation, format “indicates the object’s media type” (CollectionBuilder Documentation). | image/jpeg |
| Language          | language              | As defined by the Dublin Core standard, a language of the intellectual content of the resource. | English |
| Rights            | rights                | The rights field should include a free-text rights statement describing information about rights held in and over the object. | Educational use includes non-commercial use of text and images in materials for teaching and research purposes. Digital reproduction rights granted by the University of Idaho Library. For other uses beyond free use, please contact the University of Idaho Library Special Collections and Archives Department. |
| Rights Statement  | rightsstatement       | This field is a standardized rights statement, designated in the form of a URI. | http://rightsstatements.org/vocab/InC/1.0/ |
| Display Template  | display_template      | As defined by CollectionBuilder documentation, display_template is “used for the Item page and is used in logic to choose representations in other pages” (CollectionBuilder Documentation). | image |
| Alternative Text  | image_alt_text        | A brief description of the object. This is used by machine reading for visually impaired users. Additionally, if an object does not load, it will display the alt text instead. | A series of illustrations of Julian Eltinge by Winsor M’Cay. The piece is titled, “Winsor M’Cay draws impressions of Mr. Julian Eltinge at Orpheum”. |
| Cataloguer        | cataloguer            | The first name of the Collection Manager who catalogued the object. | Calista |
| Citation          | citation              | An MLA citation of digital object from the source. | Billy Rose Theatre Division, The New York Public Library. "Bothwell Browne" The New York Public Library Digital Collections. 1850–2020. https://digitalcollections.nypl.org/items/86257580-ff5d-012f-7e78-58d385a7bc34 |

#### Additional Documentation

[Metadata Application Profile](https://github.com/LIBDSCI350m-Fall25/group1/blob/main/objects/metadata-application-profile.docx.pdf)

[File Naming Scheme](https://github.com/LIBDSCI350m-Fall25/group1/blob/main/objects/file%20naming%20convention.pdf)
