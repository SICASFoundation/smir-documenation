---
title: Clinical Research Forms
taxonomy:
    category: docs
---

Clinical Research Form Data is accepted in CDISC ODM (xml) format. The data is split into **Clinical Study Definition** and **Clinical Study Data** objects



## Study Definition

### General meta data

| Term                   | Data entry | Editable | Data type     |
| ---------------------- | ---------- | -------- | ------------- |
| SMIR ID                | automatic  | no       | Number        |
| Type                   | automatic  | no       | List          |
| Date added             | automatic  | no       | Date & Time   |
| Number of Files & Size | automatic  | no       | Number        |
| File format				 |automatic	 | no | text |
| Description            | manual     | yes      | Text          |
| Anatomical region      | manual     | yes      | Ontology list |

### Study definition meta data

| Term                   | Data entry | Editable | Data type     |
| ---------------------- | ---------- | -------- | ------------- |
| Study OID              | automatic  | no       | Text          |
| Study Name             | automatic  | no       | Text          |
| Study Description      | automatic  | no       | Text          |
| Protocol Name          | automatic  | no       | Text          |
| Meta Data Version OID  | automatic  | no       | Text          |
| Meta Data Version Name | automatic  | no       | Text          |
| Events | automatic | no | Text |
| Events & Forms | automatic | no | Text |

## Study Data

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

### Study data meta data
| Term                   | Data entry | Editable | Data type     |
| ---------------------- | ---------- | -------- | ------------- |
| Subject Key            | automatic  | no       | Text          |


### Study definition meta data
| Term                   | Data entry | Editable | Data type     |
| ---------------------- | ---------- | -------- | ------------- |
| Study Object | automatic | no | Link |
| Study OID              | automatic  | no       | Text          |
| Study Name             | automatic  | no       | Text          |
| Study Description      | automatic  | no       | Text          |
| Protocol Name          | automatic  | no       | Text          |
| Meta Data Version OID  | automatic  | no       | Text          |
| Meta Data Version Name | automatic  | no       | Text          |
| Events | automatic | no | Text |
| Events & Forms | automatic | no | Text |



### Supported file types

- [CDISC-ODM](https://docs.smir.ch/basics/supported%20standards/cdisc-odm.html)