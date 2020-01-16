---
title: User Manual
---



# User Guide

## UI Overview

![](/screens/ui-overview.png)

### Open & Create Notebook

Open or create a new notebook by calling the `foxtrot` command
with the filename of the notebook. 

```bash
$ foxtrot example.nbx
```

Start a temporary notebook by calling `foxtrot` without any argument.
After closing a temporary file, it's content is discarded.


### Create Cells 
To create a new cell, first focus a slot by 
To create a new cell either, click the plus button of a slot,
or enter one of the following keyboard command:

* Enter for a Input cell
* Cmd+1 for a H1 cell
* Cmd+2 for a H2 cell
* Cmd+3 for a H3 cell
* Cmd+4 for a H4 cell
* Cmd+7 for a Text cell
* Cmd+8 for a Code cell

### Move between cells

Move to cell above or below the slot by pressing the up/left or down/right keys respectively.

### Select Cells

Cells can be selected with either the mouse or the keyboard.
Click or tab on a cell's margin to select it, hold down the shift key to select a range of cells.
When a cell is selected its margin is highlighted with a blue background.


#### Delete Cells

Selected cells are removed with the the delete or backspace key.

#### ~~Copy, Cut and Paste cells~~

Not yet implemented.

### Plot Function

```
Plot[Sin[x],{x,0,7}]
```

### Draw Graphics

## Cell Types
* Input
* Output
* H1, H2, H3, H4, H5, H6
* Text
* Code

## Read More
* [Keyboard Shortcuts](/guide/keyboard-shortcuts)