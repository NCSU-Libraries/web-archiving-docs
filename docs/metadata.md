# Seed Metadata
Each seed in the collection should be assigned metadata as it is added to the collection. There are default metadata fields provided by Archive-It. More information on how Archive-It manages metadata and their recommendations for metadata management can be found at [https://support.archive-it.org/hc/en-us/articles/208332603-Add-edit-and-manage-your-metadata](https://support.archive-it.org/hc/en-us/articles/208332603-Add-edit-and-manage-your-metadata).

In addition to the default metadata fields provided by Archive-It, you can also create custom metadata fields. In our NC State University Websites Collection we have created custom metadata fields to record when a seed url is being redirected to from an old url or when an old seed url is redirecting to a new seed url. Currently, all metadata that is added to seeds is publicly viewable from the collection and seed level views found at [https://archive-it.org/home/ncsu-libraries](https://archive-it.org/home/ncsu-libraries).


The follow is an example of the metadata fields that we are using for our **NC State University Websites Collection**. Fields will need to be added and removed as found appropriate for other collections.

- URL - The full and valid URL for the site as it is represented in Archive-It  
- Language - The primary language of the website.
- Creator - The creator of the website.
- Collector - 'NCSU Libraries'
- Title - The website title as it appears in the title meta tag in the website source.
- Publisher - The creator of the website.
- Description - A full description of the website.
- Redirecting To - The URL that the seed is now redirecting to, if the redirection is permanent.
- Redirecting From - The URL that redirected to this seed, if the redirect is permanent.
- Format - 'Web'
- Subject - The primary subject of the website.

*****

## Updating metadata
### Adding or Updating Individual Seed Metadata
The ability to create metadata for a seed happens only after the seed url is added to the collection ([See Adding new seeds to a Collection](https://ncsu-libraries.github.io/web-archiving-docs/seeds/#adding-new-seeds-to-a-collection)).

**You can complete individual seed metadata updates by following these steps:**

1) Open the Archive-It admin panel

2) Click on the collection that contains the seed you wish to add metadata for

3) Find the individual seed you wish to update and click on that url to open the seed settings panel

4) Click on the Metadata tab

5) Click Edit

6) Fill out each metadata field with the correct metadata, click 'add' after filling out each individual
field

7) Once all of the fields have been updated, click 'done'

### Bulk Metadata Updates
Archive-It allows you to upload bulk metadata for all of your seeds. This is very useful if you have recently added a lot of new seeds to a collection, or if there is a new metadata field that you wish to add to all of the seeds in an existing collection. To learn more about bulk seed metadata importing and exporting can be found at [https://support.archive-it.org/hc/en-us/articles/208012996-Upload-and-download-metadata](https://support.archive-it.org/hc/en-us/articles/208012996-Upload-and-download-metadata).

It is important to note the difference between adding to existing metadata values and overwriting current metadata. You would use the 'add to existing metadata values' option if you were adding a new metadata field to every seed in your collection. You would use the 'overwrite existing seed metadata values' option if you were updating multiple seeds with metadata for the first time or if you had edited metadata extensively from an export (cleaning up exiting metadata).

Seeds must exist in Archive-It before they will appear in the exported sheet. That means you must first [add all new seed urls](https://ncsu-libraries.github.io/web-archiving-docs/seeds/#adding-new-seeds-to-a-collection) that you wish to create metadata for before exporting the .ods file that you will add the metadata to.

**You can complete a bulk metadata updates by following these steps:**

 1) Navigate to the collection overview page for the collection that you added the new seeds to.

 2) Click on the Metadata tab

 3) Click on the Bulk Seed Metadata tab

 4) Click Download Existing Seed Metadata, make a duplicate of this file and store it somewhere safe. The file has an .ods extension. It can be opened by Microsoft Excel in Windows. If you are using a Mac it must be opened using [OpenOffice Spreadsheets](http://www.openoffice.org/)

 5) Add content to the metadata fields for each seed that you have added or wish to edit the metadata for

 6) Return to the Bulk Seed Metadata tab in Archive-It

 7) Export a second (backup) copy of the existing metadata, label the file with the current date and mark it clearly as backup and put it into Google Drive.

 7) Select 'Overwrite Existing Seed Metadata' and click upload

 8) Upload the .ods file that you modified with new metadata for the new seeds

 9) Confirm you wish to overwrite the existing metadata and review the preview to ensure the new metadata reflects your changes

 10) Save the new changes
