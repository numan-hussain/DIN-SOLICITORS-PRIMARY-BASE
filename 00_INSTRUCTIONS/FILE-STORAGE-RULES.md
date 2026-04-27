# File Storage Rules

Use GitHub for lightweight project memory.

Use Dropbox/local storage for large files.

## Store in GitHub

- Markdown files
- Briefs
- Notes
- Campaign copy
- SEO plans
- Website code
- Templates
- Asset registers
- Lightweight CSV files
- Small text exports

## Do Not Store Large Media in GitHub by Default

Keep these in Dropbox/local folders:

- Images
- Videos
- Audio files
- Photoshop, Illustrator or design source files
- ZIP files
- Large PDFs
- Raw exports

## Default Project Storage

Every campaign, task, export or piece of work should have its own folder:

`02_PROJECTS/YYYY-MM-DD_project-name/`

Large files should be placed locally in:

`02_PROJECTS/YYYY-MM-DD_project-name/06_ASSETS/`

or:

`02_PROJECTS/YYYY-MM-DD_project-name/08_FINAL/`

These large files are ignored by GitHub using `.gitignore`.

## Asset Register

For each project with images, videos or large files, create an asset register in GitHub:

`02_PROJECTS/YYYY-MM-DD_project-name/07_REPORTS/ASSET-REGISTER.md`

Track:

- File name
- Local path
- Dropbox path or shared link
- Purpose
- Source
- Licence or consent status
- Notes

## Rule for Codex

When creating or exporting large files:

1. Save the actual file in the project folder locally or Dropbox.
2. Do not commit large media to GitHub by default.
3. Add a note in the asset register so future chats can understand where the file is.
4. Only commit large files to GitHub if Numan explicitly asks and the file size is suitable.
