---
title: Objects
taxonomy:
    category: docs
---


Data sets are represented as **Objects** on SMIR. Each object has a unique ID, a set of meta data and object permission. The object's ID is static. This allows you to link permanently to an object. Additionaly, SMIR offers to create a [Digital object identifier](https://www.doi.org/) (DOI). Please read the [DOI section](#doi) for details and instructions.

**Link template**

`https://www.smir.ch/Objects/ID`

**Example for ID 101597**

`https://www.smir.ch/Objects/101597`

 

There are different *object types* to represent the type of the data set. Example *object types* are:

- RAW Image like CT scan, MR Images, etc..
- Segementation of Images
- Surface models
- Genetic data

For a complete list check the [technical documentation section](http://smir-docs.readthedocs.io/en/latest/filetypes/).



## Object names

SMIR uses a template to replace filenames after upload. This helps to identify what type of data the object represents by just looking at the name. It also removes identification information stored in the original (local) filename. The original filename is stored but only displayed to the *owner* of the object.

### Naming template

**Template**  `Namespace.Anatomy.Age.Gender.Modality.ID.Filenumber.Extension`

**Example** `SMIR.Right_scapula.56.M.OT.167141.000.stl`

-  Namespace: SMIR
-  Anatomy: Right scapula
-  Age: 56
-  Gender: male
-  Modality: Other Type (OT)
-  ID: 167141
-  Extension: STereoLithography (stl)

## Meta Data

### General meta data



###  Type specific meta data

## Export meta data

MMeta data of an object can be exported on the detail page. Available formats:

- SMIR API (json)

- Dublin core (xml)

  ![smir-export-meta-data](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-export-meta-data.png)

## DOI

##  Object permissions

### Permission sets

### Default permission

## Owner change

Ech object has exactly one owner. But the owner can change (transfer) the ownership of the object(s).

- Owner change does not affect existing permissions!
- You will lose control over the selected objects!
### Single object

1. Open the Object's menu ![smir-object-menu](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-object-menu.png) 

2. Select `Change Owner` ![smir-owner2](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-owner2.png)

3. Search the new Owner and confirm the change in the modal to finish the process

   ![smir-owner3](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-owner3.png)

### Batch change

1. Select multiple object using the checkboxes. 
2. Select `Owner` in the the `Manage selected` drop-down menu

![smir-owner1](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-owner1.png)

3. Search the new Owner and confirm the change in the modal to finish the process

![smir-owner3](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-owner3.png)

## License

The license specifies the rights the user has after download whereas object permissions define the access to the file on SMIR.

A license is set for each object. *Copyright* is set as default. Please consider changing it when you prepare the object for publishing. The license file will be included in the download. A list of open source license are available. If you need a custom license please use the [ticket system](https://tickets.smir.ch) to send such a request.

### Change license of a single object

The user can change the license in a object list view or on the object's detail page.

1. Login
2. Navigate to the object
3. Click on the menu icon ![smir-object-menu](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-object-menu.png)(list view)
4. Select `Edit license`
5. Select the license from the drop-down menu in the modal 
   ![smir-license-modal](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-license-modal.png) 
6. `Set license` to change  or `cancel`  to abort


### Batch license change

1. Login
2. Select the object and click on `Manage selected` and then `License`
   ![smir-batch-license1](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-batch-license1.png)
3. Select the license from the drop-down menu in the modal
   ![smir-batch-license-modal](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-batch-license-modal.png)
4. `Set license` to change/save or `cancel` to abort

##  Preview Images

SMIR generates for Images and model a set of up to 10 preview images to give a glance at the data set. Preview images are not part of the actual data you download.   

## Files

The actual data is not displayed/accessable on SMIR. To use the data set, download the object. However, the list of included files in an object is displayed. 

## Object download

Download are wrapped in a directory contains the following files and downloaded as compressed archive (zip)

- Data files
- Meta data file: `*.json`
- Readme `README.md`
- SMIR citation as Bibtex: `smir.bib`
- License: `License_*.txt`

## Object lists

### Unpublished data

### Published data

## Browse data