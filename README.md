# About

The website introduces the ResponsibleTech.Work framework and is open to [community contributions](https://ResponsibleTech.Work/contribute/).

# Dev stack

The website was created in [Jekyll](https://jekyllrb.com/), a static website generator, and is hosted on [GitHub](https://github.com/ResponsibleTechWork/RespTechWork-website)

The design is based on the [Libris theme](https://github.com/stackbit-themes/libris-jekyll) by [Stackbit](https://www.stackbit.com/). The theme's SASS files are stored in the `_sass/imports` folder.

# Content file structure

## The framework

- **The Pledges**: the 7 core pledges of the framework. Source files are stored in the `/responsible-pledges` folder, implemented with the theme's docs layout. Open to suggestions for text improvements.
- **Methodologies**: advice on how to adapt existing methodologies within tech companies.Source files are stored in the `/methodologies` folder, implemented with the theme's docs layout. Open to suggestions for text improvements as well as new methodologies.
- **Tools**: updating existing tools used in different tech roles to encourage day to day action. Source files are stored in the `/_tools` folder, implemented as a Jekyll collection. Open to suggestions for improvements as well as new tools that follow the [requirements](https://ResponsibleTech.Work/about/#tools). To add a new tool, add a new Markdown file with a description and assign one of the existing categories.

## Additional content

- **Resources**: lists of links to additional resources, organized by topic. Source files are stored in the `/resources` folder, implemented with the theme's docs layout. Open to suggestions for text improvements as well as new links. 
- **Blog**: posting news related to the framework and the website. Source files are stored in the `/_posts` folder, implemented as a Jekyll collection. Maintained and updated by the core team.

## Additional pages

Additional static pages (**About**, **Contribute**) are stored in the `/pages` folder.

## Images

When adding images, use the appropriate content folder within the `/assets/img` folder. SVG and WebP are the preferred image file formats to keep the size of the website and its carbon footprint low. Images should only be used when they help people understand the written text better and include descriptive alt text for improved accessibility.

## Settings

General Jekyll settings are stored in the `_config.yml` file, additional variables are defined in the `/_data/_config.json` file. 

# License information

## Libris theme

The modified Libris theme is subject to [Stackbit's License Agreement](https://github.com/stackbit-themes/libris-jekyll/blob/master/LICENSE.md).

## Website content

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

The content of the website is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa] unless indicated otherwise.

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-2C82C9.svg
