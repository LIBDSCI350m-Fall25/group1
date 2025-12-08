---
title: Data Management Plan
layout: about
permalink: /dmp.html
---

# Data Management Plan

Data Management Plan
DMP Requirements

### Project Description

This digital collection uses CollectionBuilder, an open-source framework for creating digital collection websites from metadata stored in Google Sheets and digital objects hosted on GitHub. Our project documents early representations of queer identities in popular entertainment through photographs, postcards, sheet music, and artistic renderings of male and female impersonators from approximately 1880-1934. The collection aggregates materials from multiple GLAM repositories including the Digital Transgender Archive, New York Public Library Digital Collections, JD Doyle Archives, and Queer Music Heritage Archive. By bringing together these dispersed archival materials in a single, searchable interface, the project serves LGBTQ+ community members, educators, students, and researchers seeking primary source materials that document queer visibility in mainstream entertainment during periods of social repression. The CollectionBuilder platform offers interpretive visualization features including timeline views, geographic mapping, and subject browsing while maintaining long-term sustainability through static site generation. The site is freely available online with no authentication barriers, hosted on GitHub Pages, and accessible to anyone with internet access.

### Roles and Responsibilities*

Data management responsibilities are distributed across five specialized roles. The Project Manager coordinates activities, leads quality reviews, manages Google Drive, and submits deliverables. The Collection Development Manager makes final decisions about object inclusion and writes collection descriptions. The Object Preservation Manager oversees storage organization, establishes file naming standards, and ensures backup copies exist. The Metadata Manager coordinates cataloging of all 21 objects, ensures adherence to the metadata application profile with 21 defined fields, and maintains the master spreadsheet. The Repository Manager validates technical requirements, manages GitHub setup, and troubleshoots platform issues.
If team members become unavailable, the Project Manager assumes Repository Manager duties with Object Preservation Manager guidance, and the Metadata Manager assumes Project Manager coordination. All members access complete materials through Google Drive and GitHub.

### Anticipated Data

