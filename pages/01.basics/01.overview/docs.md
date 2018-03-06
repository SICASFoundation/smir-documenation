---
title: Overview
taxonomy:
    category: docs
---

 ![smir logo](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-logo-90dpi.png)



## First look

You can [browse](https://www.smir.ch/Home/Browse) SMIR without registration or use the [demo](https://www.smir.ch/Account/LogOnDemo) instance of SMIR.



## Quick start

### Concepts

- Users are registered to **Research Units** (RU)
- Data items are called **objects**. An object can consist of multiple files (eg DICOM series) or a single data file (eg statistical model).
- Objects can be related to each other. Related objects are visible in the **Related data** section of each object.
- After upload, the objects are only visible to the owner. These objects are called **unpublished data**. After curation by the owner (filling meta-data, reviewing the data, setting permissions), the data has to be pulished to make them available to other users.  
- Each object has and unique **SMIR-ID** and is renamed according to the SMIR naming template. The original file name is only visible to the user who owns the data



### Registration

For registration, a research unit (RU) is required. Please check (interally) if your institute already has registered. 

1. RU exists, use it in the registration form
2. Challenges, use the appropriate challenge group for registration
3. RU does not exist, use the link on the registration page to request your own research unit.

### Upload

To add data to SMIR, use the upload page. After successful upload, the data in still unpublished (only visible to you) and some steps need to be complete before publishing.

### Adding meta data and publish

1. add **meta-data** like *description*, *height*, *age* etc. The *anatomical region* is the only field required to publish the object
2. add **relate data** object. For example, link a segmenation to its image object
3. Set **permissions**. Choose how users/RU can access your data object. 
4. Set a **license** to specify how the data can be used by others
5. After **pulishing** the data is available to other users

### Organize the data

Your can find your data in **My SMIR > published data**. You can organize them in MyProjects (visible to you) or in MyGroups (visible to group members). Here are the steps needed

1. Create a new folder 
2. Select the objects you want to put into this folder and select *copy* in the object menu. 
3. A copy of the object is now visible in the folder
4. You can shared the folder if you want to make it available to other users

! The object is always visible in **published data**. 
! The object permission are **NOT** affected when sharing a folder

### Find data

Use the full-text search field in the to bar or the modular search. Additionally, have a look at the **SharedFolders** in **MyPlaces**.


### Download

Use the download in the menue item of each object. The system generates a *zip* file which is downloaded. It includes 

- the data files
- The license (.txt)
- the meta data (.json)





