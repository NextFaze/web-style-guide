# NextFaze CSS style guide

## In a nutshell

| Preprocessor |   Prefixing  | Style enforcement |
|:------------:|:------------:|:-----------------:|
| [SCSS](https://github.com/sass/sass)         | [Autoprefixer](https://github.com/postcss/autoprefixer) | [Stylelint](https://github.com/stylelint/stylelint)         |

## TOC

- [Tools](#tools)
- [Colours](#colour-palette)
- [Font](#Font)
- [Images](#Images)
- [Resources](#resources)

## Tools

Use [sass](https://github.com/sass/sass)

Grids? Try [Susy](http://susy.oddbird.net/)

Care about supporting old browsers? [autoprefixer](https://github.com/postcss/autoprefixer)

Supporting a wide variety of browsers/devices? [normalize.css](https://github.com/necolas/normalize.css/)

Want to display your created styles (For a designer or something)? [aigis](https://pxgrid.github.io/aigis/)

On that note, want to display stats of your css? [CSS Stats](http://cssstats.com/)

Need a linter? Use [stylelint](https://github.com/stylelint/stylelint)

## Colour Palette

Create an official palette for the project (Use [coolors](coolors.co)

e.g., [Brownsea](https://coolors.co/461b6e-622599-0aa65c-58a665-ececec)

## Font

(Site only uses latin based alphabet) ? Helvetica : [Google Noto](https://www.google.com/get/noto/)

## Images

2:1 ratio images are hot right now (Or UWS 21:9 if you want more), use them when appropriate.

Embed small (under 10kb) frequently occuring images (logos etc) in dataURIs. This will save on requests but increase CSS size.

## Resources (Updated 12/10/16)

Start with whatever [Github is currently doing](http://markdotto.com/2014/07/23/githubs-css/)

Check [Airbnb](https://github.com/airbnb/css). It's effectively just as good.

Then move on to whatever [Trello is currently doing](https://gist.github.com/bobbygrace/9e961e8982f42eb91b80) (They use LESS, so ignore those parts.)

If that fails, just vanilla CSS to keep it as extensible as possible, [follow the Maintainable](http://maintainablecss.com/chapters/introduction/) guide.

If you ever read this part, Google 'hacker news 201x CSS'. Read the latest comments and update this guide.

- [Maintainable](http://maintainablecss.com/chapters/introduction/)
- [Trello CSS Guide](https://gist.github.com/bobbygrace/9e961e8982f42eb91b80)
- [Trellisheets](https://github.com/trello/trellisheets)
- [Trello Branding Guide](https://trello.com/about/branding)
