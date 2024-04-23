# HTML
HTML (HyperText Markup Language) is the standard markup language used to create web pages. It describes the structure of a web page using a series of elements, which can be thought of as building blocks. Each element represents a different part of the content, like headings, paragraphs, links, images, and more.

Here's a basic example of an HTML document structure:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Web Page</title>
</head>
<body>
    <header>
        <h1>Welcome to My Web Page</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section>
        <h2>About Me</h2>
        <p>I am a web developer passionate about creating interactive and user-friendly websites.</p>
    </section>
    
    <footer>
        <p>&copy; 2024 My Web Page</p>
    </footer>
</body>
</html>
```

In this example:

- `<!DOCTYPE html>` declares the document type and version of HTML.
- `<html>` is the root element that wraps all the content of the web page.
- `<head>` contains meta-information, links to stylesheets, scripts, and the page title.
- `<body>` contains the visible content of the web page.
- Various elements like `<header>`, `<nav>`, `<section>`, `<footer>`, `<h1>`, `<ul>`, `<li>`, and `<p>` define different parts of the web page's structure and content.

HTML elements are often used together with CSS (Cascading Style Sheets) to style and layout the content, and JavaScript to add interactivity and dynamic behavior to web pages.

<br/>
<br/>
<br/>

# `markup` language
A markup language is a system for annotating a document in a way that is syntactically distinguishable from the text. It uses tags or codes to define elements within the document, which can then be interpreted by software for display, formatting, or other processing.

HTML (HyperText Markup Language) is one of the most well-known markup languages used to structure content on the web. In HTML, elements are represented by tags enclosed in angle brackets (`< >`). These tags define the structure and presentation of the content.

Here are some key characteristics of markup languages:

1. **Tags**: Markup languages use tags to define elements within a document. Tags usually come in pairs, an opening tag (`<tag>`) and a closing tag (`</tag>`), to define the beginning and end of an element.

2. **Attributes**: Tags can have attributes that provide additional information about an element. Attributes appear within the opening tag and provide properties like `id`, `class`, `src`, `href`, etc.

3. **Nesting**: Markup languages allow for nesting of elements, meaning one element can contain another element. This hierarchical structure helps define the relationship between different parts of the content.

4. **Standardization**: Markup languages often follow a standardized set of rules and guidelines to ensure consistency and compatibility across different platforms and browsers.

Besides HTML, other examples of markup languages include:

- **XML (eXtensible Markup Language)**: A flexible markup language designed to store and transport data.
  
- **Markdown**: A lightweight markup language used to format plain text documents, often used for writing readme files, messages in online forums, and more.

- **LaTeX**: A markup language used for typesetting documents, especially scientific and technical documents.

Each markup language serves a specific purpose and has its own set of rules, syntax, and conventions.

<br/>
<br/>
<br/>

# Hyper Text
HyperText refers to text that contains links to other texts. In the context of the World Wide Web, HyperText is often associated with HyperText Markup Language (HTML), which is used to create web pages containing links to other web pages, images, videos, and other resources.

Here's a breakdown of what HyperText means:

- **Hyper**: The prefix "hyper" means "beyond" or "over," indicating that HyperText goes beyond the linear structure of traditional text. It allows for non-linear navigation by linking to other pieces of information, creating a web-like structure.

- **Text**: Refers to the written content, which can be words, sentences, or paragraphs.

In a HyperText document, certain words or phrases, known as hyperlinks, are clickable and lead to another document or resource when clicked. These links can connect different parts of the same document or link to external resources on the web.

For example, in an HTML document, a hyperlink is created using the `<a>` (anchor) element with an `href` attribute specifying the URL of the linked resource:

```html
<a href="https://www.example.com">Visit Example.com</a>
```

When a user clicks on "Visit Example.com," they will be directed to the specified URL.

HyperText allows for interactive and interconnected content, enabling users to navigate through information in a non-linear manner, which is a fundamental concept behind the design of the World Wide Web.

<br/>
<br/>
<br/>

## **`Tags`**
In HTML (HyperText Markup Language), tags are used to define elements within a web page. HTML elements are the building blocks of web pages and represent different types of content, such as headings, paragraphs, links, images, forms, and more.

Here are some common HTML tags and their purposes:

1. **`<!DOCTYPE html>`**: Declares the document type and version of HTML.

2. **`<html>`**: The root element that contains all other HTML elements.

3. **`<head>`**: Contains meta-information, links to stylesheets, scripts, and the page title.

4. **`<title>`**: Sets the title of the web page, which appears in the browser's title bar or tab.

5. **`<body>`**: Contains the visible content of the web page.

6. **Heading Tags**:
    - **`<h1>` to `<h6>`**: Defines headings of different levels, where `<h1>` is the highest (most important) level and `<h6>` is the lowest.

7. **Paragraph Tag**:
    - **`<p>`**: Defines a paragraph of text.

8. **Link Tag**:
    - **`<a>`**: Creates a hyperlink to another web page or resource. It uses the `href` attribute to specify the URL of the linked resource.

9. **Image Tag**:
    - **`<img>`**: Inserts an image into the web page. It uses the `src` attribute to specify the image source (URL) and the `alt` attribute to provide alternative text for the image.

10. **List Tags**:
    - **`<ul>`**: Defines an unordered list.
    - **`<ol>`**: Defines an ordered list.
    - **`<li>`**: Defines a list item within `<ul>` or `<ol>`.

11. **Div Tag**:
    - **`<div>`**: Defines a division or a section in a web page. It is often used as a container for other HTML elements to group them together.

12. **Span Tag**:
    - **`<span>`**: Defines a span of text within a document, typically used for styling or scripting purposes.

13. **Form Tags**:
    - **`<form>`**: Defines an HTML form for user input. It uses various input elements like `<input>`, `<textarea>`, `<select>`, `<button>`, etc., to create form controls.

These are just a few examples of the many HTML tags available for structuring content on a web page. Each tag serves a specific purpose and can be combined with attributes to customize its behavior and appearance.

<br/>
<br/>
<br/>
<br/>
<br/>

# **`Self-closing`** tags
Self-closing tags are HTML tags that don't require a separate closing tag because they don't contain any content between an opening and closing tag. Instead, they close themselves within a single tag. These tags usually end with a forward slash (`/`) before the closing angle bracket (`>`).

Here are some common self-closing tags in HTML:

1. **`<img>`**: Used to embed images into a web page.
   ```html
   <img src="image.jpg" alt="Description">
   ```

2. **`<br>`**: Represents a line break within text.
   ```html
   This is a line.<br>
   This is another line.
   ```

3. **`<hr>`**: Represents a thematic break or horizontal rule.
   ```html
   <p>Paragraph before<hr>Paragraph after</p>
   ```

4. **`<input>`**: Used to create various form controls like text fields, checkboxes, radio buttons, etc.
   ```html
   <input type="text" name="username">
   ```

5. **`<link>`**: Used to link external resources like stylesheets, favicons, etc.
   ```html
   <link rel="stylesheet" href="styles.css">
   ```

6. **`<meta>`**: Provides metadata about the HTML document.
   ```html
   <meta charset="UTF-8">
   ```

7. **`<source>`**: Specifies multiple media resources for `<video>` and `<audio>` elements.
   ```html
   <video controls>
     <source src="video.mp4" type="video/mp4">
     <source src="video.ogg" type="video/ogg">
   </video>
   ```

8. **`<area>`**: Defines an area inside an image map.
   ```html
   <img src="planets.gif" usemap="#planetmap">
   <map name="planetmap">
     <area shape="rect" coords="0,0,82,126" alt="Sun">
   </map>
   ```

When using self-closing tags, it's essential to remember that the forward slash (`/`) before the closing angle bracket (`>`) is necessary to indicate that the tag should close itself. Not all HTML tags can be self-closed; only the tags that are designed to not contain any content can be used in this manner.

<br/>
<br/>

# **`Header tags `**
Header tags in HTML are used to define headings within a web page. These tags range from `<h1>` to `<h6>`, where `<h1>` represents the highest (most important) level heading, and `<h6>` represents the lowest level heading.

Here's a breakdown of the header tags in HTML:

1. **`<h1>`**: Represents the main heading or the most important heading on the page. It should be used sparingly and only once per page to represent the main topic or title.
   
   ```html
   <h1>Main Heading</h1>
   ```

2. **`<h2>`**: Represents a subheading or a section heading. It's typically used for major sections of the content.
   
   ```html
   <h2>Subheading</h2>
   ```

3. **`<h3>`**: Represents a sub-subheading or a subsection heading. It's used to further divide sections into smaller parts.
   
   ```html
   <h3>Sub-subheading</h3>
   ```

4. **`<h4>` to `<h6>`**: These tags represent lower-level headings and are used for subsections within `<h3>` or `<h2>` headings. `<h4>` is lower than `<h3>`, `<h5>` is lower than `<h4>`, and so on.

   ```html
   <h4>Lower-level Heading</h4>
   <h5>Even Lower-level Heading</h5>
   <h6>Lowest-level Heading</h6>
   ```

Header tags are not just for styling; they also provide semantic meaning to the content, which is beneficial for accessibility and search engine optimization (SEO). Search engines use header tags to understand the structure and hierarchy of the content on a web page, which can impact how the page is indexed and ranked in search results.

It's essential to use header tags appropriately to maintain a logical and hierarchical structure for your web page content, ensuring that it's both user-friendly and SEO-friendly.

<br/>
<br/>

# Paragraph Tag
In HTML, the `<p>` tag is used to define a paragraph of text. It represents a block-level element that contains a block of plain text. Paragraphs are commonly used to structure and organize textual content on a web page.

Here's an example of how the `<p>` tag is used:

```html
<p>This is a paragraph of text. It contains multiple sentences that form a coherent block of information.</p>
```

In this example:

- `<p>` is the opening tag that defines the beginning of the paragraph.
- `This is a paragraph of text. It contains multiple sentences that form a coherent block of information.` is the content of the paragraph.
- `</p>` is the closing tag that defines the end of the paragraph.

You can include various types of content within a paragraph, such as text, links, images, and inline elements like `<strong>`, `<em>`, `<a>`, etc.

Here's an example with inline elements:

```html
<p>This is a <strong>bold</strong> and <em>italic</em> paragraph.</p>
```

In this example:

- `<strong>` and `<em>` are inline elements used to emphasize text. `<strong>` makes the text bold, and `<em>` makes the text italic.

Remember to use the `<p>` tag appropriately to structure your content and improve readability on your web pages.

<br/>
<br/>

If you provide plain text without any HTML tags, it will be displayed as-is in the web browser without any formatting or structure applied to it. The browser will treat it as plain text content within the web page.

For example, if you have the following plain text:

```
This is a paragraph of text. It contains multiple sentences that form a coherent block of information.
```

When rendered in a web browser without any HTML tags, it will appear as:

```
This is a paragraph of text. It contains multiple sentences that form a coherent block of information.
```

As you can see, the text is displayed as a continuous block without any line breaks, styling, or other formatting.

To format and structure text on a web page, you need to use HTML tags to define the content's structure, apply styling, and add interactivity. Without HTML tags, the browser will not recognize the content as structured elements and will display it as plain text.

When you provide plain text without any HTML tags within the `<body>` element of an HTML document, the browser will display that text as plain content directly in the body of the web page.

For example, consider the following HTML document with plain text inside the `<body>` tags:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Plain Text Example</title>
</head>
<body>
    This is a paragraph of text. It contains multiple sentences that form a coherent block of information.
</body>
</html>
```

