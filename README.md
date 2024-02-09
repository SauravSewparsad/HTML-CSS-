# HTML & CSS

## Week 1:
 Day 1: Introduction to Html & css

Day 2: Learning units 1 - 5

# Summary of units

Unit 1: Intoduction to HTML

What is HTML
- HTML is a crucial component in web technology, serving as a channel for various content types, bridging the gap between human and computer languages, and facilitating intelligent communication on the web.

The function of HTML
- HTML, CSS, and Javascript are three programming languages used in the Web. HTML marks content, provides built-in browser functionalities, and is a declarative language with simplicity, resilience, and robustness.
- CSS, or Cascading Style Sheets, is a web page stylist responsible for color, font, and size, and can add animations and interactions. It is both power and fragile, if there is an error in the CSS code the browser is smart enough to skip it and move on to the code that works.
- JavaScript is a powerful programming language used to create interactive websites, but can be fragile if outdated browsers don't understand the code. The Web, created to function on various platforms and devices, relies on HTML, CSS, and JavaScript for resilience and robustness. Developers use HTML for tasks that can be done in other languages, emphasizing the importance of learning HTML elements.

Unit 2: HTML Text Formatting

HTML Syntax
- HTML is a language used to structure web pages using tags, including opening and closing tags. It serves as a bridge between humans and computers, providing meaning to content and helping computers understand it. HTML elements can be nested within each other, creating a tree structure called a DOM tree. The choice of HTML elements impacts user experience, including accessibility.

HTML Paragraphs
- The paragraph element in Notepad++ and HTML window is not resembling paragraphs. To fix this, add an opening (P) and closing tag (/P) , and separate paragraphs with their own tags.

HTML Headlines
- Headlines are essential elements in web pages, dividing content into smaller, more digestible chunks. They act as clickable titles on landing pages and convey a sense of hierarchy in how the browser interprets and communicates about the page. Headlines come in six types: h1, h2, h3, h4, h5, and h6.
- The largest and most prominent element is h1, while the smallest and least attention-grabbing element is h6. Selecting the appropriate headline level is straightforward, starting with the opening tag and ending with the closing tag. This hierarchical system gives meaning to the browser and ensures all article headlines share the same type, ensuring consistency for screen reader users.

HTML Bold and Italics
- The four HTML elements - bold, italic, and bold - are used to emphasize text in a book or magazine. The use of bold is for making a strong point, while italic is used for visually distinguishing between words. In book publishing, journalism, and magazine production, rules dictate when to use bold or italic. In this case, italicizing the word "favorite" emphasizes the character, while italicizing the phrase "Sesame Street" is used to highlight the TV show title. The browser should understand when to verbally emphasize or visually distinguish between the two.
- In HTML, two elements can be used to emphasize or make something bold: the "strong" element, which shows importance, seriousness, or urgency, and the "b" element, which is more generic and neutral. The "strong" element is used to emphasize a specific part of a phrase or to make certain words bold without conveying any meaning. The "b" element is used to make certain phrases bold without holding any special significance for the browser or screen reader. CSS can be used to change the appearance of text to be bold.

HTML List
- Lists are a common aspect of daily life, including to-do lists, recipes, wish lists, and bucket lists. In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists. Unordered lists are the most common, with each item enclosed in an "li" element. Indentation is optional but is used to convey meaning.
- Ordered lists are similar but with a specific order, with "ol" indicating a specific order.
- Definition lists, on the other hand, are used to create a key-value pair in computer science. The term or key is enclosed in "dt" tags, while the description or value is enclosed in "dd" tags. Multiple "dd" tags can be used for each term, and the entire list is wrapped in a "dl" tag. These tags are placed side by side without any additional wrapper, forming a structure that is unique to each list type.

HTML Quotes
- To quote a phrase, the phrase must be in the normal paragraph tag and the author of the quote is in the "cite" tag and we wrap the whole thing in a "blockquote" element.
- To use a quote that is said by someone and place it in semicolons we use the "q" element, which stands for quote.
- To provide additional information for the HTML, in this case the datetime attribute allows us to specify the date or time in a format. The format for the time within the datetime must be specific.

