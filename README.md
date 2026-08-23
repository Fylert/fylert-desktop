# Fylert

**Find hidden document issues before you share.**

Fylert is a lightweight desktop Beta for professionals who want to check Word, Excel and PowerPoint files before sending them.

> This is a public download and feedback repository. The Fylert application source code is not published here.

## What Fylert checks

Fylert performs deeper checks on DOCX, XLSX and PPTX files. Depending on the format, findings may include:

- comments or notes
- unaccepted tracked changes in DOCX
- hidden worksheets in XLSX
- hidden slides and speaker notes in PPTX
- external links
- local or network paths
- selected document metadata

Legacy DOC, XLS and PPT files are identified, but they do not receive the deeper content checks above.

## How it works

1. Choose a folder.
2. Fylert recursively checks supported files on your computer.
3. Review the findings before sharing.

Document checks run locally. Document contents are never uploaded for scanning. Checks are read-only and do not modify the original files.

## Download

- [Download details](https://fylert.com/en/download/)
- [Latest GitHub release](https://github.com/Fylert/fylert-desktop/releases/latest)

### Requirements

- Windows 10 or 11
- Apple Silicon Mac running macOS 12 or later

### macOS Beta notice

The macOS Beta is not notarized by Apple, so macOS may show a security warning. Review the release details and checksum before installing, and only continue if you are comfortable testing an unnotarized Beta.

Apple explains the risks and available controls in [Safely open apps on your Mac](https://support.apple.com/en-us/102445).

## Privacy

The full, current privacy behavior is documented in the [Fylert Privacy notice](https://fylert.com/en/privacy/). The app's request payloads do not include file names, file paths, document contents, specific scan results, user IDs, or device IDs.

## Feedback and issues

Use [GitHub Issues](https://github.com/Fylert/fylert-desktop/issues) for reproducible product feedback. Please include the app version, operating system, file format, check name, and expected behavior when relevant.

Do not upload sensitive documents, document contents, private file names, or internal paths to a public Issue. Use a synthetic sample if a file is necessary to reproduce a problem.

For a possible security vulnerability, follow [SECURITY.md](SECURITY.md) instead of opening a public Issue.

## Repository scope

GitHub may automatically attach “Source code” archives to a release. Those archives contain only files tracked in this public repository; they do not contain the Fylert application source code.

Website: https://fylert.com/en/
  
