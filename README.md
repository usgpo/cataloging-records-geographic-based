# CGP Geographic-Based

## General Information
Library Services & Content Management (LSCM) of the U.S. Government Publishing Office created this repository. Metadata and Collection Services (MCS), formerly Library Technical Services (LTS), creates and maintains the collections in the repository.
This repository contains sets of bibliographic records in the Catalog of U.S. Government Publications (CGP) based on geographic coverage and governmental jurisdictions and reports about the records. The records have been extracted using a list of MARC metadata elements. Our intention is to provide a new product for Federal depository libraries to develop and manage their collections and the GPO records in their catalogs and systems.

We selected a group of MARC fields and subfields to identify records that are related to a particular state or entity. We use the full names, abbreviations, and adjectival forms of the names as the match points.

- [Geographic Area Code (043)](https://www.loc.gov/marc/bibliographic/bd043.html)
  - Please see the [MARC Code List for Geographic Areas](https://www.loc.gov/marc/geoareas/)
- [Main Entry - Corporate Name (110)](https://www.loc.gov/marc/bibliographic/bd110.html)
- [Main Entry - Meeting Name (111)](https://www.loc.gov/marc/bibliographic/bd111.html)
- [Title Statement (245 $a and $b)](https://www.loc.gov/marc/bibliographic/bd245.html)
- [Varying Form of Title (246 $a and $b)](https://www.loc.gov/marc/bibliographic/bd246.html)
- [Name of Publisher, Distributor, etc. (260 $b)](https://www.loc.gov/marc/bibliographic/bd260.html)
- [Name of Producer, Publisher, Distributor, Manufacturer (264 $b)](https://www.loc.gov/marc/bibliographic/bd264.html)
- [Note Fields (5XXs)](https://www.loc.gov/marc/bibliographic/bd5xx.html)
- [Subject Added Entry - Corporate Name (610)](https://www.loc.gov/marc/bibliographic/bd610.html)
- [Subject Added Entry - Meeting Name (611)](https://www.loc.gov/marc/bibliographic/bd611.html)
- [Subject Added Entry - Topical Term, Geographic Subdivision (650 $z)](https://www.loc.gov/marc/bibliographic/bd650.html)
- [Subject Added Entry - Geographic Name (651)](https://www.loc.gov/marc/bibliographic/bd651.html)
- [Added Entry - Corporate name (710)](https://www.loc.gov/marc/bibliographic/bd710.html)
- [Added Entry - Meeting Name (711)](https://www.loc.gov/marc/bibliographic/bd711.html)

The reports are in the form of tab-separated values spreadsheets. They include several different types of metadata, such as:

- Match points
  - MARC field names and tags
- Major metadata elements
  - Titles
  - CGP system numbers
  - OCLC numbers
  - Record types
    - Names and MARC codes
  - Record formats
    - Names and MARC codes
  - Agency names
    - Up to three per record
  - SuDoc numbers
    - Up to three per record
  - Item numbers
    - Up to three per record
  - Publication dates
  - PURLs
    - Up to three per record
  - Publications URLs
    - Up to three per record
- Collection development and management elements
  - SuDoc agency classes
    - Up to three per record
  - Shipping list numbers
  - Online equivalent records
    - True or False
  - OCLC numbers of the online equivalent records

We are testing this process with one state in each [National Collection Service Area (NCSA)](https://www.fdlp.gov/about-the-fdlp/national-collection-service-areas):

- Alaska (West)
- Ohio (Midwest)
- Pennsylvania (Northeast)
- Texas (South)

We plan to create record sets for all states and entitites and to combine the files for the states and entities in each NCSA into individual collections.

## Collections List

| **State** | **NCSA** | **No. of Records** | **Last Update** | **Record Formats** | **Cataloging Dates** |
| :----- | :----- | :----- | :----- | :----- | :----- |
| Alaska | West | 13,053 | 8/2024 | All | All |
| Ohio | Midwest | 8,865 | 8/2024 | All | All |
| Pennsylvania | Northeast | 8,246 | 8/2024 | All | All |
| Texas | South | 11,047 | 8/2024 | All | All |

## Other LSCM Repositories  

LSCM develops and maintains other repositories:

- [All CGP Records (MARC UTF-8)](https://github.com/usgpo/cataloging-records-all-cgp-utf8)
- [All CGP Records (MARC XML)](https://github.com/usgpo/cataloging-records-all-cgp-marcxml)
- [CGP Records Maintenance Files](https://github.com/usgpo/cataloging-records-CGP-maintenance-files)
- [CGP on GitHub](https://github.com/usgpo/cataloging-records)
- [U.S. Congressional Serial Set Project (MARC UTF-8)](https://github.com/usgpo/cataloging-records-serial-set-utf8)
- [U.S. Congressional Serial Set Project (MARC XML)](https://github.com/usgpo/cataloging-records-serial-set-marcxml)

## Repository History and Versions

GitHub uses a versioning system to provide access to the iterations of a repository. This enables a user to return to the state of a repository before the various changes ("commits" in GitHub terminology) that were made to it.

**To see a list of versions of the repository as a whole, follow these steps:**

- Click or tap on "commits" in the top right-hand section of the page
  - ![Image shows pointer to 'commits' link in upper right-hand of main file list](images/commit_history_link.png)
- On the "Commits" page, choose the date of the version to be retrieved and then click or tap the "Browse the repository at this point in the history" link.
  - ![Image shows pointer to "Browse the repository at this point in the history" link](images/browse_history_link.png)
- The resources in the repository on that date will be available for viewing  and downloading.

**To see a list of versions of a particular collection, follow these steps:**

- Click or tap on the name of a collection in the Collections List.
- Click or tap on "History" in the top right-hand corner of the collection page.
  - ![Image shows the "History" link on ](images/collections_history_link.png)
- On the "History" page, choose the date of the version to be retrieved.
- Click or tap on the "Browse the repository at this point in the history" icon.
  - ![Image shows pointer to "Browse the repository at this point in the history" link](images/browse_historical_collections.png)
- The main page of the repository on that date will be displayed.
- The resources in the repository on that date will be available for viewing and downloading.

## Feedback and Questions

For questions and feedback about the repositories, collections, and resources, please submit inquiries via [askGPO](https://ask.gpo.gov/s/). Select the Federal Depository Library tile and then the Cataloging/Metadata (Policy and Records) category.
