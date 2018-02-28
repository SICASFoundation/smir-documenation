---
title: Genomics Data
taxonomy:
    category: docs
---

Genomic data is accepted in the MINiML format. The upload separate xml files for **Platform GPL**, **Series GSE** and the tabular **Sample GSM**.  The data can be linked to each other using **Related data**.

## Genomic Platform

### General meta data

| Term                   | Data entry | Editable | Data type     |
| ---------------------- | ---------- | -------- | ------------- |
| SMIR ID                | automatic  | no       | Number        |
| Type                   | automatic  | no       | List          |
| Date added             | automatic  | no       | Date & Time   |
| File format				 |automatic	 | no | text |
| Number of Files & Size | automatic  | no       | Number        |
| Description            | manual     | yes      | Text          |
| Anatomical region      | manual     | yes      | Ontology list |

### Platform meta data

| Term                  | Data entry | Editable | Data type |
| --------------------- | ---------- | -------- | --------- |
| IID                   | automatic  | No       | Text      |
| Title                 | automatic  | No       | Text      |
| Distribution          | automatic  | No       | Text      |
| Technology            | automatic  | No       | Number    |
| Manufacturer          | automatic  | No       | Text      |
| Manufacturer protocol | automatic  | No       | Text      |

## Genomic Series

### General meta data

| Term                   | Data entry | Editable | Data type     |
| ---------------------- | ---------- | -------- | ------------- |
| SMIR ID                | automatic  | no       | Number        |
| Type                   | automatic  | no       | List          |
| Date added             | automatic  | no       | Date & Time   |
| File format				 |automatic	 | no | text |
| Number of Files & Size | automatic  | no       | Number        |
| Description            | manual     | yes      | Text          |
| Anatomical region      | manual     | yes      | Ontology list |

### Series meta data

| Term               | Data entry | Editable | Data type |
| ------------------ | ---------- | -------- | --------- |
| IID                | automatic  | No       | Text      |
| Title              | automatic  | No       | Text      |
| Summary        | automatic  | No       | Text      |
| Type      | automatic  | No       | Number    |
| Overall design | automatic  | No       | Text      |
| Referenced samples | automatic  | No       | Text      |


## Genomic Sample

### General meta data

| Term                   | Data entry | Editable | Data type     |
| ---------------------- | ---------- | -------- | ------------- |
| SMIR ID                | automatic  | no       | Number        |
| Type                   | automatic  | no       | List          |
| Date added             | automatic  | no       | Date & Time   |
| File format				 |automatic	 | no | text |
| Number of Files & Size | automatic  | no       | Number        |
| Description            | manual     | yes      | Text          |
| Anatomical region      | manual     | yes      | Ontology list |

### Sample meta data

| Term               | Data entry | Editable | Data type |
| ------------------ | ---------- | -------- | --------- |
| IID                | automatic  | No       | Text      |
| Title              | automatic  | No       | Text      |
| Description        | automatic  | No       | Text      |
| Channel count      | automatic  | No       | Number    |
| Data processing    | automatic  | No       | Text      |
| Supllementary data | automatic  | No       | Text      |




###  Supported file types

- [MINiML](https://docs.smir.ch/basics/supported%20standards/miniml.html)