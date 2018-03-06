---
title: Browse & Search
taxonomy:
    category: docs
---


## Search bar

- full text search
- user `#` to search for SMIR-ID. You can add multiple to display all of them
`#1402 #1502 #1604`
- use `@` to search for anatomical regions
`@Brain`

![search bar](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-search-bar.png)

## Modular search

You can execute simpel and more advanced (combined) search queries with the modular search. It is available in lists views (Browse, MyData, Folders)

![modular search](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-search-mod.png)

The modular search uses the  `tripples` concept. These tripples can be combined using the logical operators `AND, OR`. Tripples consist of an subject, a predicate and the literal/object. On SMIR, subjects and predicates are predefinded lists while the literal is autocomplete field.

1. Subject: Type (), Object I, Subject ID, Anatomical Region
1. Predicates: `=`, `!=`, `>`, `<`, `>=`, `<=`
1. Literal/object: Autocomplete form (start typing to see the options)

### Example 1: Type, search for segmentations

`(Type = 'Segmentation Image')

![search segmentations](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-search-segmentation.png)

### Example 2: Anatomy, search for objects containg the brain

`(Anatomical Region = 'Brain')`

![search brain](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-search-brain.png)

### Combinations

Search for Raw Images  and for segmentation images with and SMIR-ID greater than 20.

`(Type = 'Raw Image' OR (Type = 'Segmentation Image' AND Object Id > '20'))`

![search complex](https://github.com/SICASFoundation/smir-documenation/raw/master/assets/smir-search-complex.png)