When this HTML document is rendered in a web browser, the text "This is a paragraph of text. It contains multiple sentences that form a coherent block of information." will be displayed directly in the body of the web page as plain text without any additional formatting or styling.

The text will appear just like any other plain text content you would read on a web page, without any headers, paragraphs, or other structured elements.

<br/>
<br/>
<br/>

# **`List`** in HTML
Lists are commonly used in HTML to organize and structure content into ordered or unordered collections. Here's a detailed explanation of both ordered and unordered lists in HTML:

### Ordered List (`<ol>`)

An ordered list (`<ol>`) is used to represent a list of items in a specific order. Each item in an ordered list is preceded by a number or another type of marker indicating its position in the list.

#### Syntax:

```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

#### Attributes:

- **`type`**: Specifies the type of numbering used in the list. Possible values are `1` (default, numbers), `A` (uppercase letters), `a` (lowercase letters), `I` (uppercase Roman numerals), and `i` (lowercase Roman numerals).

  ```html
  <ol type="A">
      <li>Apple</li>
      <li>Banana</li>
      <li>Cherry</li>
  </ol>
  ```

- **`start`**: Specifies the starting number of the list.

  ```html
  <ol start="5">
      <li>Five</li>
      <li>Six</li>
      <li>Seven</li>
  </ol>
  ```

### Unordered List (`<ul>`)

An unordered list (`<ul>`) is used to represent a list of items without any specific order or sequence. Each item in an unordered list is preceded by a bullet point or another type of marker.

#### Syntax:

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

#### Attributes:

- **`type`**: Specifies the type of bullet or marker used in the list. Possible values are `disc` (default, filled circle), `circle` (hollow circle), and `square` (filled square).

  ```html
  <ul type="circle">
      <li>Red</li>
      <li>Green</li>
      <li>Blue</li>
  </ul>
  ```

### List Item (`<li>`)

Both ordered and unordered lists use the `<li>` (list item) element to define individual items within the list.

#### Syntax:

```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
</ol>

