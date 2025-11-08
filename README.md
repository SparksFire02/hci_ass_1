# HCI Theory And Methods Assignment 1

### Gitlab Use
Ensure you have editing access before commencing. Always create a pull request to merge to `master`.

At least one person should review your updates.

## First Time Installation Instructions
### TeX Installation
For windows, you may use **MikKTeX**. For macOS, you may use **MacTeX**.

For the IDE, you can use anything that supports preview. For example, **TeXstudio** would work.

### Clone Repo
Clone this repo. Always create a feature branch before making any changes.

### Packages
All packages have been written within the .tex file when building the first time. Accept when required.

## Configuration
> Assumes a TeXstudio IDE

Go to:
1. Options
2. Configure TeXstudio
3. Build

Under Default Compiler, use **xelatex**.

Compile the document (Build & View) to test if everything is running.

The file in reference is called `sigconf-main.tex`.

## Issues
### Class acmart not found
Ensure acmart.cls is in the same folder as the .tex file.

### File ACM-Reference-Format.bst not found
Ensure that file is also in the same folder.

### Missing Bibliography
Go to
1. Tools
2. Bibliography

That should build it using the bib file.

This bib file is `main-base.bib`.