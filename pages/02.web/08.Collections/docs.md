---
title: Collections
taxonomy:
    category: docs
---

Collection is a special object type. You do not upload data, you generate it on the web. It is a collection of other objects presented with a description, contact information etc.. The collection object generates internally two files which can be downloaded.

- a  markdown (.md) file with the description
- a  comma separated list (.txt) holding the contained objects 

## Create a collection

A folder is the base for a collection. Navigate to the desired folder and select **Create collection** from the **Action** menue of the folder.![Create collection](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-create-collection.png)

The all contained objects are included in the collection automatically. 

### Provide description

The description is prefilled with template text and is intended as a starting point. You can edit the content to you likings.

- Use the **markdown** syntax. Here some usefull resource
  - [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
  - [Syntaxt Documentation](https://daringfireball.net/projects/markdown/syntax)
  - [Markdown Editor Typora](https://typora.io/). Cross-platform, Syntax and live preview,and wide range of export options. 
#### Images 
Images can be inserted using base64 encoding or pointing to an URL

##### URL 
You can use the preview image URL or any other external URL

1. Upload a preview image
2. Open the preview image after upload
3. Right click on the image in the popup and select **Copy Image Location**​
4. Add this code where you want to display the image

`![Caption](http://anyurl.org)`

`![Caption](https://www.smir.ch/Handler/ObjectImage.ashx?objectId=214259&number=1&type=1&hash=B983F46522B91A3CD8C4CC011679CE9B3537877E)`

##### Base64
  - Use the reference syntax
  - [Online base64 encoder](http://jpillora.com/base64-encoder/)

```markdown
  ![Image Caption][image]`
  ... content
  [image]:data:base64imagecontent_verylongstring
```

### Provide information

Fill the **File information** section

- Title: Title of the collection
- Contact name: Full name
- Contact email: valid email address
- Description
- Anatomical region

### Publish

Use the **Publish** button to publish the collection. 

### Create DOI

After publishing, the **Create DOI** button is available. For more information please read the [DOI section](https://docs.smir.ch/basics/supported%20standards/doi.html)

![Create DOI Button](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-create-doi-button.png)

### Create DOI for objects

You can generate DOI for a single or multiple included objects. 

![Create DOI for objects](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-create-doi-collection.png)

## Modifiy a collection
You can add single objects or folder content to a collection using the **Add objects/folder** button

![add objects or folder to collection](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-add-object-to-collection.png)

### Adding objects

You can add indivdual object using their SMIR-ID to the collection

![add objects modal](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-add-objects-modal.png)

### Adding folders

![Add folder modal](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-add-folder-modal.png)


## Download

### Collection

![Download collection](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-collection-download.png)

You do only download the collection object, not the contained data objects.

You get a **zip** with these files:
- SMIR.XX.XX.ID.md, the description 
- SMIR.XX.XX.ID.txt, list of contained objects 
- License.txt, the license 
- SMIR.XX.XX.ID.json, the meta-data 

 If you want to download data object read the next section

### Objects

You can download individual, multiple object or all objects from the list. 
- mark the objects to download using the checkboxes and download it using the **Download selected** button
- **Download all** to download the all objects of the collection

![Download objects](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-download-collection-obj.png)


