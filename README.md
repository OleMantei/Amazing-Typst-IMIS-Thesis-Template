The formatting might appear slightly off or unpolished in some areas. This template aims to replicate the Word template as closely as possible. The original sizes were inconsistent in places.

## ✒️ Fonts

This template requires the fonts "**Calibri**" and "**Times New Roman**". Ensure that both fonts are installed on your system. If they are not available, you can find the font files in the program folders of Microsoft Word in .ttf format.

- **On Mac OS**: Right-click on the Microsoft Word application in the Applications folder and select "Show Package Contents". The font files are typically located in the folder: "/Applications/Microsoft Word.app/Contents/Resources/DFonts/". Once you have located the font files, please copy and install them.

## 📖 Bibliography

Typst currently does not support multiple bibliographies natively. This template uses a workaround with the "alexandria" addon.

### How It Works

- **Main Bibliography:**  
  All references must be prefixed with `x-` to be included in the bibliography.  
  _Example:_ `@x-nielsenHeuristicEvaluationUser1990`

- **Categorized Groups:**  
  To automatically group sources, use these additional prefixes in your citation keys:
  - **Online-Quellen:** Prefix with `ON`  
    _Example:_ `@x-ONinstitutfurmultimedialeundinteraktivesystemeIMISInstitutFur`
  - **Software:** Prefix with `SO`
  - **Normen:** Prefix with `NO`

The template will display the main bibliography along with these extra groups if references with the corresponding prefixes are present.

**Note:** Check future Typst releases for native support of multiple bibliographies and remove this workaround if implemented.

Version: typst 0.13.0
