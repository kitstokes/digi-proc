---
title: Processing Files
nav: Processing
topics: Processing Images and Docs; Text Recognition; Actions
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

{:#images}
# Processing Images

---

There are two main steps to processing your image scans:

1. Convert files from TIFF to JPEG
2. Crop and convert files to low resolution JPEGs

### Convert Files from TIFF to JPEG

**Step 1:** Open Photoshop. Go to **File** > **Automoate** > **Batch**.

{% include figure.html img="processing_1.jpeg" alt="Open Batch Window" caption="" width="50%" %}

**Step 2:** Select the action **tiff>jpeg**. If you do not have this action on your machine, ask CDIL staff for assistance. 

**Step 3:** Change the settings in the **Batch** window to the following:

- **Action**: select the **tiff>jpeg** action.
- **Source**: select the **tiff** folder for the project. 
- **Destination**: select the **access jpeg** folder for the project. 

{% include figure.html img="processing_2.jpeg" alt="Batch Window" caption="" width="80%" %}

**Step 4:** Click **OK**. Wait for Photoshop to complete the action.

**Step 5:** Check that the files saved to the correct folder. 

### Crop and Convert Files to Low Resolution JPEGs:

#### Crop

**Step 1:** Go to the **access jpeg** folder. 

**Step 2:** Open the first image in Photoshop. 

**Step 3:** Crop out the color bar. Crop the image as close to the edges of the item as possible while getting rid of the entire background.

**Step 4:** If needed, balance images using the **Levels** tool in Photoshop.

**Step 5:** Save and close the image when finished.

**Step 6:** Complete steps 1-5 until all files have been cropped. Then, convert files to low resolution JPEGs.

#### Convert

**Step 1:** In Photoshop, open the **Batch** window and change the settings to the following:

- **Action**: select the **lowresjpeg** action.
- **Source**: select the **access jpeg** folder for the project.
- **Destination**: select the **lowres jpeg** folder for the project.

{% include figure.html img="processing_3.jpeg" alt="Batch Window" caption="" width="80%" %}

**Step 2:** Click **OK**. Wait for Photoshop to complete the action.

**Step 3:** Check that the files saved to the correct folder. 

{:#documents}
# Processing Documents

---

### Convert JPEG scans to PDF Using Adobe Acrobat

**Step 1:** Open the **lowres jpeg** folder for the scanning project.

**Step 2:** Select the item(s) you would like to convert.

**Step 3:** Right-click the selected item(s). Choose one of the following from the context menu:

- **Convert to Adobe PDF** if converting only one file. 
- **Combine supported files in Acrobat** if converting files that need to be combined into one (like a multi-page letter or document).

{% include figure.html img="processing_4.jpeg" alt="Convert or Combine Files" caption="" width="50%" %}

**Step 4:** Click **Combine** in the window that appears.

**Step 5:** Wait for Acrobat to open your files.

**Step 6:** Find **Tools** in the top-right corner of the screen. Click **Recognize Text** and then **In this file**. 

{% include figure.html img="processing_5.jpeg" alt="Recognize Text" caption="" width="75%" %}

**Step 7:** Wait for Acrobat to complete the command. If working with a multi-page document, you will know it is finished when it ends back at the first page.

**Step 8:** Save the document as a PDF following the naming rules established in the [Scanning](https://kitstokes.github.io/digi-proc/content/0-scanning.html) section. 

{:#ocr}
## Text Recognition with Adobe Acrobat Pro DC OCR

Optical Character Recognition (OCR) is a technology that recognizes text in documents and images to make them machine readable. Using Adobe Acrobat Pro DC, you can extract text through OCR on single or multiple documents with just a few clicks. 

### OCR on a Single Document

Follow these steps to extract text through OCR on one document.

**Step 1:** Open a PDF in Adobe Acrobat Pro DC.

**Step 2:** Select **Scan & OCR** from the tool menu on the right side of the application window.

{% include figure.html img="processing_6.jpeg" alt="Scan & OCR" caption="" width="30%" %}

**Step 3:** Select **Recognize Text** from the toolbar at the top of the screen. Choose **In This File** from the dropdown menu.

{% include figure.html img="processing_7.jpeg" alt="Recognize Text" caption="" width="80%" %}

**Step 4:** In the **Recognize Text** window, check that the settings are correct:

- **Document Language**: language in which the document is written. Most documents you work with in the CDIL will be in English (US).
- **Output**: set to **Searchable Image**.
- **Downsample To**: set to **300 dpi**.

{% include figure.html img="processing_8.jpeg" alt="Recognize Text Settings" caption="" width="75%" %}

{:#reduce}

### Batch OCR on Multiple Documents

Follow these steps to extract text through OCR on multiple documents at one time.

**Step 1:** Open Adobe Acrobat Pro DC. Click the **Tools** menu in the top-left corner.

{% include figure.html img="processing_9.jpeg" alt="Tools Menu" caption="" width="50%" %}

**Step 2:** Click **Scan & OCR** in the **Create & Edit** tool group.

**Step 3:** Click **Or recognize text in multiple files** under the blue Start button.

{% include figure.html img="processing_10.jpeg" alt="Multiple Files" caption="" width="50%" %}

**Step 4:** Click **Add Files...** to manually add files or drag and drop files into the window.

{% include figure.html img="processing_11.jpeg" alt="Add Files" caption="" width="50%" %}

**Step 5:** Output options:

- **Target folder**: choose to save the items to the same folder as the originals or to save them to a new folder. 
- **File naming**: choose to keep the same file name or input a text or number string before or after the original name. 

{% include figure.html img="processing_12.jpeg" alt="Output Options" caption="" width="50%" %}

**Step 6:** Click **OK**. Check the **General Settings** dialog box that opens. Set PDFs to **300 dpi** to avoid file size issues later.

**Step 7:** Click **OK** to start the OCR process.

## Batch Reduce File Size

Follow these steps to reduce the file size of many PDFs at once using Adobe Acrobat Pro DC.

**Step 1:** In Acrobat, open the **File** menu and select **File** > **Save As Other** > **Reduce Size PDF**.

{% include figure.html img="processing_13.jpeg" alt="Reduce Size PDF" caption="" width="50%" %}

**Step 2:** In the **Arrange documents** dialog box, add files by selecting **Add Files...** or drag and drop files into the window. Click **OK**.

{% include figure.html img="processing_14.jpeg" alt="Arrange Documents" caption="" width="50%" %}

**Step 3:** In the next window, choose **Retain existing** for the compatibility options and click **OK**.

**Step 4:** Output options:

- **Target folder**: choose to save the items to the same folder as the originals or to save them to a new folder.
- **File naming**: choose to kep the same file name or input a text or number string before or after the original name.

{% include figure.html img="processing_15.jpeg" alt="Output Options" caption="" width="50%" %}

**Step 5:** Click **OK** to begin the process.


{:#actions}
## Creating Batch Actions in Photoshop

Follow these steps to learn how to make the two Photoshop actions required for the CDIL digitization process.

### Action: tiff > access jpeg

{% capture text %}**Before you begin**:
Open Photoshop. Is the **Action Window** visible? Make sure by selecting the **Window** menu at the top of the screen and clicking **Actions**.{% endcapture %}
{% include alert.html text=text color=secondary %}

**Step 1:** Open one of the tiff files from your scanning project in Photoshop.

**Step 2:** In the **Action Window**, click on the **Create New Action** button. It is a small square with a plus sign.

{% include figure.html img="processing_18.jpeg" alt="Create New Action" caption="" width="50%" %}

**Step 3:** In the **New Action** window, set the name of the new action to **tiff > jpeg**.

{% include figure.html img="processing_20.jpeg" alt="tiff > jpeg" caption="" width="50%" %}

**Step 4:** Click **Record**.

**Step 5:** In the **File** menu, select **Save As...** Navigate to the **access jpeg** folder for your scanning project. 

**Step 6:** Choose **JPEG** from the **Save as** type drop down menu. Click **Save**.

**Step 7:** In the **JPEG Options** window change the **Quality** value to 10 and click **OK**.

{% include figure.html img="processing_23.jpeg" alt="JPEG Options" caption="" width="50%" %}

**Step 8:** Select **Close** from the **File** menu or use Ctrl + W.

**Step 9:** Click the square **Stop** icon in the Action Window.

{% include figure.html img="processing_25.jpeg" alt="Stop Action Record" caption="" width="50%" %}

### Action: access jpeg > lowres jpeg

{% capture text %}**Before you begin**:
Open Photoshop. Is the **Action Window** visible? Make sure by selecting the **Window** menu at the top of the screen and clicking **Actions**.{% endcapture %}
{% include alert.html text=text color=secondary %}

**Step 1:** Open one of the **access jpeg** files from your scanning project.

**Step 2:** In the **Action Window**, click on the **Create New Action** button. It is a small square with a plus sign.

{% include figure.html img="processing_18.jpeg" alt="Create New Action" caption="" width="50%" %}

**Step 3:** In the **New Action** window, set the name of the new action to **lowres jpeg**.

{% include figure.html img="processing_26.jpeg" alt="Lowres JPEG Action" caption="" width="50%" %}

**Step 4:** Press **Record**.

**Step 5:** In the **File** menu select **Save As...** Navigate to the **lowres jpeg** folder for your scanning project. 

**Step 6:** Choose **JPEG** from the **Save as** type drop down menu. Click **Save**.

**Step 7:** In the **JPEG Options** window change the **Quality** value to 8 and click **OK**.

{% include figure.html img="processing_18.jpeg" alt="Create New Action" caption="" width="50%" %}

**Step 8:** Select **Close** from the **File** menu or use Ctrl + W.

**Step 9:** Click the square **Stop** icon in the Action Window to stop the recording.

{% include figure.html img="processing_25.jpeg" alt="Stop Recording" caption="" width="50%" %}


<!-- all content added!
- look for consistency in wording and format
- check double check triple check spelling errors -->
