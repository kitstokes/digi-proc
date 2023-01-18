---
title: Scanning
nav: Scanning
topics: Scanning Specs; Lab Equipment
---

This is a scanning guide for anyone conducting digitization work in the Center for Digital Inquiry and Learning (CDIL) lab.

Contents:

1. Why do we scan?
2. File naming
3. Scanning images
4. Scanning documents
5. Lab equipment

{% capture text %}
1. Ensure that hands are clean and dry before handling any materials.
2. Wear cotton gloves when necessary (ask CDIL staff if unsure).
3. Handle items with extreme care.
4. Give you full attention to the scanning process.
{% endcapture %}
{% include card.html text=text header="Before You Scan" %}

<!-- turn the above setup overview card into a "Before You Scan" card -->

-------------

# Why do we scan?

Scanning materials with a flatbed, large format, or feed scanner is often the safest and most effective way to preserve an item's information. Creating digital copies of items also allows us to make them available to patrons using the internet. 

Scanning items at a high resolution allows us to use them in different ways without manipulating the items themselves. For this reason, we aim for a minimum **600 dpi** image when scanning. This size specification provides a scalable file that we can then use for large or small reprints while maintaining the original details of the item.

## File Naming

Every scanned item needs a file name. A standardized file naming system helps us know exactly where an item belongs. Name scanned files using the following standardized naming rules:

**collectionabbreviation_box#_envelope/folder#-item#subitem**

- Collection abbreviation refers to an abbreviated version of either Manuscript Group (mg) or Photograph Group (pg).
- All information needed to name items should be found on the item and the folder, envelope, or box that it comes in.
- When in doubt about how to name an item, talk to CDIL staff.

**File name examples**:

Manuscript Group 190, box 4, folder 2, letter 1, with multiple pages becomes `mg190_b4_f2-001p001; mg190_b4_f2-002p002; etc`.

Photograph Group 3, box 1, photograph 3 becomes `pg3_b1-003`.

### Prepare Your Workstation:
1. Go to your personal folder in the **Scans** folder on the C: drive at your workstation.
2. If CDIL staff has not done so already, create a folder for the scanning project titled after the collection you're scanning (e.g. MG 190).
3. Inside that folder, create another folder called **tiff**. This will be the destination for your initial scans. 

## Scanning Images



### Install Text Editor

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/), Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for managing Jekyll projects.

Open-source cross platform suggestions:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)

Tip: you can click `.` on any GitHub repository to [open the web editor](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor) (which is a light version of VS Code)!
