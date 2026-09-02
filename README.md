## **License**
This repository is released under the Creative Commons BY‑NC‑ND 4.0 license.
You may download and share the PDF and notebooks freely.
Commercial use and derivative works are not permitted.



## **Description of this repository**
 
 This repository contains the PDF version of the book *Algebraic Funtions, A Computational Introduction using Mathematica* with supporting Mathematica notebooks.  The repository is orgainzed as follows:

```
 algebraicFunctions\
  |- notebooks\
  |    |- notebookLoader.nb
  |    |- ch1Introduction.nb
  |    |- ch2BranchPlots.nb
  |    |- . . .
  |    |- ch12RationalBeta.nb
  |- PDF\
  |    |- algebraicFunctionBook.pdf
  
```

The notebook folder contains the Mathematica chapter notebooks referenced in the book and includes a notebook loader used to download the notebooks and book PDF file.  The PDF folder contains the PDF version of the book. 

## **About the Book**

*Algebraic Functions: A Computational Introduction Using Mathematica* provides a visually rich, computation‑driven introduction to multi‑valued functions.  The text begins with algebraic functions—the simplest and most structured class—and gradually builds the conceptual tools needed to explore more complex examples.

The accompanying Mathematica notebooks reproduce every computation, figure, and example from the book as well as other exercises for each chapter.

---

## **Recommended Download Method**

If you have Mathematica versions 13 or higher, the easiest way to download *all* materials is through the automated loader using the following steps.  Note this procedure will create the directory structure above at a desired local location.

### ⚠️ **Important: Use `notebookLoader.nb` to install the project correctly**

> A **`config.wl`** file is automatically created during the download process when using **`notebookLoader.nb`**.  
> This file is essential: it tells all notebooks where to store computed data inside the **`algFunctionBook/data`** directory.  
>
> If users download notebooks manually *without* using the loader, the **`config.wl`** file will not be created, and notebook export functions will fail.

### **1. Download notebookLoader.nb**
- Open the ***notebooks*** directory  
- Click ***notebookLoader.nb***  
- At the top right, click the download icon (arrow going into a box).  Then click ***Open***.  This will open the file in Mathematica.  Note the notebooks were designed and tested with Mathematica version 13 and checked with version 15.  The notebooks may not execute correctly with earlier versions. 

### **2. Run the Loader**
Run the notebook.  The loader will prompt the user for a desired local destination for the book and notebook folders.  For example, on a Windows system, if the user selects the D:\ drive, then the following folder structure is created:

```
 D:\algFunctionBook\
  |- notebooks\
  |- PDF\
   
```
The loader then does the following steps:
- Download all chapter notebooks into ***D:\algFunctionBook/notebooks/***
- Create a ***D:\algFunctionBook\data*** directory.  This directory is used by all the notebooks for computed data storage
- Download a ***config.wl*** file into the ***D:\algFunctionBook*** folder.  This file identifies the directory name used to store the files created by the notebooks.
- Display a summary of downloaded files

### **3.  Download the book PDF file directly to a desired location**

Click the ***PDF*** folder.  Then click the ***algebraicFunctionBook.pdf*** file.  Next, click the download icon and download the PDF file to a desired destination. Click on any hyperlink to navigate through the book.  Use your PDF viewer’s Back command to return to your previous location after clicking a link. For example the Alt+left arrow key is used by Firefox which is the recommended book viewer.

This ensures readers receive the complete and organized installation.

---


