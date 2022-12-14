# TMMifier Chrome Extension
A Chrome Extension for swapping text surrounded by quotation marks with T.M.M. lyrics!

To use/test this, clone the repository, go to _chrome://extensions_ in Chrome, switch the toggle to enable Developer Mode, click "Load Unpacked", and then select the cloned repo's directory. Then Chrome should display it as an extension that you can toggle.

## Websites Recommended for use with the TMMifier

No issues with these websites have been encountered while using the TMMifier.

- [BBC.com](https://www.bbc.com/)
- [The Guardian](https://www.theguardian.com/us)
- [Science.org](https://www.science.org/)
- [Smithsonian Magazine](https://www.smithsonianmag.com/)
- [Space.com](https://www.space.com/)
- [Wikipedia](https://www.wikipedia.org/)

## Limitations:
It currently works with most webpages, but it is incompatible with WordPress websites such as [dbknews.com](https://dbknews.com/) and a variety of other webpages. Thus, the extension will ignore websites that contain certain strings in their source. A message will be printed to the console any time such a website is encountered.

Currently, there isn't a good way to determine if a website is compatible with this extension on-the-fly, so some sites you visit may break. Feel free to report such sites by opening a GitHub issue. Also, if you know of a way to make the extension either work with all websites or automatically ignore incompatible websites, feel free to submit a pull request!

## TODO:
- Fix problem preventing it from working with WordPress websites such as [dbknews.com](https://dbknews.com/) and other websites
  - Or at least find an on-the-fly solution for deterimining if any website is compatible with the extension
- Move the lyrics to their own JSON file
- Maybe add a simple UI to make it easier to toggle
