# Homebrew webpage

[![Build Status](https://travis-ci.org/Homebrew/homebrew.github.io.svg?branch=master)](https://travis-ci.org/Homebrew/homebrew.github.io)

The webpage uses [jekyll](https://github.com/mojombo/jekyll). The template for
the index is at `_layouts/index.html`.

## Translations
If you want to add a new translation, follow these steps:

1. In `_config.yml` append this:

	```yml
	- langcode: {the_lang_code}
	  lang_string: {the_link_string}
	```
2. Copy `index.html` as `index_{langcode}.html`
3. Change the values of the strings to the translated strings.

You can see the translated webpage by running `jekyll serve` and opening
<http://localhost:4000/>
