---
title: Digitization Resources
nav: Resources
description: 
topics: Equipment Recommendations; Student Links
---

<!-- go back and look at evan's template for some links to other sites using this template to see how they might differ -->

# For Community Members

Information for community members or researchers conducting their own digitization work.

## Equipment Recommendations

### Scanners

The type of scanner  you need depends on the types of items you plan to scan. The CDIL recommends using a flatbed scanner to digitize your items as any type of feed scanner has potential to damage delicate photos and documents.

Look for a scanner with a bed size that will fit the largest of the items you'll be scanning. 8 1/2" x 11" will typically work unless you have many oversized items. If you are scanning slides and film, opt for a scanner with a built-in transparency unit. For high-quality scans, you'll need a scanner capable of at least 600 dpi.

### External Hard Drive

Consider purchasing an external hard drive to store your scans if you'll be creating many high resolution TIFF files. This will prevent your computer storage from filling up. It will also protect your files and make them easily transportable. 

Opt for an external hard drive with 1 terabyte or greater of storage if you're conducting a large scanning project. This should provide plenty of space for all your photos and documents.

## Scanning Specifications

In the CDIL we have very specific technical requirements to create archival quality scans. Your process may differ depending on your needs:

- **DPI**: DPI, or dots per inch, measures the resolution of a digital scan. We scan images at 600 dpi and documents at 400 dpi. 
- **Pixels**: we scan all items at 6,000 pixels on the longest edge of the item.
- **File type**: we scan all images to .tiff format and all documents to .jpeg. Visit the [Adobe website](https://www.adobe.com/creativecloud/file-types/image/comparison/jpeg-vs-tiff.html) to read more about TIFF vs JPEG files.

## Processing Your Images

After digitizing your items, there rae a few different things you can do to process and build your collection:

- **Photoshop**: the CDIL uses Adobe Photoshop to process the digital files from our scanning projects. Visit the [Processing](https://kitstokes.github.io/digi-proc/content/1-processing.html) page for a guide to these procedures.
- **GIMP**: if you don't have access to Photoshop, [GIMP](https://www.gimp.org/) is a free image editing software with similar functions.
- **Metadata**: you may want to create some metadata to describe your images. Visit the [Metadata](https://kitstokes.github.io/digi-proc/content/2-metadata.html) page to see some common metadata fields the CDIL uses to describe collections. We recommend using [Google Sheets](https://docs.google.com/spreadsheets/u/0/) to create your metadata. 

# For Student Workers

Links for students working in the CDIL:

#### Reference

- [University of Idaho Digital Initiatives Home](https://www.lib.uidaho.edu/digital/)
- [Center for Digital Inquiry and Learning Home](https://cdil.lib.uidaho.edu/)
- [Getty Art & Architecture Thesaurus](https://www.getty.edu/research/tools/vocabularies/aat)
- [Dublin Core Metadata Practices](https://en.wikipedia.org/wiki/Dublin_Core) 

#### Administrative

- [VandalWeb](https://vandalweb.uidaho.edu/PROD/twbkwbis.P_GenMenu?name=payroll)

## Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to simplify writing content for the web. 
Markdown can be used any where on GitHub and in Jekyll.

- [Mastering Markdown GitHub Guide](https://guides.github.com/features/mastering-markdown/){:target="_blank" rel="noopener"}
- [GitHub Markdown documentation](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax){:target="_blank" rel="noopener"}
- [Markdown in a Minute](https://evanwill.github.io/_drafts/notes/markdown-minute.html)

## Bootstrap 5

[Bootstrap](https://getbootstrap.com/) is a CSS framework designed to streamline developing user interfaces for your website.

[Bootstrap Icons](https://icons.getbootstrap.com/) are SVG-based icon set used to add graphics to your content.

## YAML

[YAML](http://www.yaml.org/) is a human readable plain text data format.
It is used in Jekyll for configuration, site data, and front matter.
Jekyll projects are [configured](https://jekyllrb.com/docs/configuration/) using the "_config.yml" file.

## Liquid

[Liquid](http://shopify.github.io/liquid/) is a flexible template language.
[In Jekyll]((https://jekyllrb.com/docs/liquid/) it allows you to layout pages built from modular components and data, using the "_includes", "_layouts", and "_data" directories.
Liquid includes features such as operators, loops, and filters to manipulate raw content. 
Liquid statements are enclosed by {% raw %}`{%  %}`{% endraw %} and variables in {% raw %}`{{  }}`{% endraw %}.

## Sass  

[Sass](http://sass-lang.com/) is a CSS extension / preprocessor. 
All normal CSS is valid SCSS, but Sass adds many powerful functions and programmatic features. 
Writing SCSS is often easier and more sensible, for example by supporting nesting, variables, and operators. 
Jekyll lets you write SASS in modular chucks called partials, in the "_sass" directory, that will be combined and compiled into normal CSS files when the site is built.
