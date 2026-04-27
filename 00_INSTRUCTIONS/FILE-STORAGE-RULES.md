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

## Default Activity Storage

Each activity should still have its own folder:

`DIN-ACTIVITIES/YYYY-MM-DD_activity-name/`

Large files should be placed locally in:

`DIN-ACTIVITIES/YYYY-MM-DD_activity-name/01_RESOURCES/`

or:

`DIN-ACTIVITIES/YYYY-MM-DD_activity-name/03_EXPORTS/`

These large files are ignored by GitHub using `.gitignore`.

## Asset Register

For each activity with images, videos or large files, create an asset register in GitHub:

`DIN-ACTIVITIES/YYYY-MM-DD_activity-name/05_NOTES/ASSET-REGISTER.md`

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

1. Save the actual file in the activity folder locally or Dropbox.
2. Do not commit large media to GitHub by default.
3. Add a note in the asset register so future chats can understand where the file is.
4. Only commit large files to GitHub if Numan explicitly asks and the file size is suitable.

