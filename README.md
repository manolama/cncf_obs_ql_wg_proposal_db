# Observability Query Language Proposal Dataset

This repo is a proposed format for capturing data pertaining to the 
[CNCF Observability TAG Query Standardization work group](https://docs.google.com/document/d/1JRQ4hoLtvWl6NqBu_RN8T7tFaFY5jkzdzsB9H-V370A)

## Goals

The primary aim is to create a data set that is easy to edit, understand and share.
YAML files in a GIT repo like this allows for easy editing and modification attribution.
The repo can also hold front-end code to create a GitHub site with search and 
display capabilities.

## Layout

### dsl_survey

Contains subdirectories for each existing query language with details about the
language and grammar. Additional languages and fields can be added over time.

### telemetry_models

This is a collection of various observability data types along with implementations
for OpenTelemetry as well as other systems. These models inform the various query
languages and in choosing a standard we need to account for the various models.

### use_cases

These are various use cases for observability data. A unified language should account
for all common use cases and as many uncommon cases as possible.

## YAML

YAML is a nice format for a GIT repo in that it has a structure, has wide programmatic
support, and allows for multi-line fields that we can use for verbose descriptions
containing Markdown for display purposes.