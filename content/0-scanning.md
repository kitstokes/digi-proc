---
title: Scanning Procedures
nav: Scanning
topics: Scanning Specs; Lab Equipment
---

This is a scanning guide for anyone conducting digitization work in the Center for Digital Inquiry and Learning (CDIL) lab.

Contents:

1. [Why do we scan?](#why)
2. [File naming](#file)
3. [Scanning images](#images)
4. [Scanning documents](#documents)
5. [Lab equipment](#scanners)

{% capture text %}
1. Ensure that hands are clean and dry before handling any materials.
2. Wear cotton gloves when necessary (ask CDIL staff if unsure).
3. Handle items with extreme care.
4. Give you full attention to the scanning process.
{% endcapture %}
{% include card.html text=text header="Before You Scan" %}

-------------

{:#why}
## Why do we scan?

Scanning materials with a flatbed, large format, or feed scanner is often the safest and most effective way to preserve an item's information. Creating digital copies of items also allows us to make them available to patrons using the internet. 

Scanning items at a high resolution allows us to use them in different ways without manipulating the items themselves. For this reason, we aim for a minimum **600 dpi** image when scanning. This size specification provides a scalable file that we can then use for large or small reprints while maintaining the original details of the item.

---

{:#file}
## File Naming

Every scanned item needs a file name. A standardized file naming system helps us know exactly where an item belongs. Name scanned files using the following standardized naming rules:

**collectionabbreviation_box#_envelope/folder#-item#subitem**
{:.text-center}

- Collection abbreviation refers to an abbreviated version of either Manuscript Group (mg) or Photograph Group (pg).
- All information needed to name items should be found on the item and the folder, envelope, or box that it comes in.
- When in doubt about how to name an item, talk to CDIL staff.

**File name examples**:

Manuscript Group 190, box 4, folder 2, letter 1, with multiple pages becomes: `mg190_b4_f2-001p001; mg190_b4_f2-002p002; etc`.

Photograph Group 3, box 1, photograph 3 becomes: `pg3_b1-003`.

---

{% capture text %}
1. Go to your personal folder in the **Scans** folder on the C: drive at your workstation.
2. If CDIL staff has not done so already, create a folder for the scanning project titled after the collection you're scanning (e.g. MG 190).
3. Inside that folder, create another folder called **tiff**. This will be the destination for your initial scans. 
{% endcapture %}
{% include card.html text=text header="Prepare Your Workstation" %}

{:#images}
# Scanning Images

**Step 1:** Turn on scanner at station. 

**Step 2:** Open EpsonScan scanning software from the shortcut on the desktop.

**Step 3:** Place the item along the left side of the scanning bed (the glass plate). Leave a slight border between the item and the edge of the glass. 

**Step 4:** Position the color separation guide so that the saturated bar is beside the item you're scanning. Leave a 1/8" gap between the guide and the item.

**Step 5:** Close the scanner lid and press **Preview** in EpsonScan.

**Step 6:** After the preview scan finishes, use the cursor to draw the selection window around the edge of the item. Include as much of the color separation guide as needed to color balance the item:
 
{% include figure.html img="1_preview.jpeg" alt="preview scan image" caption="" width="75%" %}

**Step 7:** In EpsonScan, set **Resolution** to 600 dpi and set the length of the longest edge of the item to at least 6,000 pixels. Refer to the image below. If other settings on your screen do not match this image, ask CDIL staff before scanning:

{% include figure.html img="2.jpeg" alt="Scan settings" caption="" width="50%" %}

**Step 8:** After settings are correct, press **Scan**.

**Step 9:** In the **File Save Settings** window, you need to:
- Click **Other** and then **Browse** to select the folder you want your images to save to. This should be the folder labeled **tiff** in the main project folder.
- Enter the file name prefix. This should be the file name you created **minus the subitem number**, which the **Start Number** field will replace. See [File Naming](#file) for complete details. 
- **Start Number** should be set at **01** if you're starting a new project. If you're continuing a project, it should be set to the next sequential number. 
- Set **Image Format** file type to **TIFF (*.tif)**:

{% include figure.html img="3.jpeg" alt="File Save Settings" caption="" width="75%" %}

**Step 10:** Press **OK** and the scan will begin.

<!-- need to figure out how to get numbers to not reset to "1" after each image is included -->

{:#documents}
# Scanning Documents

Document scans have different technical requirements from images. In the CDIL, we:

- Scan all documents at 400 dpi.
- Scan all documents straight to JPEG format.

When conducting a documents-only scanning project, you will only need to create a **lowres jpeg** folder as the destination for your scans. Scan all documents in the project directly to this folder. 

Follow all other directions for scanning an image, including the [file naming conventions](#file). Use the color separation guide unless working with the feed scanner. 

---

{%- assign scanners = site.data.equipment -%}

{:#scanners}
# Lab Equipment

This section is an overview of the scanning equipment we use in the CDIL. 

<table class="table">
<tbody>
{% for s in scanners %}
<tr>
<td class="col-4"><img src="{{ s.image | prepend: '/images/' | relative_url }}" alt="image of {{ s.image }}" class="img-fluid"/></td>
<td class="col-8">{{ s.text }}</td>
</tr>
{% endfor %}
</tbody>
</table>