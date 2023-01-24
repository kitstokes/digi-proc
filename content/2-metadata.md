---
title: Metadata
nav: Metadata
topics: Metadata categories
---

This section explains the different formats and guidelines for a typical metadata spreadsheet created in the CDIL. Every scanned collection will eventually have its own metadata sheet.

Metadata describes and give information about other data. The metadata we create for our digital collections records everything we know about the item. 

In the CDIL we use the [Dublin Core Metadata Practices](https://en.wikipedia.org/wiki/Dublin_Core). These guidelines provide a standard for how we format and make our metadata readable for a large audience. 

Read before beginning:
<!-- should this be in a card or a notification? or just like this? should each thing be numbered?-->

Not all of the fields listed below will appear on every metadata spreadsheet. Some spreadsheets will have extra or fewer fields depending on the subject material. Each field serves a purpose for both preservation and access of an item. 

Metadata field title format should be followed exactly as they are written. Titles always need to be lower-case and either one or multiple words as indicated.

The metadata categories in this document are divided into two different guides: one for CDIL student workers and one for CDIL staff. **If you are a student worker**, please only fill in the metadata categories in the student worker section.

Refer to CDIL staff if you have questions about metadata not answered in this document. 


<!-- card code:

{% capture text %}
1. Click the green "Use this template" button on the [workshop-template-b repository](https://github.com/evanwill/workshop-template-b) to make your own new copy of the code (make sure you are logged into GitHub!).
2. Work on the GitHub web interface or clone to your local machine to edit files (tip: click `.` on any GitHub repository to [open the web editor](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor)).
3. Edit the `_config.yml` with your info.
4. Edit/add the content pages in Markdown (found in the "content" folder).
5. Add any images to the "images" folder.
5. Push to GitHub or commit on the web interface.
6. In your repository's settings, activate GitHub Pages, using main branch.{% endcapture %}
{% include card.html header="Overview" text=text %} -->
---

# Metadtata (Students)

#### title

The name of an item. Either the given title of an item or a short, descriptive set of words used to identify it. 

- **Required**.
- Use "sentence case". Only capitalize the first word of the title, unless referring to a proper noun (Dylan Fuller, Empire State Building, Logging camp on the Potlatch River, etc.).
- For questions on how to title photographs in a series, refer to CDIL staff.
- Example value: `Heclia Mine; Students playing baseball`

#### description

A detailed 1-3 sentence account of the item to communicate what it is and its contents.

- **Required**.
- Include small details such as 'mountains can be seen in the background'. 
- Include names of people and places when known.
- Example value: `Students on lawn in front of old Gault Hall. Gault Hall was torn down in 2003 to make room for the current Living Learning Communities.`

#### subject

Subjects allow researchers searching for one thing in particular to narrow collections down to their interests.

- **Required**.
- Keywords that describe or relate to the material.
- Separate entries with a semi-colon but no space.
- Include 2-3 entries when possible, but more are encouraged.
- Use the [Getty Art and Architecture Thesaurus](https://www.getty.edu/research/tools/vocabularies/aat) to locate subject terms. 
- Adhere to the controlled vocabulary list if the collection has one.
- Example values: `children;parades;automobiles;cows (mammals);farming (function);Return to Riverside Festival;`
#### creator

The individual or entity that created the item.

- For articles or publications, this is the author.
- For photographs, this is the photographer or the studio.
- Use Last Name, First Name format.
- For additional names use Last Name, First Name, "Nickname" Middle Name Maiden name.
- Example values: `Riegger, Hal; Barnard Studio`

#### date

Refers to the date the item was created or published.

- Use yyyy-mm-dd format if you know the exact date.
- Use yyyy-mm if you only know the month and year.
- Use yyyy if you only know the year.
- If there is no year included with the item, you may estimate the nearest decade if you know enough information from the content and context of the item. Ask CDIL staff for more information.
- If estimating a date, be sure to fill in 'yes' in the 'date is approximate' cell.
- Example values: `1955-12-08; 1955-12; 1955`

#### date is approximate

Indicates that the date is an estimation and not exact.

- Only enter 'yes' if there is an estimation. Otherwise, leave this cell blank.
- Example value: `yes`

#### location

The geographic location(s) and/or place names associated with the item.

- City, State format.
- Extend this to City, County, State, Country depending on the collection.
- Separate multiple location entries for a single record with a semicolon but no space.
- Example values: `Boise, Idaho;Potlatch, Latah County, Idaho;Jakarta, Indonesia`

#### latitude

A geographic coordinate specifying the north-south position of an item.

- Find latitude and longitude using [Google Maps](maps.google.com) by right-clicking on a point and clicking the coordinates displayed in the top of the menu.
- Paste the coordinates into the field in the metadata sheet.
- Split latitude and longitude values into two separate fields. See 'longitude' below.
- Example value: `46.72762`

#### longitude

A geographic coordinate specifying the east-west position of an item.

- Find latitude and longitude using [Google Maps](maps.google.com) by right-clicking on a point and clicking the coordinates displayed in the top of the menu.
- Paste the coordinates into the field in the metadata sheet.
- Split latitude and longitude values into two separate fields.
- Example value: `-117.-1353`

#### identifier

The unique identifier assigned to the object by the object's physical source collection. This is typically assigned by Special Collections staff. 

- Usually found on the folder or box for the collection.
- Ask CDIL staff if unsure about identifier.
- Example value: `ARG-02-16-1993`

#### format original

Specifies the format of the original physical object.

- Choose a word or phrase that best describes the format. There is no controlled vocabulary for this field.
- Be consistent with items across a single collection.
- Example value: `black-and-white photograph; color photograph; article; scrapbook; newspaper clipping; magazine`

#### format

The digital format of the item.

- **Required**.
- This field tells the viewer what format the uploaded material is. 

Choose from the following options:
- Image: `image/jpeg`
- Document: `application/pde`
- Audio: `audio/mp3`
- Video: `video/mp4`

# Metadata (Staff)

## Style customization [optional]

The file "assets/css/styles.scss" exposes variables that can customize the basic style of website:

- `$top-border` adds a tiny splash of color on the header and footer borders. Try tweaking the color using an [HTML # value](https://www.w3schools.com/colors/colors_picker.asp).
- `$text-color` sets the body text color
- `$link-color` sets link color
- `$base-font-size` sets the body text size
- `$container-max` sets a maximum width for the text body--keeping it narrow can make it easier to read, but gives less screen space!

To use the Bootstrap defaults for *any* of these values, comment out the variable in "styles.scss", using `//` in front of the option's line (e.g. `// $text-color: #111 !default;` ).

To add your own custom CSS, use the file "_sass/_custom.scss".
Any CSS/SASS you add to this file will override the template and Bootstrap classes.

## Add Optional Analytics [optional]

To use Google Analytics, add your analytics id to "_config.yml" in `google-analytics-id:` (if `google-analytics-id` is blank, the GA code will not added).
To use an alternative analytics, paste the code snippet provided by the platform into the file "_includes/template/analytics.html".

The analytics code will only be added when using "production" environment. 
This happens automatically on GitHub Pages. 
To build manually you need to add "JEKYLL_ENV", like: `JEKYLL_ENV=production jekyll build`.
