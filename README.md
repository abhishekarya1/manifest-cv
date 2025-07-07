This is my resume template made in LaTeX. Based on [Jake's Resume](https://www.overleaf.com/latex/templates/jakes-resume/syzfjbzwjncs) and modified using Windsurf AI, also inspired by [this](https://www.overleaf.com/latex/templates/jakes-resume-anonymous/cstpnrbkhndn) a little.

## Build
Install [MiKTeX](https://miktex.org/) for `latexmk` to be available.

To compile Latex and generate PDF, run:
```bash
$ latexmk -pdf jakes-resume.tex
```

To clear all temp files (including PDF), run:
```bash
$ latexmk -C jakes-resume.tex
```

## Compatibility
To check for compatibility, do "select all plain text check" by opening in Chrome, Edge, and Adobe Acrobat.

Then use this to verify proper parsing - https://www.open-resume.com/resume-parser

## Processing
- Compress PDF
- Remove certain PDF Metadata (e.g. name of compress site)

## Storing and Versioning
Stored in Google Drive - https://drive.google.com/drive/u/0/folders/1BwnE5gdTmD0scHC3n4S_91aenfW2iOts

Version History - `More actions -> File information -> Manage versions` (helps maintain a single static shared link)

## Known Issues
Spaces not copied in plain text check - don't use the SourceSansPro font! Issues happens in Edge, and not in Chrome so better avoid it.

## License
[MIT License](/LICENSE)
