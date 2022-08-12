[![Netlify Status](https://api.netlify.com/api/v1/badges/9a3495d5-35e7-49ab-8a48-5a07192f7936/deploy-status)](https://app.netlify.com/sites/dnd-club-22/deploys)

# What is this?
This is the Repo for my DnD club year 22-23. I wanted a nice way to display the lore to all our players, and this is just the perfect way to go about it.

# Why?
Well, previous years we've either run pre-made modules, or in the case of last year, and incredibly well done doc by NidhoggPhantom. The only problem with that doc was that it was an 80 page word document that you might search through to find something specific, or else read once and never think about again. I wanted a medium that's easier to navigate, and make changes to, and Obsidian + Jekyll is the perfect solution.

# Features
There are loads of features that hail both from the [original project](https://github.com/maximevaillancourt/digital-garden-jekyll-template), by Maxime Vaillancourt, as well as [this](https://github.com/meewgumi/green-web-template/) modified version by Meewgumi that I have improved further upon.

## Changes
All the changes that Meewgumi made are here, with functioning Obsidian embeds, emoji favicons, an archive page, tables and the easily changable theme, and in addition to that I have made some changes of my own.
- **The theme** I swapped the theme for a dark blue one to be easier on the eyes.
- **Footnotes** In Meewgumi's version footnotes weren't classified as local links, so they would open in a new tab. This is now fixed
- **D3.js node graph scrolling strangely** The node graph would visually change size when the window was resized, but the actual bounding box for where you could scroll in it did not. This has also been fixed in my version.

# Template Quirks

Interesting errors and quirks of the project:

-   Your file path must not have any spaces in it or your `bundle` command will fail!
-   Plugins are not compatible with Github Pages instance of Jekyll, so you have to build your site locally and reconfigure output to `docs` folder. I have a similar setup in [this github pages repository](https://github.com/meewgumi/digital-garden-ghpages-template)
-   This template only works for apex and subdomains. If you build your site in a `/directory`, you may have to reconfigure the relative links throughout the template.
-   Does not yet support Obsidian Heading Links in this format `[[page#Heading]]`, although each heading automatically generates an `id=` so you can create anchor links manually with HTML
-   Emoji is not unicode, so they might not display properly in all browsers and operating systems
-   Excerpts on archive page truncate weirdly. I wish there was a way to exclude headings. There probably is if I get deeper into Nokogiri documentation.

# License
This blue theme version is available for free to view and edit on github [here](https://github.com/defyd/green-web-template)

The base, "Green" version, by Megumi Tanaka is [publicly available on Github](https://github.com/meewgumi/green-web-template) and you are free to edit as you wish! [Buy Megumi a tea](https://www.buymeacoffee.com/megumi). 🍵

And finally we have the [original project](https://github.com/maximevaillancourt/digital-garden-jekyll-template), by Maxime Vaillancourt!