HTML Date and Time Input
- HTML simplifies programming by using a single element called "time" to mark specific moments or ranges in time. This element consists of an opening tag ("time") and a closing tag ("/time"). The "time" element conveys the exact date or time to computers using an HTML attribute called "datetime". The datetime attribute specifies the date or time in a machine-readable format, which is preferred by computers.
- Examples include May 8th as 05, 08, 2025-05-08. Machines prefer 24-hour clock format and can specify the time zone. The datetime attribute can also combine the date and time, with options for separating them using a T or leaving a space. These formatting rules apply to many programming languages and are acceptable and correct. By using the time element with its datetime attribute, we can convey the time in a way that computers can understand.

HTML Code, pre, br
- To showcase code on a webpage, use the code element to create a monospaced font and style it. By default, code is treated as an inline element, meaning it remains part of the sentence. To change the word "H4" into an actual H4 headline, type "<" as an HTML entity. This will display a less than sign and a greater than sign.
- For HTML entities, like br and pre elements, add spaces and line breaks to make code more readable without affecting the webpage's content. For example, to display a poem with irregular spacing, add a br element at the end of each line. This will make the poem look correct and the browser will recognize the line breaks.
- To display a code block with proper indentation, combine pre and code elements. For example, to make a piece of HTML using HTML entities, add indentation to the code and include CSS code, which is also indented.

HTML Superscript, subscript, small text
- Subscripts, superscripts, and small text are used to mark up specific content with different meanings. Subscripts are characters set below the normal baseline for text, while superscripts are characters set above the normal baseline. Mathematical formulas and footnotes often use superscripts.
- To handle subscripts and superscripts in HTML, use sub and sup elements. MathML is a specialized markup language for math, more powerful than HTML. Small text, such as copyright information, can be marked up with a small element to convey its low prominence. CSS can adjust text size to any desired size. However, small text can convey that something has very little prominence, like the fine print at the bottom of a page regarding ownership.

Unit 3: HTML Capabilites

Troubleshooting and denugging HTML Code
- In this text, we examine HTML elements in browser developer tools, which can reveal information about a website's code and performance. To access these tools, right-click on the demo and select "inspect element" or go to "tools," then "web developer," and choose "inspector."
- The inspector has three sections: HTML, CSS, and more options. The left pane displays the HTML and Document Object Model (DOM), which the browser creates when sending HTML to Firefox. If the code has an unordered list with incorrect numbers, it's possible that the browser is adding an extra set of tags. To fix this, add a missing slash before the third item and correct the DOM.

HTML Attributes
- HTML is a complex language that offers additional capabilities through attributes, such as class, ID, and content editable. Class attributes allow for reusable names for elements, which can be styled using CSS. IDs, on the other hand, can only be used once on an entire HTML page and are more specific, making them useful for CSS targeting.
- They are also useful for addressing specific elements in JavaScript or targeted links. These attributes provide a way to name HTML elements and reference them in other parts of the code stack. Examples of these attributes include the editable block quote element, which allows visitors to edit content on a web page.

ARIA Roles
- ARIA Roles are additional attributes added to HTML elements to enhance their meaning and help browsers understand their content. They are crucial for websites that are inaccessible for people with disabilities, as it is against the law in many places. ARIA Roles are particularly useful for assistive technologies like screen readers, braille displays, and magnifiers.
- The accessibility tree, a companion to the DOM tree, is essential for assistive devices like screen readers to provide a better experience. To improve the experience, add an ARIA label to the HTML and hide individual letters within a div element. ARIA Roles are a powerful tool for web accessibility, especially for teams working with semantic HTML or complex application interfaces.

Formatting HTML
- In HTML, programmers add comments to enhance code readability by explaining its purpose. These comments are ignored by the browser, but code editors like Notepad++ can display commented code in a grayed-out fashion. The uppercase versus lowercase debate in HTML is interesting, as it has evolved over time.
- In the late 80s and early 90s, HTML was created to optimize file size due to limited computer resources. As technology advanced, it became more important to prioritize code readability and understandability for humans. Newer HTML elements use complete words instead of abbreviations, making it easier for English-speaking individuals to comprehend code. The length of an element also helps determine its existence. Some older elements have no closing tag, but the best practice is to add a slash at the end of elements without one.

