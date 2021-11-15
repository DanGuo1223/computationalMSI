# A survey on computational methods for MSI experiments
*by Dan Guo, on 11/05/2021*

## 1. What is Mass Specttrometry Imaging

Mass Spectrometry Imaging (MSI) is a technique that detects spatially-resolved molecular compositions of samples, such as tissues. It collects mass spectra at thousands of locations in a raster pattern throughout a sample. A mass spectrum is a plot with *x-axis* as the mass-over-charge ratio (*m/z*) of ionized molecules and *y-axis* as their corresponding intensities. A location is refered as a *pixel*, and unlike natural images, a pixel in MSI is not represented by RGB values, but a mass spectrum instead. The plot of the intensities of a specific m/z across pixels is called an *ion image*.

## 2. Computational goals in MSI

The computational goals in MSI can be devided into three categories: pixel segmentation, m/z clustering, and image classfication.
- *Pxiel segmentation*, segmenting pixels into segments of homogeneous molecular compositions using a single or multiple m/z.
- *m/z clustering*, clsutering m/z into spatially-similar groups according to their ion images
- *image classification*, classifying MSI into different classes, such as delineation of tumor tissues.

## 3. Pixel segmentation





You can use the [editor on GitHub](https://github.com/DanGuo1223/computationalMSI/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/DanGuo1223/computationalMSI/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