<ul>
    <li>Item A</li>
    <li>Item B</li>
</ul>
```

#### Nesting Lists:

You can also nest ordered and unordered lists within each other to create hierarchical lists.

```html
<ol>
    <li>Main Item 1</li>
    <li>Main Item 2
        <ul>
            <li>Sub-item 2.1</li>
            <li>Sub-item 2.2</li>
        </ul>
    </li>
    <li>Main Item 3</li>
</ol>
```

In this example, "Main Item 2" contains a nested unordered list with two sub-items ("Sub-item 2.1" and "Sub-item 2.2").

### Summary:

- **Ordered List (`<ol>`)**: Represents a list of items in a specific order using numbers or other markers.
- **Unordered List (`<ul>`)**: Represents a list of items without any specific order using bullet points or other markers.
- **List Item (`<li>`)**: Defines individual items within both ordered and unordered lists.
- **Attributes**: Both `<ol>` and `<ul>` elements can have attributes like `type` and `start` to customize the appearance and behavior of the lists.

By using ordered and unordered lists appropriately, you can effectively organize and present content in a structured and readable manner on your web pages.

<br/>
<br/>
<br/>

# Emmet in VS Code 

Emmet is a powerful toolkit for web developers that greatly improves HTML and CSS workflow in code editors like Visual Studio Code (VS Code). Emmet provides a shorthand syntax for writing HTML and CSS, making it faster and easier to create and edit code.

Here's how you can use Emmet in VS Code:

### Basic Emmet Abbreviations

Emmet allows you to use abbreviations to quickly generate HTML and CSS code snippets. Here are some examples:

- `!`: Generates a basic HTML5 template.
  ```
  ! + TAB
  ```

- `div`: Generates a `<div></div>` element.
  ```
  div + TAB
  ```

- `ul>li*3`: Generates an unordered list with three list items.
  ```
  ul>li*3 + TAB
  ```

### Nested Elements

You can nest elements using `>`:

- `div>ul>li`: Generates:
  ```html
  <div>
      <ul>
          <li></li>
      </ul>
  </div>
  ```

### Sibling Elements

You can create sibling elements using `+`:

- `div+p`: Generates:
  ```html
  <div></div>
  <p></p>
  ```

### Multiplication and Grouping

You can multiply elements using `*` and group them using `()`:

- `ul>li*3`: Generates:
  ```html
  <ul>
      <li></li>
      <li></li>
      <li></li>
  </ul>
  ```

- `div>(header>ul>li*2>a)+footer>p`: Generates:
  ```html
  <div>
      <header>
          <ul>
              <li><a href=""></a></li>
              <li><a href=""></a></li>
          </ul>
      </header>
      <footer>
          <p></p>
      </footer>
  </div>
  ```

### CSS Abbreviations

Emmet also supports shorthand for CSS properties:

- `m10`: Generates `margin: 10px;`
- `p20-30`: Generates `padding: 20px 30px;`
- `bgc#f00`: Generates `background-color: #f00;`

