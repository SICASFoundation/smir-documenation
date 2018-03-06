---
title: Folders
taxonomy:
    category: docs
---

![folder overview](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-folders-collapsed.png)

## Structure

MyData: 
1. MyGroups
  1. Group1
  2. Group2
2. MyProjects
  1. Project1
  2. Project2
3. SharedFolders


![folder overview](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-demo-myplaces.png)


### Group Folders

The system generates for each research unit a group folder where all members have access. The users group folder are listed here. 

### Project Folders

This is the place to create/organize your data into project. 

### Shared Folders

The folders shared with you by other users are listed here


## Folder creation

1. Click on the folder where you want to create the new folder 
2. Use the *Action > New Folder* menu entry to create a new folder

!! Folder name restrictions: no special characters and no spaces allowed except `_`, max. length 32 chars


## Folder deletion

! It is only possible to delete empty folder at the moment.

1. Navigate to the folder you want to remove
2. Use the *Action > Delete Folder* menu entry to delete a folder. 
2. A popup will require you to confirm the removal of the folder.
3. Finish the removal using the *confirm* button.

![folder deletion confirmation](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-delete-folder-confirmation.png)


## Folder sharing & permissions

### Permissions
- Visit: allow people to view the folder and its content
- Modify: allow users to add/remove content from the folder and rename it. But cannot delete a folder
- Manage: allows to delete folders and manage sharing permission.

### Permission set
- Viewers: share a folder, you control the content
- Collaborators: collaboration folder 
- Editors: 


### Single folder
1. Navigate to the folder you want to share
2. Use the *object menu > share* menu entry to define sharing permission for selected folder. Make sure you select the *folder* tab
3. Select the permission set
3. Search the user/group and press *add* (repeat to add multiple users)
3. *Save*

![folder sharing](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-delete-folder-confirmation.png)

### Multiple folders
1. Navigate to the parent folder of the folder you want to share
2. Use the *Manage selected > share* menu entry to define sharing permission for selected folders. Make sure you select the *folder* tab
3. Select the permission set
3. Search the user/group and press *add* (repeat to add multiple users)
3. *Save*

![folder sharing](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-delete-folder-confirmation.png)

! Object permissions are not affected by folder sharing! You only define how other users can access the folder and view the contents. E.g.private objects in a shared folder stay inaccessable to other users. Example: An object is set to private and is added to a shared folder. Only the owner will see the object in this folders, other users do not.
