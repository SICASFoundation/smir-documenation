---
title: Folders
taxonomy:
    category: docs
---

## Structure

MyData: 
1. MyGroups
  1. Group1
  2. Group2
2. MyProjects
  1. Project1
  2. Project2
3. SharedFolders

![folder overview](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-folders-collapsed.png)


![folder overview](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-demo-myplaces.png)


### Group Folders

Each research unit has its own group folder accessible by all members.

### Project Folders

This is the place to create/organize your data into projects. 

### Shared Folders

All folders shared with you by other users are listed here.

## Folder creation

1. Navigate to the folder wherein you want to create a new folder.
2. Use the *Action > New Folder* menu entry to create a new folder.

!! Folder name restrictions: no special characters and no spaces allowed except `_`, max. length 32 chars

## Folder deletion

! It is only possible to delete an empty folder at the moment.

1. Navigate to the folder you want to remove.
2. Use the *Action > Delete Folder* menu entry to delete a folder. 
2. A popup will require you to confirm the deletion of the folder.
3. Confirm the deletion.

![folder deletion confirmation](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-delete-folder-confirmation.png)

## Folder sharing & permissions

### Permissions

Similar to the object permissions described in the previous chapter, the access to a folder can be defined with fine-grained permissions.

- **Visit** (V) allows the associated user/group to see the folder and its content.
- **Modify** (Mo) allows the associated user/group to modify the folder (e.g. add/remove content from the folder and rename it).
- **Manage** (Ma) allows the associated user/group to manage the folder (e.g. change permissions).

### Permission sets 

A permission set is a combination of multiple folder permissions.

- **Viewers** allows the associated user/group to see the folder and its content.
- **Collaborators** allows the associated user/group to modify the folder including the permissions of **Viewers**.
- **Editors** allows the associated user/group to manage the folder including the permissions of **Collaborators**. 

![Permission sets](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-folder-permission-sets.png)

### Sharing a folder
1. Navigate to the folder you want to share.
2. Use the *Folder menu > Share* menu entry. 
3. Make sure you select the *Folders* tab.
4. Select the permission set.
5. Search for the user/group and press *Add* (repeat to add multiple users).
6. *Save*

![folder sharing](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-folder-sharing.png)

! Object permissions are not affected by folder sharing! You only define how other users can access the folder and view the contents. Example: An object is set to private and is added to a shared folder. In this case only the owner will see the object in this folder, other users do not.