Unusual Charactrers
- HTML symbols <, >, and & are essential for content formatting. However, they disappear when written with spaces, causing the browser to assume it is part of HTML code. To handle this, a character entity (ampersand, short code, and semicolon) is used in HTML files. These entities convert characters into desired ones, replacing instances of greater than or less than symbols.
- The W3C provides a reference chart for these entities. They can also be used to type characters not available on keyboards, such as copyright symbols. Non-breaking spaces are a unique feature in HTML, allowing the browser to wrap text without breaking the line between two words. They can also be used to create multiple spaces between words, ensuring the desired characters are displayed on the webpage.

Unit 4: HTML Navigation and Linking

HTML Links:
- Web links have become an integral part of our online lives, with links appearing in various forms such as navigation bars, menus, and article titles. The concept of linking dates back to the 1980s, when computer innovators focused on hypertext, hypermedia, and hyperlinks. The web's birth is a testament to this obsession.
- To create a link, use the A element (anchor) and an href attribute with a URL enclosed in quotes. The A element can be inline or wrapped around text, images, or complex elements. Absolute URLs, which point to a precise location on the web, can be included without a trailing slash. The HTTPS part, or Hypertext Transport Protocol, defines the rules for communication on the web and is crucial for linking. Nowadays, experts recommend using HTTPS for enhanced security.

HTML URL Pathways:
- In web development, absolute URLs are used for links, but relative URLs can be used when linking to something within the same site and domain as the page containing the link.
- all links should point to the local copy of the files, while links on a testing server should direct to pages and files on that server. Relative URLs are useful for referencing image files, video files, CSS, JavaScript files, or any other file path specified. To form a URL from scratch, one must understand file organization and how files are organized into directories or folders. To create a relative URL, omit the domain name but include the initial slash at the beginning, directing the browser to start from the root level of the file structure.
- Alternatively, write the path to be relative to the file where the link is written. In web development, a clean URL structure is essential for avoiding overlapping links and ensuring the correct file path is used.

Navigation: 
- To create a main menu bar for a website, wrap each link with the correct URL in an element with the correct URL, enclosed in an "li" element, wrapped in an "ul" element, and wrapped in a "nav" element. Apply CSS styling to give the menu a visual appearance and assign the role of "navigation" to the "nav" element. Include an "aria label" for a descriptive label that can be read aloud by a screen reader
- Other approaches include creating a breadcrumb trail, wrapping breadcrumb links in an ordered list, and wrapping links in the footer for additional content. Combining HTML elements to layer semantic meaning into content can help make the right choices for projects.
--------------------------------
Day 3: I continued making summaries on unit 5 and then i began implementing all the skills i have learned from those units.

# Summary of units

unit 5: HTML Working with Graphics and Images

Images:
- Images are essential for the web and should be included in an image element, written as an IMG.
- Four attributes are necessary for every image: source attribute (SRC), alt attribute (ALT), width and height attributes. The source attribute tells the browser which image file to load, the alt attribute provides a text description of the image, and the width and height attributes determine the image's size.
- The ALT attribute serves as a replacement for the image when it cannot be seen. The width and height attributes are necessary for the browser to determine how to display the image after it has been loaded and displayed on the page. This helps in preventing the page from shifting around as the images load, ensuring a smoother reading experience.

Image Formats:
- GIFs compress large, color-saturated illustrations but may not be suitable for photographs due to limited color support and potential pixelation, and may cause jagged edges between transparent and solid parts.
- SVGs, a programming language for graphics, are ideal for logos, icons, and illustrations due to their small size and ability to scale without loss of quality.
- JPGs are commonly used for compressing photographs, but web sites should avoid using large, half-compressed images. Balancing quality and file size is crucial.
- PNG is a transparent, compressable format that outperforms GIF and JPG in image compression. Future image formats may offer even better compression capabilities.

