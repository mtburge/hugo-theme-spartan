# Hugo Spartan Theme
A clean and minimal theme for [Hugo](https://gohugo.io/), designed for small blogs and personal websites.

I built this theme as I wanted a minimal theme, that focused on content and I couldn't find any that matched the look and feel I wanted. As it is focused on content, it may not support all Hugo features. I love [TailwindCSS](https://tailwindcss.com), so it's no surprise I've used that for all its styling goodness.

## See it in action
Shameless plug to my website: https://mattburgess.dev

## Features
1. **Clean and minimal:** very lightweight, scores 100% on all Google Lighthouse tests.
1. **Responsive:** works great on desktop, ultrawides, tablets and mobiles.
1. **Dark Mode:** Automatically switches to a dark theme, based on the operating system settings.
1. **Good SEO support:** Able to change OpenGraph tags, meta tags, description and card data.

## Setup
Have a look in the `exampleSite` directory for example posts and config files.

```json
// Use Hugo modules to add the theme as a dependency:
hugo mod init github.com/itsmattburgess/hugo-theme-spartan

// Add the theme to your config.toml file:
theme = "hugo-theme-spartan"

// Thats it, start your Hugo development server:
hugo server -D
```

## Feedback
Thoughts, feedback, improvement ideas? I'm open to feedback, feel free to open an issue or ping me on Twitter [@itsmattburgess](https://twitter.com/itsmattburgess)