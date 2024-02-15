# WEEK2-CHAPTER-5-TO-9
IMAGE FORMATS
The image  needs to be in a file format that web browsers can understand, and there are various options available. 
There are four main file formats commonly used on the web
SVG-SVGs are perfect for logos, icons, and other types of illustrations.SVG is a vector file that contains instructions for drawing rather than individual pixels
GIF-GIFs are great for compressing illustrations that have large areas of the same color, but it falls short when it comes to photographs.
PNG-PNG is a newer format that works well when you need transparency in a photograph
JPG-JPGs are a popular choice for compressing photographs. Most digital cameras save images in JPG format, but when placed on the web, it is important to resize and compress them appropriately. JPGs can be compressed further by reducing color information, finding the right balance between quality and file size
RESPONSIVE IMAGES
CSS offers a solution for displaying images in different sizes to accommodate both large screens and small screens.Users with slow network connection or limited data should consider to reduce the sizes of all images.
users with big desktop monitors will end up with low-quality, enlarged images. Alternatively, you could opt to keep every image physically small, limiting your web designs.
 RESONSIVE IMAGES SRC SET FORMATS
  there are four copies of a photo at different widths: 480, 960, 1440, and 1920 pixels
  RESPONSIVE WIDTH
  RESPONSIVE PICTURES
  Responsive images and picture element
  you want to show the whole field and the person's entire body, but on small screens, you only want to focus on her face. Just using the image element alone will not cut it, even if you add some attributes like source set or size. That is where the picture element comes into play. use the image element with its ALT text and a URL to the image file. 
  For the first source element, use the source set attribute to point to a mobile image file. This will be the cropped version of the photo, sized at 320 pixels wide. This way, when the viewport is smaller than 600 pixels, this version of the photo will be loaded.
In the other source element, use a kind of media query to specify the image for larger screens. When the viewport is at least 600 pixels wide, the landscape version of the photo will load. This is a pretty neat trick that allows you to optimize the image for different screen sizes.
FIFCAPTION AND FIGURES
Working With Media
The audio element is different from the image element because it has both an opening and a closing tag
Loop will make a file to repeat itself from the beginning until it reaches the end 
WORKING WITH THE VIDEO
Working With Captions and Subtitles

EMBEDDING MEDIA VIA IFRAMES

Embedding refers to taking content from one site and placing it within the middle of another site's page. 
HTML Content Identification
The lang attribute is used to specify the language of a webpage. If the whole page is in one language, it is quite simple. Set the language on the main element that wraps everything else, which is usually the HTML element. It may only be required to set it once, like in a template file that applies to the entire site, but do not forget to do it! 
Embedding refers to taking content from one site and placing it within the middle of another site's page. 
DOCUMENT HEAD
Inside the head of a webpage, you put important information that the browser needs to know about the website
The meta element has various purposes. One common use is to inform the browser that the layout has been adjusted to fit small screens, making it a responsive website. Without this meta tag, the browser assumes the page follows an older layout technique designed for desktops, which needs to be scaled down for mobile devices. 
he Link Element

The link element is a crucial component used extensively within the head section. It serves to connect various assets that should load, such as CSS files, fonts, and favicons. To inform the browser about the type of asset, utilize the rel attribute.
he href attribute is employed to specify the URL for the asset.

The script tag is a commonly used element in an HTML document's head. It instructs the browser to load a JavaScript file. Although it is typically placed at the end of the document, some also include it in the head. 
CONTENT STRUCTURING
SIX IMPORTANT ELEMENTS
Main-It tells the browser where the main content is located
Header- Header is used for site headers, article headers, and headers within the content
Head is where the file's metadata lives and is not displayed to users.
Footer-he footer signifies that there are extra things to convey, regardless of its position on the page.
Article-An article often starts with a title, subtitle, author's name, and publication date, which can also be considered a header
Section -The section element is used to mark sections of content.
. It is also useful for dividing different topic zones on a website
ASIDE- aside element is for content that is off to the side, like sidebar information or additional details that accompany an article but are not part of its main flow
Aside
Working with Forms and Interactive Elements
Form fields have been an essential part of the web for a long time. They are used for various tasks like logging into websites, making purchases, conducting searches, and adding content. 
To create a form, we start with the form element, which informs the browser about the presence of a form using opening and closing tags. In the newsletter signup form, there will be two fields: name and email. 

