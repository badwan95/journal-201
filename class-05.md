# HTML Images; CSS Color & Text

## Duckett HTML book:

### Chapter 5: “Images” (pp.94-125)
* You can store images on a folder or use images URL on your site.

* You can add images using the < img > element and src="" attribute, its also an empty element that doesn't require a closing tag, also you can use alt attribute to give idenication text if the image doesn't load.

* You can control the height and width of imagesby using the same words as attributes, but it's better to use CSS for this.

* Popular image formats: JPEG when you have a picture with many colors, GIF and PNG format for images with few colors.

* Images should be saved at 72 pixels per inch because most computers have that ppi and having higher resolutions means having a bigger size and longer time to load.

* HTML5 added figure and figcaption tags, figure is the semantic tag for figures, and figcaption adds a caption to the image (semantic too).



### Chapter 11: “Color” (pp.246-263)

* You can specify color in CSS in three ways: RGB values, hex codes and color names.

* Best way to pick text color and background color, high contrast is easier to read but medium contrast is better for long spans of text.

* Opacity is a value between 0 and 1, its used by rgba.


### Chapter 12: “Text” (pp.264-299)

* typefaces are type of fonts that change based on the properties of the letters and their heights, the padding between the letters etc...

* You can choose specific fonts for your website, browsers usually only display a font if it's installed on that user's computer

* Typefaces are subject to copyrights, font family that are installed on a compmuter are okay to use, while font face and service baseed font face require a permit.

* font-family property allows you to specify the typeface in CSS.

* Change the size of the text using font-size property.

* Type scales are uniform across multiple programs because they follow a scale that was made centuries ago.

* If you want more fonts, even if they are not installed on the computer, use @font-face property, you need to specify a path to a copy of the font which will be downloaded to the computer if it's not already.

* Different browsers support different formats for fonts, so you will need to supply the font in several variations to reach all browsers, also if you dont have that file conversions, you can use FontSquirrel site to convert it to more formats, it also provies the @font-face rule which is very helpful, those are some types of formats that should appear in your code in order:

1- eot
2- woff
3- ttf/otf
4- svg

* You can make the text bold by using font-weight: bold;

* For italic, you need font-style: italic;

* Text-decoration propert includes none, underline, overline line-throught and blink (blink is annoying).

* CSS3 property: drop shadow: adds shadow to the text, text-shadow: 

* You can use attribute selectors that apply to an element that have a specific attribute value.













