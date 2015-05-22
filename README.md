# Pen Paper Coffee :pencil2::scroll::coffee:
*Pen Paper Coffee* is a syntax theme for the text editor [atom](http://atom.io/), which is designed specifically for writing papers, essays etc. in [markdown](https://en.wikipedia.org/wiki/Markdown).
The theme features increased font-sizes for each level of headers, several useful, but not distracting syntax highlightings.
The overall colors are inspired by the soft beige paper you would find in a notebook. While the ink (text color) is a dark blue, all quotes and citations are in a warm brownish orange to contrast them better to your own words. When writing text, not code, I usually set a line height of 1.4 or 1.5 in atoms settings, as you can see in the sample screenshots.

Although this theme was designed for markdown usage, I paid attention that it still looks good and clear with other documents (eg. html, javascript, C).

The screenshots without gutter and text centering had [Zen](https://atom.io/packages/zen) installed, if you like to have centered text but still see the gutter, treeview and tabs [typewriter](https://atom.io/packages/typewriter) might be for you.

When you want to cite stuff from eg. a bibtex file, I find a great package to use together with this theme is [autocomplete bibtex](https://github.com/apcshields/autocomplete-bibtex). It's a great help when combining it with [pandoc](https://github.com/jgm/pandoc) for pdf & latex export from markdown.


### screenshots

![markdown with zen mode](https://raw.githubusercontent.com/nylki/PenPaperCoffee-atom-syntax/master/screenshots/penPaperCoffe_1.png)

support for critic markup:
![critic markup](https://raw.githubusercontent.com/nylki/PenPaperCoffee-atom-syntax/master/screenshots/criticmarkup.png)

![css screenshot](https://raw.githubusercontent.com/nylki/PenPaperCoffee-atom-syntax/master/screenshots/penPaperCoffe_4.png)

The screenshots below  are a bit outdated now, (the gutter color is lighter now, as the screenshots above):

![A screenshot of your theme](https://raw.githubusercontent.com/nylki/PenPaperCoffee-atom-syntax/master/screenshots/penPaperCoffe_2.png)

![A screenshot of your theme](https://raw.githubusercontent.com/nylki/PenPaperCoffee-atom-syntax/master/screenshots/penPaperCoffe_3.png)

## changes
### 11. April 2015
I changed the gutter to a lighter brown, which is much more pleasing, atleast to my eyes. If you prefer the darker gutter, just comment out and uncomment the following lines in `colors.less` to your liking:
```.less
// gutter colors
@heftstreifen: rgb(224, 218, 211);

//@heftstreifen: rgb(202, 193, 186); //old darker gutter
```
