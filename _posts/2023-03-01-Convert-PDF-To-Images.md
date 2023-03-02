---
title: How to Convert PDF's to Images with GIMP
date: 2023-03-01 15:00:00 -0800
categories: [College Life Hacks, First Day]
tags: [pdf, images, gimp]                   #tags should always be lowercase
---

## Introduction

Sometimes you may need to convert a PDF to an image PDF, which is a PDF file that contains images instead of text displayed over images. This can be useful for a variety of reasons, such as when you want to preserve the formatting of the original PDF or when you want to share the PDF with others who may not have the same fonts installed on their computer. This can also be used to prevent getting falsely accused of plagiarizing with AI software, more info on that topic can be found [here](https://gonzoknows.com/posts/GPTZero-Case-Study/).

Fortunately, GIMP, the popular open-source image editing software, can be used to easily convert a PDF to an image PDF. Here's how to do it:

## Instructions

1. **Install GIMP**

    First, you need to have GIMP installed on your computer. If you don't have it already, you can download it for free from the official GIMP website: [https://www.gimp.org/downloads/](https://www.gimp.org/downloads/)

2. **Open the PDF File in GIMP**

    Once you have GIMP installed, open it and go to `"File"` > `"Open"` to open the PDF file you want to convert to an image PDF.

    ![GIF shows how to open a PDF file in GIMP](/assets/img/pdf/step%202.GIF)

3. **Import Pages as Layers**

    GIMP will show a dialog box asking you how you want to import the PDF file. Choose the `"Open pages as Layers"` option, and click `"Import"`. GIMP will then import each page of the PDF as a separate image. You can view these images by clicking on the Layers tab on the right-hand side of the screen.
    
    ![GIF shows how to import pages as layers in GIMP](/assets/img/pdf/step%203.GIF)

4. **Export as PDF**

    To export the images to an image PDF, go to `"File"` > `"Export As"`. In the `"Export Image"` dialog box, choose a location to save the image PDF file, and give it a name. Under `"Select File Type"`, choose `"PDF"` from the drop-down menu. Click on the `"Export"` button to convert the images to a PDF.

    ![GIF shows how to export a PDF in GIMP](/assets/img/pdf/step%204.GIF)

5. **Choose PDF Export Options**

    In the `"Export Images as PDF"` dialog box, make sure the `"Layers as pages (bottom layers first)"` option is selected, and click `"Export"`.
    
    ![GIF shows how to export layers as pages in GIMP](/assets/img/pdf/step%205.GIF)

6. **Save the Image PDF File**

    GIMP will then save the image PDF file to the location you specified. You can now view and use the image PDF file just like any other PDF file.

That's it! With these steps, you can easily convert a PDF to an image PDF using GIMP. Converting a PDF to an image PDF can be a useful skill to have, especially if you work with PDF files frequently. Give it a try and see how it can benefit you!

### How does Turnitin react?
Many people ask, How does Turnitin react to PDFs that are made up of images? Well it simply doesn't, Turnitin can't scan text `in` images they can only scan text `on` images. Upon submitting your PDFs made up of images to Turnitin, you will likely be prompted with this result. 

![Images shows how Turnitin reacts to PDFs made up of images](/assets/img/pdf/Turnitin%20result.png)

`In order to see the displayed messages on a Turnitin submission, you must hover over the "x" with your mouse cursor`