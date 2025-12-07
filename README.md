# ELEC-E8740 - Basics of Sensor Fusion D LaTeX Template

This is a clean LaTeX template for assignments in ELEC-E8740 - Basics of Sensor Fusion D course.

## Files Included

- `main.tex` - Main document file
- `fphw.cls` - Document class file
- `logo_aalto.pdf` - Aalto University logo
- `references.bib` - Bibliography file

## Changes from Original Template

This template has been modified from the original ELEC-E8130 template:
- Removed "Final Group Project Report" section
- Removed "Report guidelines" section  
- Removed contribution announcement and final report instructions
- Updated course information to ELEC-E8740 - Basics of Sensor Fusion D
- Simplified structure with basic sections (Introduction, Methodology, Results, Conclusion)

## How to Use

1. Update the following information in `main.tex`:
   - `\title{}` - Your assignment title
   - `\author{}` - Your name
   - `\date{}` - Due date or submission date
   - `\professor{}` - Professor's name

2. Add your content in the respective sections

3. Compile the document using pdflatex and bibtex:
   ```
   pdflatex main.tex
   bibtex main
   pdflatex main.tex
   pdflatex main.tex
   ```

## Recommended Platform

You can use Overleaf (https://www.overleaf.com) with Aalto's free Professional account.
Upload all files to a new Overleaf project to get started.
