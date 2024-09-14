---
tags:
  - note
created_at: "2023-02-17"
source: "KemoNine Blog"
---

If you have access to `imagemagick` you can quickly convert a PDF coloring page(s) to grayscale PNG using the below procedure and notes.


## Notes {#notes}

-   The `pdfimages` command below will get you a dpi listing for each page in the PDF that has an image, use that value instead of `300` in the below, **if** it is present.
-   The `-type Grayscale` parameter can be removed if you need color output.
- If the below fails Adobe has an online converter at: https://www.adobe.com/acrobat/online/convert-pdf.html


## Conversion {#conversion}

1.  Install `imagemagick`
2.  `pdfimages -list shipspage1.pdf`
3.  ``for file in `ls *.pdf`; do convert -density 300 -type Grayscale ${file} ${file}.png; done``


## Resources {#resources}

-   <https://stackoverflow.com/questions/50006770/how-to-get-dpi-of-a-pdf-file>
-   <https://jdhao.github.io/2019/11/20/convert_pdf_to_image_imagemagick/>
-   <https://stackoverflow.com/questions/2869908/convert-pdf-to-png-using-imagemagick>
-   <https://legacy.imagemagick.org/discourse-server/viewtopic.php?t=11279>
