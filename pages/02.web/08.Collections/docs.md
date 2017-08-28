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
- Images can be inserted using base64 encoding or pointing to an external url
  - Use the reference syntax
  - [Online base64 encoder](http://jpillora.com/base64-encoder/)
```markdown
![Image Caption][image]`

... content

[image]data:<base64imagecontent>
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
You can add single objects or folder content to a collection

![smir-add-object-to-collection](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-add-object-to-collection.png)

### Adding objects

![smir-add-objects-modal](.https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-add-objects-modal.png)

### Adding folders

![smir-add-folder-modal](.https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-add-folder-modal.png)


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

You can download individual or multiple object from the list.

![Download objects](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-download-collection-obj.png)