The collection consists of 21 JPEG files, including 10 sheet music covers, 7 photographs, 2 postcards, 1 painting reproduction, and 1 advertisement. The metadata CSV is under 1 MB, and documentation files total 2-3 MB. Complete project size including CollectionBuilder code is approximately 50-70 MB.
All objects are historical materials from circa 1870-1930. Rights status uses RightsStatements.org URIs: 18 objects are "Copyright Undetermined" (http://rightsstatements.org/vocab/UND/1.0/) and 3 are "No Copyright - United States" (http://rightsstatements.org/vocab/NoC-US/1.0/). The CollectionBuilder site and our original metadata, documentation, and data dictionary are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0), enabling reuse with attribution.
Objects were acquired through systematic research using GLAM resources to identify performers, then downloading highest-resolution files from institutional repositories. Files were renamed using our standard convention: performer_archive_objecttype_description_year.jpg. 

### Documentation and Metadata

The collection has produced a significant amount of metadata that has been tracked, documented and applied in accordance with a group-developed Metadata Application Profile (MAP). The MAP ensures that users cataloging items in the collection know what information to include and how to format it, resulting in consistent description across all items. The consistency supports clarity, browsability and reproducibility, while ensuring the collection remains usable and accessible to its intended audience. The guidelines also ensure that all metadata meets CollectionBuilder’s data entry and formatting standards so the site can function properly. For reference, the CollectionBuilder documentation on CSV metadata and metadata formatting was used to inform and maintain these standards. Users can access the metadata via the “” section on our collection website.

### Storage and Backup

Our data is shared via a jekyll-built CollectionBuilder website hosted by GitHub Pages. We are making available the digital objects, including the JPG/JPEG image file of the object and the metadata, which contain citations from the source GLAMs. 
Others may want to reuse our data to conduct historical research into American Vaudeville; personal, academic, or other reasons must fall in accordance with copyright and within licensed use which is explicitly stated within the metadata fields. 
Our data is going to be additionally archived in a Google Drive in accordance with the next subsection.

### Data Sharing

Our data is shared via a jekyll-built CollectionBuilder website hosted by GitHub Pages. We are making available the digital objects, including the JPG/JPEG image file of the object and the metadata, which contain citations from the source GLAMs. 
Others may want to reuse our data to conduct historical research into American Vaudeville; personal, academic, or other reasons must fall in accordance with copyright and within licensed use which is explicitly stated within the metadata fields. 
Our data is going to be additionally archived in a Google Drive. For editing access to the Google Drive, please reach out to the admin attached to the Drive.

### Period of Data Retention

During Fall 2025, all components are actively maintained across three storage tiers. The metadata spreadsheet is continuously updated with weekly GitHub syncs. Quality reviews identify and correct errors.
The GitHub repository will likely remain accessible indefinitely as CollectionBuilder's static architecture requires no ongoing maintenance. If GitHub discontinues free hosting, any member can fork the repository or migrate to alternative platforms. If UO accounts are deactivated, the Project Manager will coordinate transfer to personal accounts 30 days in advance. If team members become unavailable, documented procedures in Google Drive enable continuity.

### Licensing and Ethical Issues

The photos and artwork we used were from public collections that we cited and we made sure to include all the information provided to us from the original collections. We included a rights statement for protection. The images we chose are public domain. The photos we included are not culturally insensitive and do not include Indigenous communities, enslaved people, children, patients or institutionalized individuals. The only concern is that these images will be taken out of context as they are images of female and male impersonators. This is the risk when posting in public collections. These are public domain images so they do risk being used as images of marginalized people without community involvement or the use of sensitive historical photographs in marketing.

### Appendix 

#### Data Dictionary

The data dictionary, created and agreed upon by group consensus, followed standards from both Collection Builder and other authorities, such as TGN (Thesaurus of Geographic Names) and RightsStatements.org. Our naming standards conform to the guidelines set by these authorities to ensure consistency. Each field in the dictionary specifies which authority it refers to. The only field that employed a pick list was the subject field since the nature of this field was very project-specific.

|Field Name|normalized_field_name|Definition|Example|
|----------|---------------------|----------|-------|
|Object ID|objectid|As defined by Collection Builder documentation and standards, the field that CollectionBuilder uses to identify each object. Please do not include the file format.|bertsavoy_cbm_memorial_1923|
|Filename | filename|This field will be the digital object’s filename, including the file extension, or a full URL to a file hosted externally to your project.|img101_b6_photographs_01.jpg|
|Title|title|A title is a word or phrase that names or designates something, such as a book, artwork, document, or piece of media.|Bert Savoy - Calla Lillies|
|Creator|creator|As defined by CollectionBuilder documentation, “the creator property designates an entity primarily responsible for making the resource” (CollectionBuilder Documentation)|Charles Demouth|
|Date|date|The date indicates a point of time associated with the object.|1927, 1927-03-26, 1927-03|
|Description|description|“An account of the object” per CollectionBuilder Documentation and DublinCore standards, either generated by Collection Managers or as defined by the source.|Postcard of the Memorial Gymnasium on the University of Idaho campus in Moscow, Idaho.|
|Subject|subject|A term or phrase that describes the topic or content of a resource, often used to support discovery, classification, and retrieval.|Karyl Norman; Bert Savoy; Vesta Tilley|
|Location|location|This field designates a geographic location to which the item is tied.|New York (United States); Hollywood (California United States); Cincinnati (Ohio United States); Unknown|
|Source|source|The source field designates a related source collection or resource from which the object is derived.|PG 5, University of Idaho Library Special Collections and Archives|
|Identifier|identifier|The identifier field is used to preserve the unique identifier assigned to the object by the object’s (usually physical) source collection. https://collectionbuilder.github.io/cb-docs/docs/metadata/csv_metadata/|ASC.2012.53|
|Type|type|An object’s type distinguishes between types of image, sound, text, etc., using a one- or two-value input.|Image;Still Image|
|Format|format|As defined by CollectionBuilder documentation, format “indicates the object’s media type” (CollectionBuilder Documentation).|image/jpeg|
|Language|language|As defined by the Dublin Core standard, A language of the intellectual content of the resource. i.e., if there is language content available, what language is it?|english|
|Rights|rights|The rights field should include a free-text rights statement describing information about rights held in and over the object.|Educational use includes non-commercial use of text and images in materials for teaching and research purposes. Digital reproduction rights granted by the University of Idaho Library. For other uses beyond free use, please contact the University of Idaho Library Special Collections and Archives Department.|
|Rights Statement|rightsstatement|This field is a standardized rights statement, designated in the form of a URI.|http://rightsstatements.org/vocab/InC/1.0/ |
|Display Template|display_template|As defined by CollectionBuilder documentation, display_template is “used for the Item page and is used in logic to choose representations in other pages” (CollectionBuilder Documentation).|image|
|Alternative Text|image_alt_text|A brief description of the object. This is used by machine reading for visually impaired users. Additionally, if an object does not load, it will display the alt. text instead.|A series of illustrations of Julian Eltinge by Winsor M’Cay. The piece is titled, “Winsor M’Cay draws impressions of Mr. Julian Eltinge at Orpheum”. |
|Cataloguer|cataloguer|The first name of the Collection Manager who catalogued the object.|Calista|
|Citation|citation|A MLA citation of digital object from the source.|Billy Rose Theatre Division, The New York Public Library. "Bothwell Browne" The New York Public Library Digital Collections. 1850 - 2020. https://digitalcollections.nypl.org/items/86257580-ff5d-012f-7e78-58d385a7bc34|

#### Additional Documention

[Metadata Application Profile](https://github.com/LIBDSCI350m-Fall25/group1/blob/main/objects/metadata-application-profile.docx.pdf)

[File Naming Scheme](https://github.com/LIBDSCI350m-Fall25/group1/blob/main/objects/file%20naming%20convention.pdf)