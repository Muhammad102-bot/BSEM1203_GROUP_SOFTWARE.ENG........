# BSEM1203_GROUP_SOFTWARE.ENG........
FINAL PROJECT
# Document Archive Asset Package

This repository contains the extracted and decompressed source components of an Office Open XML Document. The file structure has been unpacked into its native XML components, styles, themes, and embedded media assets for version control, development tracking, or programmatic document generation.

## 📂 Project Structure

The project is organized according to the Open Packaging Conventions (OPC) layout:

```text
├── [Content_Types].xml          # Content type definitions for all parts in the package
├── _rels/                       # Global package-level relationships
│   └── .rels
└── word/                        # Main document workspace folder
    ├── document.xml             # Main text content and layout structure
    ├── _rels/                   # Folder-level relationship files
    │   └── document.xml.rels
    ├── header1.xml              # Header layout and recurring text element
    ├── footnotes.xml            # Document footnotes
    ├── endnotes.xml             # Document endnotes
    ├── theme/                   # System/Office presentation styling
    │   └── theme1.xml
    └── media/                   # Embedded image database
        ├── image1.png
        ├── image2.png
        ├── image3.png
        ├── image4.png
        ├── image5.png
        ├── image6.png
        ├── image7.png
        ├── image8.png
        ├── image9.png
        ├── image10.png
        ├── image11.png
        ├── image12.png
        ├── image13.png
        ├── image14.png
        ├── image15.png
        ├── image16.jpeg
        └── image17.jpeg
