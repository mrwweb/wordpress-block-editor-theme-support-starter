# Starter CSS for the WordPress Block Editor

It's awfully hard to remember the markup, classes, and options for all the new blocks in WordPress. This project aims to document that information in an easy-to-grab starter stylesheet for WordPress themes.

**Contributions are encouraged! Submit a simple pull request or open an issue (encouraged before larger PRs).**

## Note on CSS selectors

The selectors in this project are as much for documentation as they are for styling. That's why every class is qualified with an element. This is particularly useful in cases where a block may change markup depending on it's configuration.

Depending on your CSS authoring preferences and site environment, you are encouraged to adjust selectors in your project to keep specificity as low as possible.

## Comment Styles

Follow the [TwentyTwenty](https://github.com/WordPress/twentytwenty/blob/master/style.css#L51) section comment styles for block group sections and PHPDoc-like comments for a single block section.

## Roadmap

- Keep updated with future versions for WordPress (Issues & PRs greatly appreciated!)
- [ ] Add SCSS version of stylesheets, possibly with useful features like @each loop for color classes ([Feedback issue re: SCSS](https://github.com/mrwweb/wordpress-block-editor-theme-support-starter/issues/2))
- [ ] Add supplemental stylesheets for popular 3rd-party blocks
- [ ] (Maybe?) Include relevant PHP functions for theme support
- [ ] (Maybe?) Support for package managers

## Finding This Useful?

You'll probably love the [MRW Simplified Editor plugin](https://wordpress.org/plugins/mrw-web-design-simple-tinymce/).
