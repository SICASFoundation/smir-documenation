---
title: Errors
taxonomy:
    category: docs
---

# Upload error messages

### Warning 1S

Message: The file (type:'RawImage') named `{0}` was successfully uploaded but not inserted.
Reason: An identical file you own (ID: `{2}`) already exists in `Published Data`.  (Warning `{1}`)

### Warning 5S

Message: The file (type:'RawImage') named `{0}` was successfully uploaded but not inserted. 
Reason:  An identical file you own (ID: `{2}`) already exists in `Unpublished Data`. (Warning `{1}`)

### Warning 0X

Message: An unexpected system error occurred (Error `{1}`) 

### Warning 2X

Message: The file named `{0}` failed for the follwing reason: Case `2X` is not supported by SMIR.[ˆ1]

Reason: An identical file (ID: `{2}`) owned by another user already exists on SMIR. (Error `{1}`)

### Error General

Message: The file upload failed.

Reason:   No connection to https://www.smir.ch could be established.

------

`{0}` = name of the uploaded file

`{1}`  = name of the error

`{2}`  = ID of the existing 



## The insertion of the file failed

**Error Message: The insertion of the file ` filename.ext` failed**

### Upload process took longer than the given transaction timeout of 60 minutes

- Try to upload with a faster internet connection
- Try to use another file format eg. DICOM to split the file into smaller files

### corrupted/unreadable file / file format

- Please check your file / file format to be supported by SMIR

### deadlock

- try again later