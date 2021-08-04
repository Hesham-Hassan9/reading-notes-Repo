# Images
There are many reasons why you might want to add an image to a web page: you might want to include a logo, photograph, illustration, diagram, or chart

**Choosing Images for Your Site:** A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.

**Storing images on your site:** If you're building a site from scratch, it's a good idea to create a folder for all the images your site uses.

### To add img:
**Adding Images:** (img) To add an image into the page you need to use an (img) element. This is an empty element (which means there is no closing tag).

### To change height & width of Images
Height & Width of Images: You will also often see an (img) element use two other attributes that specify its size:
* height: This specifies the height of the image in pixels.
* width: This specifies the width of the image in pixels.

### Where to Place Images in Your Code
Where the image is placed in the code will affect how it is displayed. Here are three examples of image mode that produce different results:

1: Before a paragraph The paragraph begins on a new line after the image.

2: Inside the beginning of a paragraph the first row of text is aligned with the bottom of the image.

3: In the middle of a paragraph, the picture is placed between the words of the paragraph in which it appears

### Three Rules for Creating Images
1. Save images in the right format: Websites mainly use images in jpeg, gif or png format. If you choose the wrong image format, your image may not look as sharp as it should and can make the web page load slower.
2. Save images at the right size: You must save the image at the same width and height as it will appear on the site. If the image is smaller than the width or height you specified, the image can be distorted and stretched. If the image is larger than the width and height if you select, the image will take longer to appear on the page.
3. Use the correct resolution: Computer screens are made up of dots known as pixels. The images used on the web are also made up of small dots. Resolution refers to the number of dots per inch, and most computer monitors only display web pages at 72 pixels per inch. So saving images in a higher resolution results in images that are larger than necessary and take longer to download.

**Image dimensions:** The images you use on your website must be saved at the same width and height you want them to appear on the page.

The (img) element is used to add images to a web page. You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image. You should save images at the size you will be using them on the web page and in the appropriate format. Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

# Color
## Foreground Color
Color: The color property allows you to specify the color of the text within the element. You can specify any color in CSS in one of three ways:
* RGB values: These colors are expressed in terms of the amount of red, green, and blue used in their composition. For example: rgb(100,100,90)
* Hexadecimal codes are six-digit codes that represent the amount of red, green, and blue in a color, preceded by the pound sign or the hash sign #. For example: #ee3e80
* Color Names There are 147 predefined color names that browsers recognize. For example: DarkCyan

**Background color:** CSS treats each HTML element as if it were appearing in a box, and the background color property sets the background color for that box.

Color not only brings your site to life, but also helps convey mood and provoke reactions. There are three ways to specify colors in CSS: RGB values, hex codes, and color names. Color selectors can help you find the color you want. It is important to make sure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content). CSS3 introduced an additional value for RGB colors to indicate opacity. It is known as RGBA. CSS3 also lets you specify colors as HSL values, with an optional opacity value. It is known as HSLA.

# Text
### Typeface Terminology:
* Serif
* Sans-Serif
* Monospace

Methods that provide a wider choice of font shapes: There are several ways to use fonts other than those listed on the previous page. However, fonts are subject to copyright, so the methods you can choose from are limited by their respective licenses.

Specifying Typefaces: 
* font-family: The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.
font-size: The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font.
Type Scales: You may have noticed that programs such as Word, Photoshop and InDesign offer the same sizes of text.

There are properties to control the choice of font, size, weight, style, and spacing. There is a limited set of fonts that you can assume most people have installed. If you want to use a wider range of fonts, there are many options, but you must have the correct license to use them. You can control the spacing between lines of text, individual letters, and words. Text can also be aligned left, right, center, or justified. It can also be indented. You can use pseudo-classes to change the style of an element when the user scrolls or clicks on text, or when they visit a link.

# JPEG vs PNG vs GIF:

There are three image formats commonly used in websites and mobile apps - JPEG, PNG, and GIF. These three image formats have significant differences between them which makes each one suitable for specific use cases. Understanding these key differences will help us provide the best possible images for our website and mobile app users.

### TL; DR
Use the JPEG format for all photos that contain a landscape or photograph where the contrast in color and intensity is smooth. Use the PNG format for any image that needs transparency, or for images that contain text and objects with sharp contrast edges, such as logos. Use the GIF format for images that contain animation.

### pressure
Almost all forms of data we see on the Internet - text, image, video, etc. - are compressed to reduce data size and ensure faster transmission. Choosing the correct format and compression is a major factor in determining image size.

**JPEG:** is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any appreciable difference in quality. Moreover, the compressive artefacts become more prominent. Because JPEG compression works by averaging the colors of nearby pixels (read the separate cosine transformation).

**PNG:** is a lossless image format using DEFLATE compression. No data is lost during compression and no compressed defects are introduced into the image. For this reason, a PNG image will retain a higher quality than a JPEG image and will look sharper, as well as take up more disk space. This makes it not suitable for storing or transferring high-resolution digital photos but is a great choice for photos that contain text, logos, and shapes with sharp edges.

**GIF:** It is also a lossless image format that uses the LZW compression algorithm. It was preferred over PNG for simple graphics in websites in its early days because PNG support was still growing. Since PNG is now supported across all major devices and PNG compression is about 5-25% better than GIF compression, GIFs are now primarily used only if the image contains animation.
### Transparency
In a simple form, transparency indicates something that is completely invisible. Logos and icons often need to be placed on backgrounds with variable colours. 