### How to Use Emmet in VS Code:

1. **Enable Emmet**: Emmet is usually enabled by default in VS Code. If it's not enabled, you can enable it by going to `File > Preferences > Settings`, then search for "emmet" and make sure the "Emmet: Enabled" option is checked.

2. **Use Emmet Abbreviations**: Once Emmet is enabled, you can start using Emmet abbreviations in your HTML and CSS files. Type the abbreviation and then press the `TAB` key to expand it.

3. **Customize Emmet**: You can customize Emmet settings by going to `File > Preferences > Settings`, then search for "emmet" to see various Emmet configuration options.

Emmet can significantly speed up your coding workflow by allowing you to write HTML and CSS code more efficiently. It's a tool that many developers find indispensable for web development in VS Code.


<br/>
<br/>
<br/>

# **`Image`** in HTML
In HTML, images are represented using the `<img>` (image) element. Images enhance the visual appeal of web pages by displaying graphics, photos, icons, and other visual content. Below is an in-depth guide on using images in HTML:

### Basic Image Tag

The basic syntax for adding an image to an HTML page is:

```html
<img src="image-path.jpg" alt="Description">
```

- **`src`**: Specifies the URL (source) of the image file. It can be a relative or absolute path.
  
- **`alt`**: Provides a text description of the image, which is displayed if the image fails to load and is used by screen readers for accessibility.

### Relative vs Absolute Paths

- **Relative Path**: Points to the image file relative to the current HTML file.
  ```html
  <img src="images/my-image.jpg" alt="My Image">
  ```

- **Absolute Path**: Points to the image file using the full URL.
  ```html
  <img src="https://example.com/images/my-image.jpg" alt="My Image">
  ```

### Image Attributes

- **`width` and `height`**: Specifies the dimensions of the image in pixels.
  ```html
  <img src="image.jpg" alt="Image" width="300" height="200">
  ```

- **`title`**: Provides additional information about the image, displayed as a tooltip when the user hovers over the image.
  ```html
  <img src="image.jpg" alt="Image" title="This is an image">
  ```

