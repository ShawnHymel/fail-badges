# Fail Badges

Ever wanted to wear your fails like a badge of honor? Proud that you burned your hand with a soldering iron? Got TX/RX mixed up?

We're here for you, and we want to celebrate failures, because they're part of the learning process. We've all been there.

Download the SVG's for printing or put them on your website!

## How to Print Badges

TODO

## How to Add Badge to Website

TODO

## How to Submit Your Own Design

Badge designs must be in .SVG format and adhere to the [Hex Stickers Standard](https://github.com/terinjokes/StickersStandard). That way, they all have the same size and shape. Learn more about the hex sticker format [here](http://hexb.in/sticker.html).

![Badge dimensions](https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/assets/dimensions.png)

Use a program like [Inkscape](https://github.com/terinjokes/StickersStandard) to create your design. We recommend starting with the [hex image template](https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/template/template.svg) found in the `badges/` directory as a base.

* Make sure you own the rights to the image you are submitting!
* Clone this repo
* Give your .svg file a name using only lowercase letters, numbers, and hyphens.
* Add your .svg graphic to the `badges/` directory.
* Add a md file with the current date in `YEAR-MONTH-DAY-title` format, containing information about your design to the `_posts` directory.

Here is a md file template:

```
---
layout: post
title:  template
author: Yoshua Wuyts
license: CC BY 4.0
image: template.svg
description: Template hex badge from github.com/terinjokes/StickersStandard
sticker_url: (optional) add a url to an online store that will make and ship a sticker version of your badge
---
```

Please be descriptive in the description! This should help people know what the badge represents.

When done, your directory structure should look like this:

```
fail-badges/
|- _posts/
|--- 2020-10-15-my-badge.md
|--- ..
|- badges/
|--- my-badge.svg
|--- ...
|- README.md
```

Make a pull request to this repo! See [this guide](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) for help on making pull requests.

## Resources

Here are some tools that can help you automatically generate stickers:

* Python: [hexsticker](https://github.com/fridex/hexsticker)
* R: [hexSticer](https://github.com/GuangchuangYu/hexSticker)

## License and Credits

See `license` in each badge post md file to view the license information for that particular sticker.

Sticker specifications and repo layout credits go to [hexbin](http://hexb.in/).