Responsive Images:
- CSS can display images in different sizes to accommodate large and small screens, but it can be problematic for users with slow network connections or limited data plans. To address this issue, HTML allows for the delivery of different image files to screens of different sizes. To do this, create multiple image files with different resolutions and inform the browser about these options. The device can choose which image to use based on factors like screen density, network connection, and user settings.
- To handle different image sizes for retina and high DPI screens, add a source set attribute to the HTML code, which lists the images on offer, separated by commas. The browser will swap out one version of the image for another based on what it considers best. This technique is ideal for handling different image sizes for retina and high DPI screens.

Responsive Width:
- The image element and src set attribute can display images based on screen pixel density and viewport width.
- However, this can lead to issues if the chosen image doesn't fit the desired layout. To address this, use the sizes attribute in HTML to specify the image to use at different breakpoints.
- This allows the browser to download the right-sized image for the layout, considering network conditions and user preferences. This allows the browser to make intelligent decisions based on device density and viewport width.

Responsive Pictures:
- The source set in the sizes attribute can be used to offer multiple image files to the browser, allowing it to decide which one to load and display. This can be useful for displaying different images on different screen sizes, such as mobile devices or desktop computers.
- To optimize images on the web, use techniques like picture, source, and source set. The source set attribute points to a mobile image file, sized at 320 pixels wide, and the other source element specifies the image for larger screens, sized at least 600 pixels wide.
- The browser switches between files, using the larger ones only when necessary, considering both the viewport size and the retina screen. This optimization process benefits everyone, as the image files in this demo range from 27k to 593k, resulting in a difference of half a megabyte per photo.
- This can save up to three megabytes of data if a web page has six photos and saves users 500k per photo.

Figcaption and Figures:
- To match a caption to an image on a web page, use figures and figcaption elements. For example, show a dog picture and add a caption using figcaption. Then, put the image and caption together in a figure element, providing more information about the content.
- Figures can be used for interactive graphics and visual illustrations, making them useful for demonstrating concepts.
-----------------
Day 4: I put the tutorial i was watching on hold and proceeded to study and prepare myself for my assessment on friday. I did excersies to prepare for the practicale and a quiz to prepare me for the multiple choice.

Day 5: Today is assessment day and i went in nervouse and prepares, i earned a 80% for the assessment. After words i began to follow the tutorial i was previously watching on tuesday for the rest of the day and making it a 1/4 through.

-----------------
## Week 2:

Day 1: Today i will be learning units 6 - 9 for today and also begin working on my groups business website

# summary of units

Unit 6: Working with Media

Working with audio
- Audio is more powerful and flexible than images. There are many types of audio format, but for now we will keep it to MP3 files.
- We need to let the browser know that we want it to provide some contols.
- The audio player control can be created using JavaScript and the HTML media element API. It allows users to play, pause, adjust volume, view time, and navigate through the timeline. The audio element demonstrates the power of HTML, providing functionality without having to build it from scratch.
- It also has an opening and closing tag and fallback text for if the browser doesn't understand it. The source element can specify multiple audio files, similar to the picture element. This can be helpful if a new file format is not supported in all browsers while providing a fallback for older ones.

Working with Video
- The web has revolutionized the way we connect and share content, including movies, TV shows, and teaching. The HTML video element allows users to easily display videos on web pages using an opening and closing tag.
- there are two issues to address: video encoding and the compatibility of different codecs. H.264, a patented codec, is not open source and requires licensing fees for devices, operating systems, and cameras. AV1, an open and non-patented video codec, has been developed to address this issue.
- The WebM versus AV1 debate remains uncertain, but recent developments suggest AV1 may be the superior codec and free of royalty charges. HTML allows for multiple source files, enabling simultaneous use of different codecs.
- HTML lacks a built-in mechanism for sending different video sizes based on network conditions. Major streaming platforms like Netflix, Hulu, HBO, YouTube, and Vimeo use adaptive bitrate streaming to ensure seamless switching between different resolutions as users watch videos.