- **`loading`**: Specifies how the browser should load the image. Possible values are `lazy` (load the image when it's near the viewport) and `eager` (load the image immediately).
  ```html
  <img src="image.jpg" alt="Image" loading="lazy">
  ```

### Responsive Images with `srcset`

You can provide multiple image sources with different resolutions or sizes using the `srcset` attribute for responsive design.

```html
<img srcset="image-1x.jpg 1x, image-2x.jpg 2x" alt="Responsive Image">
```

In this example:
- `image-1x.jpg` is for standard displays (1x resolution).
- `image-2x.jpg` is for high-resolution (Retina) displays (2x resolution).

### Image Formats

HTML supports various image formats, including JPEG, PNG, GIF, SVG, and WebP. You can use the appropriate format based on your requirements for quality, transparency, and animation.

### Accessibility Considerations

When using images, it's essential to consider accessibility:

- Always provide descriptive `alt` text to describe the image's content and purpose.
  
- Use `aria` attributes and roles if the image has a specific function, like a button or a link.

### Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Image Example</title>
</head>
<body>
    <h1>My Web Page</h1>
    
    <img src="images/my-image.jpg" alt="Beautiful Landscape" width="800" height="600">
    
    <p>This is a beautiful landscape image.</p>
</body>
</html>
```

In this example, an image with the path `images/my-image.jpg` and the `alt` text "Beautiful Landscape" is displayed on the web page.

Remember to replace `"images/my-image.jpg"` with the actual path to your image file and adjust the `width` and `height` attributes as needed for your specific image dimensions.

<br/>
<br/>
<br/>

# Div / Span - BLock / Inline

In HTML and CSS, elements can be classified into various display types, which determine how they are rendered on the web page. Understanding these display types is crucial for controlling the layout and appearance of your content. Here's an in-depth look at inline, block, div, and span elements:

### 1. Inline Elements

Inline elements are those that do not start on a new line and only take up as much width as necessary. They flow within the content and allow other elements to sit to their left and right. Common inline elements include:

- `<span>`
- `<a>`
- `<strong>`
- `<em>`
- `<img>`
- `<input>`
- `<button>`

#### Example:

```html
<p>This is a <strong>strong</strong> and <em>emphasized</em> text.</p>
```

### 2. Block Elements

Block elements start on a new line and take up the full width available, effectively creating a "block" of content. They do not allow other elements to sit to their left or right unless styled to do so. Common block elements include:

- `<div>`
- `<p>`
- `<h1>` to `<h6>`
- `<ul>`
- `<ol>`
- `<li>`
- `<table>`
- `<form>`

#### Example:

```html
<div>
    <h1>Heading</h1>
    <p>This is a paragraph.</p>
</div>
```

### 3. `<div>` and `<span>` Elements

- **`<div>`**: Short for "division," the `<div>` element is a block-level container used to group and style content. It's often used to create sections or divisions in a web page that can be styled with CSS.

  ```html
  <div class="container">
      <p>This is a paragraph inside a div.</p>
  </div>
  ```

- **`<span>`**: An inline container used to apply styles to a specific section of text or other inline elements without breaking the flow of the content.

  ```html
  <p>This is <span style="color: red;">red</span> text.</p>
  ```

### 4. CSS Display Property

You can control the display type of an element using CSS with the `display` property:

- **`display: block;`**: Makes the element behave as a block-level element.
  
  ```css
  div {
      display: block;
  }
  ```

- **`display: inline;`**: Makes the element behave as an inline-level element.
  
  ```css
  span {
      display: inline;
  }
  ```

- **`display: inline-block;`**: Makes the element behave as an inline-level block container, allowing it to have block-level properties like setting width and height.

  ```css
  .inline-block {
      display: inline-block;
      width: 100px;
      height: 100px;
      background-color: blue;
  }
  ```

### Summary

- **Inline Elements**: Flow within content, only take up necessary width.
- **Block Elements**: Start on a new line, take up full width available.
- **`<div>`**: Block-level container for grouping and styling content.
- **`<span>`**: Inline container for applying styles to specific text or inline elements.
- **CSS Display Property**: Used to control the display type of elements.

Understanding these concepts will help you effectively structure and style your web pages using HTML and CSS.

<br/>
<br/>
<br/>

# **`Video`** **`Audio`** Tag

In HTML, the `<video>` and `<audio>` elements allow you to embed video and audio content directly into your web pages. These elements provide built-in controls for playing, pausing, and adjusting the media playback.

### `<video>` Element

The `<video>` element is used to embed video content on a web page. You can specify various attributes to control the video playback and appearance.

#### Basic Syntax:

```html
<video src="video.mp4" width="640" height="360" controls></video>
```

- **`src`**: Specifies the URL (source) of the video file.
- **`width`** and **`height`**: Define the dimensions of the video player.
- **`controls`**: Adds built-in controls like play, pause, and volume.

#### Additional Attributes:

- **`autoplay`**: Automatically starts playback when the page loads.
- **`loop`**: Loops the video playback.
- **`muted`**: Starts the video with muted audio.
- **`poster`**: Specifies an image to display as the video thumbnail before playback starts.

```html
<video src="video.mp4" width="640" height="360" controls autoplay loop muted poster="video-poster.jpg"></video>
```

### `<audio>` Element

The `<audio>` element is used to embed audio content on a web page, such as music, podcasts, or sound effects.

#### Basic Syntax:

```html
<audio src="audio.mp3" controls></audio>
```

- **`src`**: Specifies the URL (source) of the audio file.
- **`controls`**: Adds built-in controls like play, pause, and volume.

#### Additional Attributes:

- **`autoplay`**: Automatically starts playback when the page loads.
- **`loop`**: Loops the audio playback.
- **`muted`**: Starts the audio with muted sound.

```html
<audio src="audio.mp3" controls autoplay loop muted></audio>
```

### Supported Media Formats

Both `<video>` and `<audio>` elements support various media formats, but browser support can vary. Commonly supported formats include:

- Video: MP4, WebM, Ogg
- Audio: MP3, Ogg, WAV

### Accessibility Considerations

When using `<video>` and `<audio>` elements, consider accessibility:

- Provide descriptive text using the `<track>` element for videos with subtitles or captions.
  
  ```html
  <video controls>
      <source src="video.mp4" type="video/mp4">
      <track src="subtitles.vtt" kind="subtitles" srclang="en" label="English">
  </video>
  ```

- Use the `alt` attribute to provide a text description for the media content, especially if you're embedding the media within a link or another element.

### Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Video and Audio Example</title>
</head>
<body>
    <h1>Video Example</h1>
    <video src="video.mp4" width="640" height="360" controls></video>

    <h1>Audio Example</h1>
    <audio src="audio.mp3" controls></audio>
</body>
</html>
```

Replace `"video.mp4"` and `"audio.mp3"` with the actual paths to your video and audio files. Adjust the attributes and additional settings as needed to customize the playback and appearance of your media elements.

<br/>
<br/>
<br/>

# Marquee and Comments in HTML

### `<marquee>` Element

The `<marquee>` element was a non-standard, deprecated HTML tag used to create scrolling text or images within a web page. It was widely supported in older browsers but is not recommended for use in modern web development due to accessibility and usability concerns.

#### Basic Syntax:

```html
<marquee behavior="scroll" direction="left">Scrolling text here</marquee>
```

#### Attributes:

- **`behavior`**: Specifies the scrolling behavior. Possible values are `scroll`, `slide`, and `alternate`.
- **`direction`**: Specifies the scrolling direction. Possible values are `left`, `right`, `up`, and `down`.
- **`loop`**: Specifies the number of times the marquee should loop. Use a number or `infinite`.
- **`scrollamount`**: Specifies the scrolling speed. Use a number to set the speed.
- **`scrolldelay`**: Specifies the delay between each scroll movement in milliseconds.

```html
<marquee behavior="scroll" direction="left" loop="3" scrollamount="5" scrolldelay="100">Scrolling text here</marquee>
```

### Comments in HTML

Comments in HTML are used to add notes or explanations within the code that are not displayed in the browser. They are useful for documenting your code or temporarily disabling specific parts of it.

#### Syntax:

```html
<!-- This is a comment -->
```

#### Example:

```html
<!-- This is a comment explaining the purpose of the following section -->
<div>
    <p>This is some content.</p>
</div>
```

### Best Practices:

1. **Avoid Using `<marquee>`**: As mentioned earlier, the `<marquee>` element is deprecated and not recommended for use in modern web development. Instead, consider using CSS animations or JavaScript for similar effects.

2. **Use Comments Wisely**: Use comments to explain complex parts of your code, provide context, or temporarily disable code for testing without deleting it.

```html
<!-- TODO: Implement the video player functionality here -->
<video src="video.mp4" controls></video>
```

### Example Combining Both:

```html
<!-- This is a comment explaining the marquee element -->
<marquee behavior="scroll" direction="left">This is a scrolling message.</marquee>

<!-- This is a comment explaining the following content -->
<div>
    <p>This is some content.</p>
</div>
```

In summary, while the `<marquee>` element can create eye-catching effects, it's considered outdated and should be avoided in favor of modern web technologies. Comments, on the other hand, are valuable for enhancing code readability and maintainability.

<br/>
<br/>
<br/>

# **`input`** Tag
The `<input>` element is a versatile form control in HTML that allows users to input data. It supports various types to accommodate different types of user input. Here's a detailed look at some commonly used `<input>` types:

### 1. Text Input (`type="text"`)

The `text` type allows users to input a single line of text.

#### Basic Syntax:

```html
<input type="text" name="username" placeholder="Enter your username">
```

- **`name`**: Specifies the name of the input field.
- **`placeholder`**: Provides a hint or example text that appears in the input field until the user enters their own text.

### 2. Radio Buttons (`type="radio"`)

Radio buttons allow users to select one option from a group of options.

#### Basic Syntax:

```html
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female
```

- **`name`**: Groups radio buttons together so that only one can be selected at a time.
- **`value`**: Specifies the value to be submitted when the radio button is selected.

### 3. Button (`type="button"`)

The `button` type creates a clickable button.

#### Basic Syntax:

```html
<input type="button" value="Click Me" onclick="alert('Button clicked!')">
```

- **`value`**: Specifies the text displayed on the button.
- **`onclick`**: Executes JavaScript code when the button is clicked.

### 4. Color Picker (`type="color"`)

The `color` type provides a color picker interface for selecting a color.

#### Basic Syntax:

```html
<input type="color" name="colorPicker">
```

### 5. Date and Time Inputs (`type="date"` and `type="datetime-local"`)

- **Date**: Allows users to select a date.
  ```html
  <input type="date" name="birthdate">
  ```

- **Datetime Local**: Allows users to select both a date and a time.
  ```html
  <input type="datetime-local" name="meetingDateTime">
  ```

### 6. Select Dropdown (`<select>`)

The `<select>` element creates a dropdown list for users to select one or more options.

#### Basic Syntax:

```html
<select name="country">
    <option value="usa">USA</option>
    <option value="canada">Canada</option>
    <option value="uk">UK</option>
</select>
```

- **`name`**: Specifies the name of the dropdown list.
- **`<option>`**: Defines an option within the dropdown list.
  - **`value`**: Specifies the value to be sent to the server when the form is submitted.
  - Text between `<option>` and `</option>` is displayed as the option label.

### Additional Attributes:

- **`required`**: Makes the input field mandatory.
  ```html
  <input type="text" name="username" required>
  ```

- **`disabled`**: Disables the input field.
  ```html
  <input type="text" name="username" disabled>
  ```

- **`readonly`**: Makes the input field read-only.
  ```html
  <input type="text" name="username" readonly>
  ```

### Summary:

- **Text Input**: Single-line text input.
- **Radio Buttons**: Select one option from a group.
- **Button**: Clickable button.
- **Color Picker**: Select a color.
- **Date and Time Inputs**: Select date, time, or both.
- **Select Dropdown**: Choose from a list of options.

These are just some of the many types and attributes available for the `<input>` element in HTML. By using these effectively, you can create interactive and user-friendly forms on your web pages.

<br/>
<br/>

# **`textarea`** 
The `<textarea>` element in HTML is used to create a multi-line text input field, allowing users to enter longer text content such as comments, messages, or descriptions. Unlike the single-line `<input type="text">` element, `<textarea>` can accommodate multiple lines of text.

### Basic Syntax:

```html
<textarea name="message" rows="4" cols="50"></textarea>
```

- **`name`**: Specifies the name of the textarea field, which is used when submitting the form data.
- **`rows`**: Specifies the visible number of lines in the textarea.
- **`cols`**: Specifies the visible number of characters per line in the textarea.

### Example:

```html
<form>
    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" cols="50">
        Enter your message here...
    </textarea>
</form>
```

In this example:

- The `<label>` element is used to provide a text label for the textarea, enhancing accessibility and usability.
- The `<textarea>` element has an `id` attribute that matches the `for` attribute of the `<label>`, linking the label to the textarea.
- The initial text "Enter your message here..." serves as a placeholder text within the textarea.

### Additional Attributes:

- **`placeholder`**: Provides a hint or example text that appears in the textarea until the user enters their own text.
  ```html
  <textarea name="message" placeholder="Enter your message here..." rows="4" cols="50"></textarea>
  ```

- **`readonly`**: Makes the textarea read-only, preventing users from editing the content.
  ```html
  <textarea name="message" readonly rows="4" cols="50">This is read-only content.</textarea>
  ```

- **`disabled`**: Disables the textarea, preventing users from interacting with it.
  ```html
  <textarea name="message" disabled rows="4" cols="50"></textarea>
  ```

- **`required`**: Makes the textarea field mandatory.
  ```html
  <textarea name="message" required rows="4" cols="50"></textarea>
  ```

### Summary:

- **`<textarea>`**: Multi-line text input field.
- **`name`**: Specifies the name of the textarea field for form submission.
- **`rows`**: Defines the visible number of lines.
- **`cols`**: Defines the visible number of characters per line.
- **Additional Attributes**: `placeholder`, `readonly`, `disabled`, `required`.

The `<textarea>` element is essential for capturing longer text inputs in forms and provides a flexible way for users to enter various types of textual content on your web pages.

<br/>
<br/>
<br/>

# **`Tables`** in HTML 

Certainly! Tables in HTML are used to display tabular data in rows and columns. They are structured using a combination of table-related elements: `<table>`, `<tr>`, `<td>`, `<th>`, and optionally `<thead>`, `<tbody>`, and `<tfoot>`. Here's an in-depth look at creating and styling tables in HTML:

### Basic Table Structure

```html
<table border="1">
    <thead>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </tbody>
</table>
```

- **`<table>`**: Defines the table.
- **`<thead>`**: Groups the header content.
- **`<tbody>`**: Groups the body content.
- **`<tfoot>`**: Groups the footer content (optional).
- **`<tr>`**: Defines a table row.
- **`<th>`**: Defines a table header cell.
- **`<td>`**: Defines a table data cell.

### Table Attributes

- **`border`**: Specifies the border width. Not commonly used in favor of CSS.
- **`width`**: Sets the width of the table.
- **`cellspacing`**: Specifies the space between cells.
- **`cellpadding`**: Specifies the space between the cell content and cell border.

### Styling with CSS

Tables can be styled using CSS for better design and responsiveness.

```css
table {
    width: 100%;
    border-collapse: collapse;
}

th, td {
    border: 1px solid #ccc;
    padding: 8px;
    text-align: left;
}

th {
    background-color: #f2f2f2;
}
```

### Advanced Features

- **Rowspan and Colspan**: Span a cell over multiple rows/columns.
  ```html
  <td rowspan="2">Span 2 Rows</td>
  <td colspan="2">Span 2 Columns</td>
  ```

- **Caption**: Adds a caption to the table.
  ```html
  <caption>Table Caption</caption>
  ```

- **Header Grouping**: Groups header rows.
  ```html
  <thead>
      <tr>
          <th colspan="2">Group Header</th>
      </tr>
      <tr>
          <th>Header 1</th>
          <th>Header 2</th>
      </tr>
  </thead>
  ```

### Accessibility

- **`<th scope>`**: Specifies the scope of a header cell for accessibility.
  ```html
  <th scope="col">Header</th>
  ```

### Example:

```html
<table>
    <caption>Student Grades</caption>
    <thead>
        <tr>
            <th>Name</th>
            <th>Math</th>
            <th>Science</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>John Doe</td>
            <td>90</td>
            <td>85</td>
        </tr>
        <tr>
            <td>Jane Doe</td>
            <td>95</td>
            <td>88</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="3">Average Grade</td>
            <td>89.5</td>
        </tr>
    </tfoot>
</table>
```

This example demonstrates a table displaying student grades with a header, body, and footer section. The `<caption>` element provides a descriptive caption for the table, enhancing accessibility and clarity.

Understanding these table-related elements and attributes will enable you to create well-structured, accessible, and aesthetically pleasing tables for displaying tabular data on your web pages.


<br/>
<br/>
<br/>

# **`Doctype`** in HTML 

The `<!DOCTYPE>` declaration in HTML is used to inform the web browser about the type and version of the document being rendered. It is an essential part of HTML documents as it helps the browser to correctly interpret and display the content.

### Basic Syntax

```html
<!DOCTYPE html>
```

### Explanation

- **`<!DOCTYPE html>`**: This declaration specifies that the document is an HTML5 document.

### Importance

1. **Document Type Declaration**: It defines the document to be HTML and helps browsers to display web pages correctly.
  
2. **Quirks Mode vs. Standards Mode**: Different browsers have different rendering modes based on the `DOCTYPE` declaration. Using a valid `DOCTYPE` ensures that the browser uses the standards mode, leading to consistent rendering across browsers.

3. **Validation**: The `DOCTYPE` declaration is used by validators to check the validity of the HTML document.

### HTML5 Doctype

For HTML5 documents, the `<!DOCTYPE>` declaration is simple:

```html
<!DOCTYPE html>
```

This declaration is case-insensitive, meaning you can also write it as `<!doctype html>` or `<!Doctype html>`.

### Previous Versions

For older versions of HTML, different `DOCTYPE` declarations were used:

- **HTML 4.01 Strict**:
  ```html
  <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
  ```

- **HTML 4.01 Transitional**:
  ```html
  <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
  ```

- **HTML 4.01 Frameset**:
  ```html
  <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
  ```

### Summary

- **`<!DOCTYPE>`**: Declares the document type and version.
- **HTML5**: `<DOCTYPE html>` for HTML5 documents.
- **Previous Versions**: Different declarations for older versions of HTML.
- **Importance**: Ensures correct rendering, validation, and browser compatibility.

Including the correct `DOCTYPE` declaration at the beginning of your HTML document is crucial for ensuring proper rendering and compatibility across various web browsers.

<br/>
<br/>
<br/>

# **`Head`** and **`Meta`** Tags

The `<head>` and `<meta>` tags are essential elements in an HTML document that provide metadata and other important information about the web page. Here's an in-depth look at these tags:

### `<head>` Tag

The `<head>` tag contains meta-information about the document, such as the title, links to stylesheets, scripts, and other metadata.

#### Basic Structure:

```html
<head>
    <title>Page Title</title>
    <meta charset="UTF-8">
    <!-- Other meta tags, stylesheets, and scripts -->
</head>
```

#### Common Child Elements:

- **`<title>`**: Sets the title of the web page displayed in the browser's title bar or tab.
  
- **`<meta>`**: Provides metadata, such as character set, viewport settings, and more.

- **`<link>`**: Links to external resources like stylesheets or fonts.

- **`<script>`**: Embeds scripts or links to external JavaScript files.

### `<meta>` Tag

The `<meta>` tag is used to specify metadata about the HTML document. It doesn't have a closing tag and is used within the `<head>` section.

#### Common Attributes:

- **`charset`**: Specifies the character encoding for the HTML document.
  ```html
  <meta charset="UTF-8">
  ```

- **`name` and `content`**: Used to provide various types of metadata.
  ```html
  <meta name="description" content="Description of the web page">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  ```

- **`viewport`**: Defines the viewport settings for responsive design.
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```

- **`http-equiv`**: Used for HTTP response header fields (rarely used).
  ```html
  <meta http-equiv="refresh" content="30">
  ```

### Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <meta name="description" content="This is a sample web page">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <!-- Page content goes here -->
</body>
</html>
```

### Summary:

- **`<head>`**: Contains metadata and other non-visible content.
  
- **`<meta>`**: Provides various metadata such as character set, viewport settings, description, keywords, etc.

- **Importance**: Proper use of `<head>` and `<meta>` tags is crucial for SEO, accessibility, and ensuring correct rendering across browsers and devices.

Understanding and correctly implementing these tags will help improve the usability, accessibility, and SEO of your web pages.