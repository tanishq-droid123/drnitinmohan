KidsGastro multi-page GitHub Pages layout

- index.html is the home page.
- Each named folder contains its own index.html page.
- All internal page links use root-relative URLs (for example /treatments/).
- CNAME contains drnitinmohan.com.
- Extract the ZIP, then upload the CONTENTS of this folder to the root of your GitHub Pages repository (do not upload the ZIP itself).
- Upload the original image assets into /assets/ using the filenames listed in assets/README.txt.

Implementation note: the supplied site uses a large amount of shared inline CSS/JavaScript and page templates. To minimize behavior changes, the common source is retained in each page entry point; each URL displays its corresponding template.
