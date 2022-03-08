<div align="center">
    <h3>Choose Your Side</h3>
    <img src="https://raw.githubusercontent.com/scarmuega/choose-your-side/master/vader.svg?sanitize=true#gh-dark-mode-only" alt="Vader" height="240">
    <img src="https://raw.githubusercontent.com/scarmuega/choose-your-side/master/yoda.svg?sanitize=true#gh-light-mode-only" alt="Yoda" height="240">
</div>

## Theme-Dependent README Images

I was today years old when I found out you could tell Github to use a different image in your README depending on the dark / light theme of the user.

No more white-border hacks to make your dark logo show in both themes!

This repo is a quick experiment to see how it works. If done correctly, this README should display Yoda in light mode and Vader in dark mode (try switching your settings if you wish to see the alternative).

To make it work, you need to add both images (light version and dark version) side-by-side in your readme and add a suffix to each one so that they display conditionally.

```markdown
## Dark Theme
![Yoda](https://raw.githubusercontent.com/scarmuega/choose-your-side/master/yoda.svg?sanitize=true#gh-light-mode-only)

## Light Theme
![Vader](https://raw.githubusercontent.com/scarmuega/choose-your-side/master/vader.svg?sanitize=true#gh-dark-mode-only)
```

Check the [offical Github documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to) for more info.

All copyrights and trademarks of the character images used belong to their respective owners.