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

Use a program like [Inkscape](https://github.com/terinjokes/StickersStandard) to create your design. We recommend starting with the [hex image tamplate](https://github.com/terinjokes/StickersStandard/blob/master/assets/hex-image.svg) as a base.

* Make sure you own the rights to the image you are submitting!
* Clone this repo
* Create a new folder in the `badges/` directory with the name of your badge, using only lowercase letters, numbers, and hyphens
* Give your .svg file a name using only lowercase letters, numbers, and hyphens
* Add your .svg graphic and a meta.json file containing information about your design

Here is a meta.json template:

```
{
  "name": "txrx-fail",
  "author": "Shawn Hymel",
  "license": "CC0",
  "url": "https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/txrx-fail/txrx-fail.svg",
  "description": "Show that you've messed up the TX/RX wiring on a serial bus at least once!",
  "sticker_url": "(optional) add a url to an online store that will make and ship a sticker version of your badge"
}
```

Please be descriptive in the description! This should help people know what the badge represents.

When done, your directory structure should look like this:

```
fail-badges/
|- badges/
|--- my-badge/
|----- meta.json
|----- my-badge.svg
|----- ...
|--- ...
|- README.md
```

Make a pull request to this repo! See [this guide](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) for help on making pull requests.

## Resoruces

Here are some tools that can help you automatically generate stickers:

* Python: [hexsticker](https://github.com/fridex/hexsticker)
* R: [hexSticer](https://github.com/GuangchuangYu/hexSticker)

## License and Credits

See meta.json in each badge folder to view the license information for that particular sticker.

Sticker specifications and repo layout credits go to [hexbin](http://hexb.in/).