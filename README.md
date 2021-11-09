# luzy
This is a blog to record my past.

[![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) ![GENERATOR](https://img.shields.io/badge/made_with-jekyll-blue.svg) ![VERSION](https://img.shields.io/badge/current_version-1.0-green.svg)

## Setup

```sh
$ git clone https://github.com/starry99/catbook
$ jekyll serve

# Now you can start customization!
```

## Make it yours

If you want to create a new category, you need to create `*name*.html` in the `categories` folder. And add the following content:
```html
---
layout: page
type: *name*
---

{% include archive.html %}
```
Then the number of pages in the category will be displayed.

## License

[MIT License](https://opensource.org/licenses/MIT)
