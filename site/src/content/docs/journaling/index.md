---
title: "Journaling your progress"
sidebar:
    order: 3
---

Journaling! You've probably seen this term thrown around here and there. What is it?

Journaling is a way you can keep track of your progress while working on your project! It usually involves creating a JOURNAL.md file in the root of your repository, and then taking short notes on what you did each day!

Journaling isn't just useful for Hack Club projects, but it gives you something to look back long after you've finished your project! It's also a great way to share your journey with other people who might be interested in your project!

## How to journal

First, you'll need to maek a JOURNAL.md file in your project folder! Just make a .txt file and rename it to .md!

_the `.md` extension is for [markdown](https://www.markdownguide.org/basic-syntax/), a text format that allows you to style text using symbols like `#` and `a\_`! All of the pages on this site are written in markdown_

Next, at the top of the file, add the following data:

```
---
title: "Your Project Name"
github: "your repo"
description: "Describe your project in a short sentence!"
created_at: "2026-03-20"
---
```

_this is called frontmatter, and it's a short [YAML](https://yaml.org/) section that just contains info about your project!_

From there, just start writing new journal entries! Each one should go something like this:

```
# June 8th: <journal entry title!>

<the actual journal content! what you did, some interesting findings, etc.>

<at least 1 picture of where you're currently at! the more the better>

**Total time spent: 2h**
```

_Here's an [example journal entry](/journaling/example-journal/) I did for reference!_

And that's it! Keep making journal entries, read other journals for inspiration, and then submit once you're done!

## More info

Here's some more info on journaling!

**Things you can journal:**

- Time spent designing your project in software like KiCAD, Fusion360, etc!
- Time spent working on art for your project!
- Time spent researching, esp. referencing datasheets!

**Things you can't journal:**

- Time spent watching YouTube videos on your project (I know it's technically research - doesn't count!)

**Some extra tips:**

- Try to make it less of a log of purely "I did X and Y" and include interesting things you came across! Weird quirks in a specific chip, cool inspo you came across, etc!
- Images are worth a lot! Try to add a lot of images and avoid walls of text. It makes it much easier to convey information.

---

If you're using VSCode, one plugin I recommend is [Image Paste CDN](https://marketplace.visualstudio.com/items?itemName=dari.paste-cdn). It allows you to paste images from your clipboard and have the automatically uploaded to Hack Club's storage, which means you don't have to store the images locally!

<img src="https://cdn.hackclub.com/019d5bf7-9950-72e9-a18f-22db6d4bf5ad/final.gif" alt="demo" />

(_pretty nifty, huh ^^_)
