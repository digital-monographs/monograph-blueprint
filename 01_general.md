# General Remarks

The document provides guidelines for the drafting of manuscripts as well as for their submission for publication using the “Digital Publication” platform for digital publishing (also referenced as “the platform”). Additional instructions that supplement these general guidelines may apply depending on the specific subject area. These instructions have precedence, particularly in the case of conflicting guidelines/uncertainty.

Please draft your manuscript using a standard word processing application (Microsoft Word in particular). You may use your own document or the manuscript template provided.

To ensure smooth digital processing, it is mandatory that all documents be submitted in a uniform format. Therefore, we require the use of standard styles and file formats in your word processing software.

To help you with compilation of your manuscript, we offer the manuscript template. The template is compatible with Word 2007 or higher and contains basic style formats that fulfill our requirements with respect to structure, typography, and layout. To get the newest manuscript template, please send a request to [tnb.admin@uni.lu](mailto:tnb.admin@uni.lu).

## First Draft Submission

When sending your manuscript for the first time, please follow this procedure:

1. Send an email to [tnb.admin@uni.lu](mailto:tnb.admin@uni.lu), stating all appropriate data about the book:
	1. title of the book,
	2. list of authors,
	3. short description (optional),
	4. slug proposal (unique identifier which will appear in the book URL),
	5. list of files sorted by order in which they should appear in the book.
2. Add all relevant files of the manuscript as an attachment to that email. This includes `.docx` files and `.ipynb` files, but also the `assets` folder with all the files used in your submission. This includes all the images, videos, datasets and other files. Be sure to follow the guidelines specified in the Submission Structure section.
3. You will be contacted by someone from the *tnb.admin* team. We ask you to follow their instructions.

:::{note}  
When submitting your manuscript for the first time do not worry that it is not prefect. You will be able to change it to comply with the guidelines and to make sure it looks the way you want it to. The only thing that will be difficult to change is its general structure – how it is divided into separate files and how the files are named. **Before submitting your manuscript please make sure that the file structure and the file names will not change**. Everything else you will be able to modify later.  
:::

## Modifications After First Draft Submission

As a general rule, after the first submission the *tnb.admin* team will provide you with:

* Central storage location of your manuscript,
* Link to a dashboard displaying useful information about your manuscript,
* Link to a digital version of your publication.

From then on, please use the storage location to apply every change you want to make. Changes you make on those files will be reflected in the dashboard and in the digital version of your publication.

:::{important}  
Please make sure that your submission complies with the guidelines. When you think the manuscript is ready for editing, contact [verena.deutsch@degruyter.com](mailto:verena.deutsch@degruyter.com).  
:::

## File Formats

:::{important}   
Manuscripts should be submitted in a `.docx` file format. We also accept chapters written in `.ipynb` files, although the recommended way of including visualizations, charts, diagrams, maps, jupyter notebooks, etc. is by including them in `.docx` files. As an author you are required to upload all the files included in you manuscript to the `assets` folder.  
:::

**Manuscripts should be written and submitted specifically in a `.docx` file format.** This is the default file extension produced by the most common word processing software – Microsoft Word. Other file formats, like `.pages` created in Apple Pages or `.gdoc` saved from Google Doc will not work. In the case of manuscripts written in those unsupported file formats input files should be first transformed to `.docx` in order to submit them to the platform.



| **Role of a file** | **Accepted file format** |
| --- | --- |
| Narrative expression | *docx* |
| Notebooks with code | *ipynb* |

In those files you can include other assets, like images or videos, but you should remember to upload them to the `assets` folder and write a correct reference to those files inside of `.docx` or `.ipynb` file.



| **Role of a file** | **Accepted file format** |
| --- | --- |
| Illustrations | *jpg, jpeg, tiff, png* |
| Video | *mp4* |
| Interactive elements for the digital version | *html* |

The `.html` files included in the `.docx` files can contain references to other files in the `assets` directory, for example `.js` or `.css`.

## Submission Structure

:::{tip}   
Submitting your book as a one file can result in unexpected behaviors. We recommend the authors to split the manuscript into logical parts that reflect an internal structure of a book. For example, each chapter can be its own file.  
:::

As an author, you are required to upload a package of a following structure:

:::{code}

.

├── 01_part_of_book.docx

├── 02_part_of_book.docx

