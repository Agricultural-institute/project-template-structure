## 💡 Project structure

This is a structured template repository designed specifically for research projects. It provides a well-organized framework that can be used as a starting point for any new research project. The template includes directories for analyses, documents, images, manuscripts, measurements, etc., each with its own set of relevant subdirectories and files. The use of emojis provides a visual guide to the type of content in each file, making it easy to navigate and understand the project structure. By using this template, you can ensure a consistent and efficient organization of research project, thereby facilitating better collaboration and understanding among team members.

To use this project template, follow these steps:

1. Navigate to the [releases](https://github.com/Agricultural-institute/project-template-structure/releases) page of this repository.
2. Select the most recent release.
3. Look for the `project_template.zip` file in the assets section of the release.
4. Click on `project_template.zip` to download the file.

Once downloaded, you can unzip the file to access the project template.

### General structure

```
📚 project_template
│
├── 📖 project_description.txt                
│
├── 📂 processing
│   ├── 📂 Pix4D
│   │   ├── 📂 YY_MM_DD_LOC
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
│       ├── 📄 administration.docx
│       ├── 📄 fun_facts.docx
│       └── 📊 ...
│
├── 📂 images
│   ├── 📂 multispectral 
│   │   ├── 📂 YY_MM_DD_LOC
│   │   │   ├── 🖼️ image_1.tif
│   │   │   └── 🖼️ ...
│   │   └── 📂 ...
│   └── 📂 hyperspectral 
│       ├── 📂 YY_MM_DD_LOC
│       │    ├── 📂 radiance
│       │    │   └── 🖼️ image_1.hdr
│       │    ├── 🖼️ image_1.hdr
│       │    └── 🖼️ ...
│       └── 📂 ...
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

> **Note:** In the directory `YY_MM_DD_LOC` is a placeholder where:
>
> - `YY` stands for the two-digit year of the experiment.
> - `MM` stands for the two-digit month of the experiment.
> - `DD` stands for the two-digit day of the experiment.
> - `LOC` stands for the location of the experiment.
>
> For example, a directory named `22_03_15_FieldA` would represent an experiment conducted on March 15, 2022, at location 'FieldA'.
