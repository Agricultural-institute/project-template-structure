## 💡 Project structure

This is a structured template repository designed specifically for research projects. It provides a well-organized framework that can be used as a starting point for any new research project. The template includes directories for analyses, documents, images, manuscripts, measurements, etc., each with its own set of relevant subdirectories and files. The use of emojis provides a visual guide to the type of content in each file, making it easy to navigate and understand the project structure. By using this template, you can ensure a consistent and efficient organization of research project, thereby facilitating better collaboration and understanding among team members.

```
📚 project_template
│
├── 📖 project_description.txt                
│
├── 📂 processing
│   ├── 📂 Pix4D
│   │   └── 📂 ...
│   ├── 📂 GIS
│   │   ├── 📂 YY_MM_DD_LOC
│   │   └── 📂 ...
│   └── 📂 scripts
│       ├── 📜 classifications.R
│       ├── 📜 anova.R
│       └── 📜 ...
│
├── 📂 experimental_design
│   ├── 📊 design.xlsx
│   ├── 📊 plant_labels.xlsx
│   ├── 📄 protocols.docx
│   ├── 📄 administration.docx
│   └── 📄 ...
│
├── 📂 documentation
│   ├── 📂 manuscripts
│   │   ├── 📄 manuscript_v1.docx
│   │   ├── 🎨 figures.svg
│   │   └── 📝 draft.txt
│   ├── 📂 meetings
│   │   ├── 📄 resolution_1.docx
│   │   ├── 📄 meeting_notes.docx
│   │   └── 📄 ...
│   └── 📂 miscellaneous
│       ├── 📂 photos
│       │   ├── 🖼️ photo_1.jpg
│       │   └── 🖼️ ...
│       ├── 📄 fun_facts.docx
│       └── 📊 ...
│
├── 📂 images (see: [Specifics](#specifics))
│   ├── 📂 YY_MM_DD_LOC
│   │   ├── 🖼️ image_1.hdr
│   │   └── 🖼️ ...
│   └── 📂 ...
│ 
└── 📂 measurements
   ├── 📂 GPS
   │   ├── 📝 YY_MM_DD_LOC_coordinates_plants.txt
   │   └── 📝 ...
   ├── 📂 LiCor
   │   ├── 📊 YY_MM_DD_LOC_potato_plants.xlsx
   │   └── 📊 ...
   ├── 📂 LAI                
   │   ├── 📊 YY_MM_DD_LOC_maize_plants.xlsx
   │   └── 📊 ...
   └── 📂 ...
 

```

### Specifics

if in the same experiment both hyperspectral and multispectral images are used use this structure for images instead

```
...
├── 📂 images
│   ├── 📂 multispectral
│   │   ├── 📂 YY_MM_DD_LOC
│   │   │   ├── 🖼️ image_1.tif
│   │   │   └── 🖼️ ...
│   │   └── 📂 ...
│   └── 📂 hyperspectral
│       ├── 📂 YY_MM_DD_LOC
│       │    ├── 🖼️ image_1.hdr
│       │    └── 🖼️ ...
│       └── 📂 ...
...
```
