# Changelog
All notable changes to the `pdfrender` package since the 
2023-12-04 will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
this project uses date-based 'snapshot' version identifiers.

## [2023-12-07]
Version v1.8

### Fixed

 - \PdfRender@PatchColorSetGroup -> \PdfRender@ColorSetGroupHook, issue #3

## [2023-12-04]

Version v1.7

### Changed
 - moved from oberdiek package to own repository
 - use LaTeX cmd hooks to patch \normalcolor and \color@setgroup