├── 03_part_of_book.docx

└── assets/

 ├── img-filename.jpg

 ├── video-filename.mp4

 └── data-filename.csv

:::

Note that every submission must have:

* parts of the book written in `.docx` or `.ipynb` format and
* all the objects (images, videos, files with data) used in the manuscript in a separate folder called `assets`.

Note that you have some flexibility when it comes to nesting files in the `assets` folder. For example, when writing a long book, it is recommended to divide objects by chapters in which they were referenced.

:::{code}

.

├── 01_chapter_one.docx

├── 02_chapter_two.docx

└── assets/

 ├── chapter_1/

 │ ├── some-descriptive-name.png

 │ └── some-descriptive-name.mp4

 └── chapter_2/

 ├── filename.tiff

 └── filename.mp3

:::

You can also put files in nested directories in the `assets` folder, as well as use your own naming convention. 

:::{code}

.

├── 01_name-of-the-chapter.docx

├── 02_chapter-name.docx

└── assets/

 ├── videos/

 │ └── vid.mp4

 └── images/

 ├── 01_name-of-the-chapter/

 │ └── 01-01_section-name/

 │ └── img_a.png

 └── 02_chapter-name/

 └── img_b.jpg

:::

We recommend that you apply your naming convention consistently across the whole book. All figures and tables which shall be included in the print and PDF version of your book, need to be numbered and named according to their figure caption inside the manuscript (e.g. “Figure 1” or “Chapter01_Fig01”).

## File Naming Conventions

Criteria for file naming:

* File names should not be too long.
* Only `0123456789AaBbCcDdEeFfGgHhIiJjKkLlMmNnOoPpQqRrSsTtUuVvWwXxYyZz _-+.` characters are allowed.
* Assignment should be clear and precise.

You can consider numbering your files with leading zeros for continuous documents, i.e. 01, 02 …09, 10 or 001 … 020 … 130. The main advantage is that your files will be ordered in a way you want. The downside is that with every change in a structure of your book you will have to rename the files and all the references to them.

## Obtaining Usage Rights

Please note that it is the author's responsibility to obtain usage rights to third-party material, such as to text, images or tables. Your De Gruyter contact offers a form for requesting reproduction rights to our authors and editors. When asking copyright holders for reproduction rights, please be specific about the form of publication, i.e. open access digital platform (specify CC license) + open access E-book (specify CC license) + print publication (if applicable).

Neither the publisher nor the developers nor maintainers of the platform will assume any liability for copyright infringement by authors.

To obtain the form, write an email to [verena.deutsch@degruyter.com](mailto:verena.deutsch@degruyter.com).

## Uniform Formatting

As the author, you are responsible for the uniform formatting of your manuscript. If several individuals were involved in drafting a single volume (for example for an anthology), please make sure that all articles have the same format, both in terms of layout, style, and spelling. Please make sure that all signs, numbers, symbols, highlighting, spellings etc. have been used consistently according to the language in the manuscript:

* If the manuscript is in German, orthography should be based on latest edition of Duden or Wahrig.
* If the manuscript is in English, either American or British English may be used, but spelling should be uniform throughout the whole volume. Orthography should follow the respective rules (i.e. Chicago Manual of Style).

If the manuscript is for a book series or a journal, please check in advance if there are special standardization requirements. In the event of uncertainty, consult with the editorial or the series’ or the journal’s editor. Please pay special attention to the uniform formatting of the following elements:

* Punctuation according to the used language:
	+ Quotation marks,
	+ Apostrophe,
	+ Dash: – (Windows: Strg + - (numeric keypad), Mac: Alt + - ),
	+ Hyphen
* Numbers:
	+ Years,
	+ Dates,
	+ Numbers and units

Highlighting in text: i.e. italics 

Uniform spelling: abbreviations (i.e. fig., tab.), foreign words etc.

:::{important}  
Please use a metric system such as the International System of Units (SI). For compound units, Unicode symbols must be used.  
:::

## Please Avoid The Following

* The abbreviations *ibid*, *ebd*., *a.a.O.*, *op. cit.*, *p.* and *pp.* in your citations.
* Referencing pages.
* Indentation with space characters or tabs.
* Highlights and underlines.
* Mismatching or incorrect quotation marks (e.g. ″…‶ instead of correct “…”).



