# GEN-BioDORA Metadata Schema

This repository contains the working metadata schema for GEN-BioDORA, developed as an ISA-inspired framework for describing omics workflows and related metadata in a structured and reusable way.

## Purpose

The schema is being developed iteratively through expert feedback and practical testing.  
This repository is used to:

- maintain the working schema in a versioned environment
- track changes across feedback rounds
- document open questions and design decisions
- provide structured exports for review and reuse

## Repository structure

- `schema/` — working schema files, including the Excel workbook and CSV exports per sheet
- `feedback/` — notes from feedback rounds and a decision log
- `docs/` — supporting documentation such as governance or conventions

## Current workflow

1. The schema is maintained in Excel as the primary editing format.
2. Clean versions of relevant sheets are exported to CSV.
3. Feedback is discussed and implemented in Git branches.
4. Changes are reviewed and merged through pull requests.

## Notes

- The Excel workbook remains the main working file.
- CSV exports are included to improve transparency and version comparison.
- Discussion text and informal comments should not remain inside schema tables, but should be moved to feedback notes or issues.

## Status

Work in progress. The schema is under active development and subject to revision.
