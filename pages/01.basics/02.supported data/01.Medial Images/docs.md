---
title: Medical Images
taxonomy:
    category: docs
---



Medical images of a larged variety of modalities can be stored on SMIR and are refered to as **RAW Image** on SMIR.

### General meta data

| Term                   | Data entry                               | Editable | Data type     |
| ---------------------- | ---------------------------------------- | -------- | ------------- |
| SMIR ID                | automatic                                | no       | Number        |
| Type                   | automatic                                | no       | List          |
| Date added             | automatic                                | no       | Date & Time   |
| File format				 |automatic	 | no | text |
| Number of Files & Size | automatic                                | no       | Number        |
| Anatomical region      | manual                                   | yes      | Ontology list |
| Age                    | DICOM (converted from birthday) / manual | yes      | Number        |
| Height                 | DICOM / manual                           | yes      | Number        |
| Weight                 | DICOM / manual                           | yes      | Number        |
| Gender                 | DICOM / manual                           | yes      | List          |
| Modality               | DICOM / manual                           | yes      | List          |
| Description            | DICOM / manual                           | yes      | Text          |
| Dominance              | manual                                   | yes      | List          |


### Image meta data

| Term                 | Data entry | Editable | Data type |
| -------------------- | ---------- | -------- | --------- |
| Space between slices | DICOM      | no       | Number    |
| Peak kilovoltage     | DICOM      | no       | Number    |
| Slice thickness      | DICOM      | no       | Number    |

### Visualisation

The image data can not be viewed directly in the web interface. However, SMIR generates up to 10 preview images evenly distribute through the series which are generated from the slices of the stack. 

### Supported file types

- [DICOM](https://docs.smir.ch/basics/supported%20standards/dicom.html)
- [Nifiti (uncompressed)](https://docs.smir.ch/basics/supported%20standards/nifti.html)
- [MetaData](https://docs.smir.ch/basics/supported%20standards/metaimage.html)
- [Analyze](https://docs.smir.ch/basics/supported%20standards/analyze.html)