Working with Captions and Subtitles
- Captions and subtitles are essential for making content accessible and engaging for viewers.
- The web allows for multiple ways to provide content, such as using a track element and a text file to add captions to a video. The web uses a file format called ibvtt, which stands for web video text tracks, with each line of text accompanied by a time code.
- To display captions on the video, insert a track element within the video element, specifying the file, kind attribute, label attribute, source lang attribute, and default attribute. A captioning icon appears, allowing users to toggle captions on and off, enable automatic captioning, or select English captions.
- Other options include "descriptions" and "chapters," which provide text files listing video sections. Platforms like YouTube and Vimeo allow users to upload caption files, making content more accessible and potentially increasing audience base. By including captions, content can be more accessible and inadvertently grow.

Embedding Media via Iframes
- Embed complex content from services like Google, CodePen, or Speaker Deck onto a website using someone else's toolkit.
- HTML knowledge is not necessary, but understanding the iframe element and its attributes can help. Security issues should be considered when using content management systems like WordPress or Drupal.
- Consult someone who knows how to use CMS effectively for embedding YouTube videos. When building a website, consider security aspects related to the iframe element, ensuring not all iframes are allowed without considering security measures.

Unit 7: HTML Content Identifications

HTML Language Support
- In HTML, it is crucial to indicate the language of a webpage to ensure search engines understand the language it is processing.
- The lang attribute is used to specify the language of a webpage, which can be set on the main element that wraps everything else, usually the HTML element.
- It has many options to indicate language or regional versions of a language, as well as other qualities like the writing system used. If a webpage has multiple languages, specify the language for each part of the content.
- The dir attribute can be applied to any element to indicate the direction of the content. When there is a mix of content, ensure to indicate the change in direction for each phrase.
- The charset for your project is also important, as each language uses its own set of characters or alphabet. Unicode, particularly UTF-8, is widely used to encode content to support a vast range of characters, scripts, and emojis. To specify the charset in HTML, include a meta charset tag equal to UTF-8 within the head element on every page of the website.

HTML Generic elements, Div and Span
- HTML elements like div and span are useful when an element is needed that doesn't exist. Divs and spans were heavily used before HTML5 introduced semantic elements, but they are not good practice and can negatively affect users.
- Instead, developers should opt for the appropriate HTML element that serves the purpose. Divs are block-level elements, while spans are inline elements that do nothing until CSS or Javascript is applied.
- Similarly, an inline element can mark a specific phrase in a text. Both div and span can use global attributes like class, id, lang, and aria roles. Div and span are useful when there is no other suitable element, but should be used wisely.

Unit 8: HTML Integration

HTML Page
- HTML files are essential for creating websites and web apps. When a user visits a website, they enter a URL and the web server sends a specific HTML file
- In the past, everything needed to display a webpage was contained in a single HTML file, along with images. Today, the process of the web remains the same, with text stored in databases, multiple static files combined in real-time, and additional files for images, video, audio, and ads.
- The structure of the HTML file is crucial, with the build system or CMS having templates or theme files that determine what gets sent. The HTML file should begin with a doctype statement, indicating the era of the HTML file.
- The HTML element, which contains all content, is enclosed within an HTML element, with the opening and closing tags at the top and bottom. The head and body elements are used to create the content, with the head containing metadata and the body containing content.

Document Head
- The head of a webpage contains crucial information for the browser, such as the character set and the title element. The meta element is used to provide metadata about the page, such as setting the character set to UTF-8.
- The title element is required on every webpage and appears on the browser tab or bookmark when saved. The meta element informs the browser that the layout has been adjusted to fit small screens, making the page responsive.
- It also includes a description of the site, assigns a name to the webpage when saved to the home screen, and specifies a tile image and background color. The link element connects assets like CSS files, fonts, and favicons, with the rel attribute indicating the asset type.
- The href attribute specifies the URL for the asset, and the script tag instructs the browser to load a JavaScript file.

Content Structuring
1. Main
  - The main element is used once per webpage and tells the browser where the main content is located
2. Header
- Header and footer elements indicate page areas, while header is file metadata, used for site, article, and content headers, typically at the top of web pages.
3. Footer
  - The footer signifies that there are extra things to convey, regardless of its position on the page.
