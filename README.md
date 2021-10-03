# Fail Badges

Ever wanted to wear your fails like a badge of honor? Proud that you burned your hand with a soldering iron? Got TX/RX mixed up?

We're here for you, and we want to celebrate failures, because they're part of the learning process. We've all been there.

Download the SVG's for printing or put them on your website!

## Badges

<table>
  <tr>
    <td>The compiler yelled at you for forgetting a close parenthesis.<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/close-parenthesis/close-parenthesis.svg" width="125" title="parenthesis badge" /></td>
    <td>Forgot to rotate the connector in the middle<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/connectorflipup/connectorflipup.svg" width="125" title="Connector badge" /></td>
    <td>You take your great product to the compliance lab and they dash your hopes of an easy pass with this graph<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/emc-emissions-fail/emc-emissions-fail.svg" width="125" title="EMC emissions fail badge" /></td>
    <td>Your web page looks wonky because you forgot one of these.<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/end-tag/end-tag.svg"" width="125" title="end tag badge" /></td>
  </tr>
  
  <tr>
    <td>You forgot to level the bed and your print failed!<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/failed-print/FailedPrint.svg" width="125" title="Failed Print badge" /></td>
    <td>Were you even paying attention, or were you just doodling on the desk?<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/failed-to-pay-attention-in-class/failed-to-pay-attention-in-class.svg" width="125" title="didn't pay attention in class badge" /></td>
    <td>You overvolted another board and let the magic smoke out!<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/magic-smoke/MagicSmoke.svg" width="125" title="Magic Smoke badge" /></td>
    <td>The compiler yelled at you for forgetting a semicolon.<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/semicolon/semicolon.svg" width="125" title="semicolon badge" /></td>
  </tr>
  
  
  <tr>
    <td>For those times when you've burned your hand with a soldering iron.<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/solder-burn/solder-burn.svg" width="125" title="Solder Burn badge" /></td>
    <td>TX RX labels are evil.<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/txrx-fail-color/txrx-fail-color.svg" width="125" title="TX RX Fail (now in color!) badge" /></td>
    <td>TX RX labels are evil.<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/txrx-fail/txrx-fail.svg" width="125" title="TX RX Fail badge" /></td>
    <td>Forget to link grounds on different pcbs<br><img src="https://raw.githubusercontent.com/ShawnHymel/fail-badges/gh-pages/badges/unevenground/unevenground.svg" width="125" title="uneven ground badge" /></td>
  </tr>
</table>

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

## Resources

Here are some tools that can help you automatically generate stickers:

* Python: [hexsticker](https://github.com/fridex/hexsticker)
* R: [hexSticer](https://github.com/GuangchuangYu/hexSticker)

## License and Credits

See meta.json in each badge folder to view the license information for that particular sticker.

Sticker specifications, repo layout, and much code credits go to [hexbin](http://hexb.in/).
