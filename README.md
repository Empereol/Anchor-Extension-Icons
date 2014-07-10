Anchor Extension Icons
======================

CSS added extension icons to your anchor link. The styling is left very basic in order to be modified easily to fit your theme.

It works using a pseudo selector examining the `href` of an `<a>` for a known file extension. 

This could be expanded (and incredibly simplified) to use a `data-` attribute on the element but I wanted this to work without having to modify any existing HTML. 

Installation
---

Include the CSS stylesheet: `anchor-extension-icons.css`.

**Example**: `<link rel="stylesheet" href="yourpath/anchor-extension-icons.css">`

Usage
---
Just link your anchors like you normally would. If it ends in a supported extension the CSS will automatically append the icon.

**Example**: `<a href="example.doc">Microsoft Word Document</a>`

Contribute
---
Send pull requests if you feel like anything should change. Just make sure to also comment with your justification for the change. Also, please feel free to add more extensions!

References
---
The original list was taken from: [FileInfo.com - Common File Types](http://www.fileinfo.com/filetypes/common "FileInfo.com - Common File Types")