4. Article
- Article elements include title, subtitle, author's name, publication date, footer, and metadata. They wrap around content units like articles, snippets, teasers, tweets, or apps.
5. Section
  - The section element is utilized to mark content sections, such as long essays with subheadings, and to divide different topic zones on a website, starting with a headline.
6. Aside
  - The aside element is used for sidebar information or additional details, transferring meaning from the design to the content, regardless of its position on the page.

When it all comes Together
- Web pages consist of hundreds of nested elements, each conveying meaning and playing off the other.
- To mark up a page, explore the web, find similar sites, and use developer tools.
- The correct way to combine HTML elements depends on the content and page purpose. Structuring HTML is an art, with creative freedom and the goal of representing human communication in code.

Unit 9: Working with Forms and Interactive Elements

Form Fundamentals
- Form fields are crucial for various web tasks, such as logging in, making purchases, and adding content. Using semantic form elements in HTML allows us to leverage the built-in power of the browser and ensures compatibility with all devices and input/output hardware.
- To create a simple form for an email newsletter, start with the form element, which informs the browser about the presence of a form using opening and closing tags. Use the input element to provide places for users to input their name and email, which acts as a marker for the browser to bring in functionality.
- A button is needed for users to submit the form. To make it accessible, add a "for" attribute to the label that matches the "id" attribute of the input or wrap the input with the label. Test the connection by clicking on the label to ensure focus jumps to the corresponding input.

More Form Functions
- The task is to create a form for collecting name and email addresses for email newsletter sign-up. The input elements currently collect text, but the browser needs to determine the required input type. To fix this, add the type attribute to each input, indicating that type equals text for the name field and email field. The browser will verify that the data entered is an email, and warn users if they type anything other than an email.
- Inform the browser that the button is a submit button and add a required attribute to make the email feel required. The browser will insist that the user fills out the email field before the form can be submitted.
- Add a placeholder or default value to pre-populate the field with real content, such as email addresses. This helps users understand what to do and avoids the need to manually erase the suggested text.
- In summary, creating a form with input elements that collect name and email addresses is crucial for effective email newsletter sign-up.

Other Form Element Types
- A form is a basic structure that can be customized using CSS and semantic HTML elements to create a custom look and feel. It can be used to collect various types of data, such as passwords, search, and phone numbers.
- The password field is set to password, search to search, and phone number to tel.
- Some browsers may display an integrated password manager for faster password input. The search field may have a different keyboard layout, and the phone number field may prompt a telephone pad for input. To collect larger passages of text, the text area element should be used, and the browser provides interfaces for both.
- Input types include date, color, and file. The date input type allows for date setting, while the color field opens a color picker. The file field allows uploading a file. A select list can be created using select and option elements, and checkboxes or radio buttons can be set to checkbox or radio.
--------------------------

With the summarry of the current units done i then proceeded to complete the tutorial video for the rest of the day.

Day 2: In day 2 i decided to begin working on the website for my groups project. I started with the home page that will have a navigation bar, a video and an about us section. Me and my group originally decided on a hotel booking system and then decided to change it because more groups were doing the same thing. We changed to a restaurant website that will let the user book a table or ask for delivery.

Close to the evening i created the home page as well as the menu for the website. For now me and my team decided to focus on the delivery aspect of the website. I then pushed the project to github so everyone else can have access to the project.

Day 3: Coming back to the office the team created a login and registration page for the website. After looking at the improvements with the website, we held another group meeting and talked about what would be added. After talking about what to add, i then volenteered to create the power point for the presentation and i spent the whole day looking for a good presentation to create and help with bug fixing.

Day 4: Today we ran into a problem with push and pulling commits from git hub but apon further inspection it was a device error because everyone else in the group could submit so that problem was sorted after helping set the person up on local computer. The i spent the rest of the day creating the power point.

Day 5: Today the gourp and i finished up the website and began working on what we were going to say, luckily the presentation was moved to monday so we had more time to practice. While my group members worked on what to say for the presentation i kept working on the power point eager to finish it today.
