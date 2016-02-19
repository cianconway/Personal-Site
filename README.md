# Personal-Site

### Overview
Website created using Jekyll, a Ruby framework for static websites. This is my personal website which also serves as both an introduction
into Jekyll and also the CSS preprocessor SASS while also providing a summary of my work to date and discussion of topics that interest me 
on a professional level. This is deployed using GitHub pages to [my website](www.cianconway.tech)

### `_includes`
This folder contains all of the modular pieces of my site. Everything from headers and footers to standard icons that are generated and
reused on different pages.

### `_layouts`

### `_posts`
This section contains the various posts I will be creating. There is a standard naming convention with these posts which plays a part in
the correct URL and must adhere to the format `YEAR-MONTH-DAY-title.MARKUP`

### `_sass`
Contains the scss preprocessing files that will be outputted by Jekyll into pure css in the (hidden) `_site` directory.

### `_css`
Main css files are found here

### `config.yml`
This is the YAML file containing the human readable configuration options. These options can either be specified in the `_config.yml` 
file placed in your site’s root directory, or can be specified as flags for the jekyll executable in the terminal.

