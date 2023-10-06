

## Usage

### The following variables are required:

`_config.yml`:
* `title`
* `author`
* `description`
* `baseurl`  

`index.md`:
* `banner_title`
* `banner_subtitle`
* `background_image`

### The following variables are optional:
`index.md`:
* `favicon`
* `facebook_username`
* `twitter_username`
* `github_username`
* `linkedin`
* `google_analytics` (your Google Analytics Tracking ID)

By declaring these variables, you can include a button that links to an external website or to media.
* `about_button` (the link)
* `about_button_label` (the label on the button)

By declaring these variables, you can include a portfolio showcasing your work and organize your portfolio's items into a custom layout, all without adding any CSS. In addition, you must 1) create an HTML file in the_includes folder for each project with the text you'd like to display, and 2) create a YAML file in the _data folder describing how each project should be shown and categorized. See `/includes/example.html` and `/_data/work.yml` for examples.
* `portfolio` (the heading for your portfolio and title of your YAML file)
* `portfolio_description` (a description to be displayed below the heading and above the content)

By declaring these variables, you can include a CTA section.
* `cta` (the heading for your CTA section)
* `cta_description` (a description to be displayed below the heading and above the content)
* `cta_button` (a link to an external website or to media)
* `cta_button_label` (the label on the button)

## Additional Information
Created by [Sara Gong](https://saragong.github.io/), University of Southern California.  

This work is licensed under the MIT License, which lets you use, modify, and publish adaptations of this template free of charge and without restriction, as long as you preserve all copyright notices and licenses.  

This original theme, of which this is an adaptation, is licensed by HTML5 Up under the [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/).  


