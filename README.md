# Pathfinder 2 SRD

The Pathfinder 2 SRD is an unofficial hypertext reference document for the second edition of the Pathfinder role-playing game, which is licensed under the Open Game License. Note that Pathfinder 2 is currently in the beta/playtesting phase, so many of the rules and features are likely to change. Currently, we're working on copying the rulebook verbatim to the SRD, but we hope to offer additional information not available in the text, along with hyperlinking.

## Contributing

There's a lot to unpack in the rulebook, so help would be very much appreciated! Here's how:

1. Fork the project
2. Turn on GitHub Pages in the repository settings (on the master branch)
3. Modify and create Markdown files (see below) as you see fit - you can either do this within GitHub, or through `git` and a text editor on your computer
4. Once you're done, submit a pull request to this repository
5. If your changes are approved, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the site, and your changes will be visible

If you notice a problem or have some feedback, but not the time or knowledge to correct it, you can also submit an issue [here](https://github.com/TristanBomb/Pathfinder-2-SRD/issues). We also have a [Discord channel](https://discord.gg/rr5Q5EQ) that I recommend joining!

### About GitHub Pages

This site is graciously hosted by GitHub Pages, which provides free web hosting with the use of Jekyll (currently the Cayman theme). Pages documentation can be found [here](https://help.github.com/categories/github-pages-basics/) and support [here](https://github.com/contact).

### Markdown

Pages are styled using Markdown. You may be familiar with a more restricted version of Markdown from Reddit and Discord, but this project uses [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/), which is more feature-rich, and can even support raw HTML. Here's some simple examples of Markdown:

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

### Navigation and the Sidebar

If you want to add new pages to the sidebar (or the navigation page for smaller screens), modify `_data/sidebar.yml` like you would other Markdown. Make sure you test it first!

### Guidelines

* All content should be based off Paizo-official material - no homebrew content, house rules, or personal judgements are allowed.
* Make sure the content you're using is licensed under the OGL; this also means that we can't use screenshots from the rulebook PDF.
* Use proper spelling and grammar, professional language, and high editing standards. If you aren't sure how to implement something in HTML/Markdown, ask a maintainer (such as TristanBomb) for help.
* Test your changes before submitting a pull request. Your fork of the site should be visible at `[your GH username].github.io/Pathfinder-2-SRD`.
* Hyperlink to other articles when necessary, and make sure to add new pages to the sidebar.
  * However, because this project and the playtest are still new, copying text from the SRD verbatim is fine. We'll refine it later.
* Not every item, spell, power, etc needs a page of its own - compile them on list pages instead.
