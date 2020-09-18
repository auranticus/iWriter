# Oxford iWriter
An interactive tool designed to help you write more effectively in English.

Visit this website to use the tool: https://auranticus.github.io/iWriter/

![](https://i.imgur.com/Wi3eQVH.png)

Originally, the tool is ported from **Oxford Advanced Learner's Dictionary 8th Edition**'s CD-ROM to **Oxford Advanced Learner's Dictionary 9th Edition**'s one in HTML format. It is also available for premium users on **Oxford Learner's Dictionaries** website, however, it is going to be removed on 12/31/2020 in favor of new design.

This reposity is created to preserve this version, which works independently without relying on the **Oxford Learner's Dictionaries** website's resources. The new design, however, it cannot be used independently because premium account is required.

More information can be found in the [Help](https://auranticus.github.io/iWriter/help.html) section.

## Features
- PNG icons are in SVG format to be consistent on most resolutions. Courtesy of https://www.svgrepo.com/.
- Fixed several bugs related to CSS.
- Optimized the Help section for smaller file size (it was bloated before due to Microsoft Word -> HTML).
- More information is added in the Models/My Writing section.
- Added new topics (more coming soon).
- De-bloated the tool by removing unnecessary images and scripts.

## Known bugs
- The **Save** and **Save As** options are only available for Chromium browsers. Mozilla Firefox does not support them because it deprecated WebSQL in favor of IndexedDB. See [Issue #1](https://github.com/auranticus/iWriter/issues/1).  
For Safari on iOS 13+, you need to disable **Disable Web SQL** in **Setting** > **Safari** > **Advanced** > **Experimental Features**.
- On iOS, if you don't disable **Disable Web SQL** or use browsers other than Safari, the page is frozen. Attempting to reload will show error "An error occurred while processing XML file."
