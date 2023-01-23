---
title: Processing Files
nav: Processing
---

This section contains instructions on how to process files once a project is fully scanned.

{% capture text %}**Before you begin**:
Go to the folder for this scanning project. Check for two folders labeled **access jpeg** and **lowres jpeg**. Create the folders if they do not exist. {% endcapture %}
{% include alert.html text=text color=secondary %}

Contents:

1. [Processing Images](#images)
2. [Processing Documents](#documents)
3. [Apply OCR](#ocr)
4. [Reduce File Size](#reduce)
5. [Create Photoshop Actions](#actions)

## Process Images

There are two main steps to processing your image scans:

1. Convert files from TIFF to JPEG
2. Crop and convert files to low resolution JPEGs

### Convert Files from TIFF to JPEG

1. Open Photoshop. Go to **File** > **Automoate** > **Batch**.

* insert photo

2. Select the action **tiff>jpeg**. If you do not have this action on your machine, ask CDIL staff for assistance. 

3. Change the settings in the **Batch** window to the following:

- **Action**: select the **tiff>jpeg** action.
- **Source**: select the **tiff** folder for the project. 
- **Destination**: select the **access jpeg** folder for the project. 

* insert photo

4. Click **OK**. Wait for Photoshop to complete the action.

5. Check that the files saved to the correct folder. 

### Crop and Convert Files to Low Resolution JPEGs:

#### Crop

1. Go to the **access jpeg** folder. 

2. Open the first image in Photoshop. 

3. Crop out the color bar. Crop th eimage as close to the edges of the item as possible while getting rid of the entire background.

4. If needed, balance images using the Levels tool in Photoshop.

5. Save and close the image when finished.

6. Complte steps 1-5 until all files have been cropped. Then, convert files to low resolution JPEGs.

#### Convert

1. In photoshop, open the **Batch** window and change the settings to the following:

- **Action**: select the **lowresjpeg** action.
- **Source**: select the **access jpeg** folder for the project.
- **Destination**: select the **lowres jpeg** folder for the project.

2. Click **OK**. Wait for Photoshop to complete the action.

3. Check that the files saved to the correct folder. 

## Process Documents

There are two main steps to processing your document scans:

1. Convert JPEG scans to PDF using Adobe Acrobat
2. Combine multiple PDF files to create one document

### Convert JPEG scans to PDF Using Adobe Acrobat

1. Open the **lowres jpeg** folder for the scanning project.

2. Select the item(s) you would like to convert.

3. Right-click the selected item(s). From the context menu choose one of the following:

- **Convert to Adobe PDF** if converting only one file. 
- **Combine supported files in Acrobat** if converting files that need to be combined into one (like a multi-page letter or document).

* insert image

4. Click **Combine** in the window that appears.

5. Wait for Acrobat to open your files.

6. Find **Tools** in the top-right corner of the screen. Click **Recognize Text** and then **In this file**. 

* insert image

7. Wait for Acrobat to complete the command. If working with a multi-page document, you will know it is finished when it ends back at the first page.

8. Save the document as a PDF following the naming rules established in the [File Naming] section. 

## GitHub Pages 

One amazingly useful GitHub feature is [GitHub Pages](https://guides.github.com/features/pages/).
It provides free static web hosting from any repository.
Gh-pages is intended to host relatively simple sites for your GitHub portfolio, project, or documentation.
Because it is free and a valuable transferable skill, this is a great option for teaching and learning.

Many organizations are using GitHub to collaboratively create and publish public workshop websites. 
For example: 

- [Programming Historian](http://programminghistorian.org/)
- [Software Carpentry](https://software-carpentry.org/), [Data Carpentry](http://www.datacarpentry.org/), [Library Carpentry](https://librarycarpentry.org/)
- this site!

{% capture text %}Note:
There are *soft* limits and guidelines for gh-pages usage: sites should be < 1GB, use < 100GB bandwidth per month, and make < 10 builds per hour.
If your site exceeds these quotas, GitHub will send you a notice asking you to modify the repository.
All content must follow the [community guidelines](https://help.github.com/articles/github-community-guidelines/), e.g. no violence, obscene sex, or illegal stuff.{% endcapture %}
{% include alert.html text=text color=secondary %}
