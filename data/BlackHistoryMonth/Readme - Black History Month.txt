README - Metadata subsets from the British Library

====================================================================================================

GENERAL INFORMATION ABOUT THE DATASETS

The British Library 'Black History Month' dataset  dataset is a set of .csv (comma separated value) files containing metadata for resources from the British National Bibliography (BNB) and our British Library collections, relating to the history of the African diaspora. It was initially released to coincide with the 2016 'Black History Month', and has been updated annually thereafter.

There are 5 files; each provides a different view of the data. Each record in a .csv file contains the identifier (BL record ID) for the full metadata record held in the British Library's online catalogues. The online catalogues can be accessed at http://bnb.bl.uk (BNB), and http://explore.bl.uk (published items).

====================================================================================================

CSV FILES

records.csv.
A list of all resources. Includes: BL record ID, Type of resource, Content type, Material type, BNB number, ISBN, Name, Dates associated with name, Type of name, Role, All names, Title, Variant titles, Series title, Number within series, Country of publication, Place of publication, Publisher, Date of publication, Edition, Physical description, Dewey classification, BL shelfmark, Topics, Genre, Languages, Notes.
Note: we have used the column heading 'Name' rather than 'Author' to reflect the fact that the names associated with a resource may be editors, artists, etc.

names.csv.
A list of all names (including authors and editors, personal names and organisations) associated with the resources. Includes: Name, Dates associated with name, Type of name, Role, Other names, BL record ID, Type of resource, Content type, Material type, BNB number, ISBN, Title, Variant titles, Series title, Number within series, Country of publication, Place of publication, Publisher, Date of publication, Edition, Physical description, Dewey classification, BL shelfmark, Topics, Genre, Languages, Notes.
Note: when a resource is associated with multiple names, each name appears as a separate entry within this file.

titles.csv.
A list of all titles (such as main titles, standardised titles, and variant titles) associated with the resources. Includes: Title, Other titles, BL record ID, Type of resource, Content type, Material type, BNB number, ISBN, Name, Dates associated with name, Type of name, Role, All names, Series title, Number within series, Country of publication, Place of publication, Publisher, Date of publication, Edition, Physical description, Dewey classification, BL shelfmark, Topics, Genre, Languages, Notes.
Note: when a resource has multiple titles, each title appears as a separate entry within this file.

topics.csv.
A list of all topical/subject terms (including general terms, geographical terms, personal names, meetings/conferences and organisations) associated with the resources. Includes: Topic, Type of topic, BL record ID, Type of resource, Content type, Material type, BNB number, ISBN, Name, Dates associated with name, Type of name, Role, All names, Title, Variant titles, Series title, Number within series, Country of publication, Place of publication, Publisher, Date of publication, Edition, Physical description, Dewey classification, BL shelfmark, Genre, Languages, Notes.
Note: when a resource has multiple topical terms, each term appears as a separate entry within this file.

classification.csv.
A list of all Dewey classification numbers associated with the resources. Includes: Dewey classification, BL record ID, Type of resource, Content type, Material type, BNB number, ISBN, Name, Dates associated with name, Type of name, Role, All names, Title, Variant titles, Series title, Number within series, Country of publication, Place of publication, Publisher, Date of publication, Edition, Physical description, BL shelfmark, Topics, Genre, Languages, Notes.
Note: when a resource has multiple Dewey classification numbers, each classification appears as a separate entry within this file.

====================================================================================================

FORMAT OF THE DATA

Header row: The first row is a header row containing the name of the value e.g. 'Place of publication'.

Repeating values: Some cells may contain repeats of values separated with a delimiter e.g. 'London ; New York' in Place of publication. The two places are separated with the delimiter ';'.

Multiple facets: Some cells may contain multiple facets separated with a delimiter e.g. 'Civil rights--History' in Topics, where the sub-facet is separated with the delimiter '--'.

====================================================================================================

SUPPORTING INFORMATION

Import issues: BL record IDs begin with at least one 0 (zero). Some import utilities may strip these leading zeros. If you wish to open the files in Excel, for example, you will need to set the data format to 'Text' when importing the file.

Character set issues: The raw bibliographic metadata is held in a library character set format, MARC8. We have exported the csv files as UTF-8 but, depending on which utility you use to import or analyse the data, there may be some instances where there are character set problems. These may be circumvented if Unicode UTF-8 is an import option for the data format. For instance, if you wish to open the files in Excel, you will need to import the files as 'data from text', and specify the character encoding as UTF-8; if you open the files in Excel without following this import procedure, it is likely that letters with diacritics and other special characters will not display properly.

Data cleaning: Cataloguing rules and procedures have changed over time so there may be some variations in the detail of each entry. Some cleaning of the data has been carried out to remove unnecessary punctuation from the entries; however, given the varying nature of the original catalogue records there may be some instances where this has not been successful. In many cases these examples will be obvious because they will occur at the beginning of the table, prior to the beginning of the alphabetical listing.

Information about the Dewey classification system can be found at http://en.wikipedia.org/wiki/List_of_Dewey_Decimal_classes.

Information about importing CSV data into Microsoft Excel can be found at https://support.office.com/en-ZA/article/import-data-using-the-text-import-wizard-40c6d5e6-41b0-4575-a54e-967bbe63a048.

For further information or to comment, please contact metadata@bl.uk.