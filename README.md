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
----------------------------------------------
#Week 3
Day 1: The whole of Monday the whole of capaciti ABSA did their presentations infront of the invidulators and other groups as well as demoing their websites.

Day 2: For today we got a teams message saying that we need to learn unit 10-11 for into to HTML as well as starting into to CSS units 1-3. We will also be doing out second assessment this friday from units 5-9. The invidulators would also like us to touch on units 10-11 and to start HTML & CSS intermediate Units 1-3.

# Summarry of Units

Unit 10: Organizing Tabular Information in HTML

HTML Tables
- HTML tables are not evil and should be used for tabular data. However, misuse of table elements is not acceptable. The purpose of semantic HTML is to communicate with computers, so use button elements for buttons and table elements for tables. The fear of HTML tables stems from the scrambled messages.
- During the early days of the web, there was no proper tools for styling or layouting content. People used to typeset headlines in Photoshop and export them as images, but this was not an actual headline. Instead, they used HTML tables to break up content into pieces, which was a terrible hack due to its lack of accessibility and reusability. HTML email still uses this technique, but it is not the best use of tables. Instead, they should be used for tabular data.
- A data table is a chart of information that is best communicated by aligning it into rows and columns. It is used for comparing prices, population data, election results, product comparisons, and schedules. The data can be numbers, text, images, or other types. Tables in HTML help convey relationships between data cells and header cells, making it more clear and concise. CSS can be used to rearrange table display and layout for different screen sizes. If the information is inherently a table, then use an HTML table.

Building HTML Tables
- To create a HTML table you need to use several elements in just the right combination. Table, TR, TH, RD
- The table element wraps around the whole table, all the content and markup of the table, making it the beginning and end of the table. The TR element stands for table row and it wraps around a set of elements defining them as belonging to the same row. The TH element stands for table header and defines the header for each column. The TD stands for table data and marks up the cells of data.
- A table with six rows and five different birds is created using the TR element. The content is placed inside each row, with the American goldfinch being the first bird. The TD element wraps the content and image, and any HTML markup is placed inside. The table has four columns, with data in each row.
- To make the table look more like your choice, add styling and CSS to the header content. Place the content in the first row, wrapping each in a TH element instead of a TD element. Use CSS to change the header's appearance, ensuring proper pronunciation and easy style changes for the table.

Unit 11: Course Project - Build Your Personal Portfolio
- The "Build Your Personal Portfolio" project offers aspiring web developers a hands-on experience to enhance their HTML and CSS skills by creating a personalized portfolio website, serving as an online resume for potential employers.

Part 01:Introduction to HTML
- This part gives a scenerio and how you would go around creating the poe.
- The scenerio is A web developer creates a personal portfolio, including bio, skills, projects, and contact information. HTML structure, images, clickable links, and interactive forms for visitor feedback are essential. To go about doing this you will need to know the basics of HTML and then implement CSS.
- Objective Design

1.  Understanding HTML Syntax:

a. Create a basic HTML document with necessary structure.

b. Use various HTML elements to structure content effectively.

2. Formatting and Styling in HTML:

a. Apply formatting options to text content.

b. Implement inline and block-level elements for proper styling.

3. Incorporating Images and Hyperlinks:

a. Embed images and provide alternative text.

b. Create hyperlinks to external projects and resources.

4. Utilizing Global HTML Attributes:

a. Apply global attributes such as 'class' and 'id' for styling and identification.

5. Developing Navigation Menus and Forms:

a. Create a navigation menu using lists.

b. Construct interactive forms for user engagement.

6. Organizing and Structuring Content:

a. Understand and implement semantic HTML elements.

b. Organize content with proper document structure.

7. Constructing Tables:

a. Build tables to display project or skill-related data.

- This project teaches learners to create a functional personal portfolio website, showcasing their skills and work. It includes a professional bio, skills display, completed projects, and contact form. This project enhances their understanding of HTML and CSS.

Moduale Summary:

Re-cap Intro to HTML
- The module concludes with a reminder of the ongoing evolution of HTML and the abundance of online resources available for further learning and quick reference.
- <b>MDN Web</b> docs provides authoritative HTML reference documentation, including element and attribute descriptions, code examples, browser support charts, and links to specific technologies. It also offers advice on combining HTML elements for specific use cases and content types.
- <b> HTML Specifics</b>
 The specification is the canonical source of truth about any web technology, including HTTP, URL, HTML, CSS, and JavaScript. It is created by a group of people who collaborate on a plan for each technology. These decisions are documented in official documents called specifications, which are closely followed by browser engineers when adding new features.
The HTML specification, most recently numbered version five, is the current version of HTML. It is constantly changing and may eventually be declared HTML6. Some people argue that the Living Standard, a slowly changing specification without a number, is the current version of HTML. It is available for reading, and a simplified version is available for designers and developers.

- <b> WCAG Guidlines </b>
We also recommend putting some time into learning more about ARIA and accessibility in general. A great place to start is with the WCAG guidelines. W-C-A-G stands for Web Content Accessibility Guidelines. It is the official W3C specification on accessibility best practices. You can read the WCAG specifications or search for WCAG or ARIA to find more resources.

- <b> CSS </b>
We strongly advise you to learn CSS. Knowing both HTML and CSS makes for a powerful combination. HTML does not change very often, so knowing these essential foundations will set you up for a long time.
Trying to memorize everything is futile. We all forget things. Just look it up when needed and do not be embarrassed when you are unsure which element to use or cannot quite remember what an attribute's called. Search the web, look it up, and then get it right. Your projects will be better for it and your users will thank you.
---------------------------------
# HTML & CSS 102 - Introduction to CSS 

Module focus
CSS, short for cascading style sheets, is the language that controls the pretty stuff on websites. This course aims to give you a beginner-friendly introduction to CSS, even if you have no prior experience with it. 

HTML and CSS work hand in hand to create the visual aspects of a webpage. By learning the basics of CSS, you will be able to effectively collaborate and communicate with your developer team. It is recommended to have foundational HTML knowledge before diving into this course.

In this module, you will learn how to:

Apply CSS to your web pages.
Use Selectors.
Manage colors and multimedia using CSS.
Apply the Box Model.
Work with links.

Unit 1: HTML & CSS

What is CSS?
- A style sheet is like a CSS file that holds all the styles for your webpage. This adds visual appeal to your webpage. To connect the HTML and CSS, you simply link them together. HTML and CSS are closely connected and work hand-in-hand but before we dive into CSS.
- HTML recognizes common elements like paragraphs, headings, lists, and links, defining webpage structure. Raw HTML appears ugly in web browsers, but CSS helps improve appearance by changing font, colors, and spacing, making pages readable and understandable.
  CSS has two parts: 
The selector. 
The declaration block
- The selector in HTML matches a pattern, causing styles within the declaration block to be applied to the corresponding elements, with cascading in CSS allowing multiple styles.

CSS Components
- In CSS, each style decloration consists of two parts: A property and a value.
- This course focuses on select properties and values in CSS, emphasizing the importance of the selector in HTML. Initially, unattractive web pages will be created, but by the end, pages will improve with the incorporation of key styles.

Unit 2: Adding CSS Sectors
Writing Your First Comment and Element Selector
- CSS selectors are used to create styles for various elements on a page. The first type is the element selector, which can be used to select paragraphs and make them blue.
- For example, to make all H2s red, the selector "H2" can be used. To create styles for heading one (H1) and heading three (H3) elements, choose any desired colors for each text. To learn more about CSS selectors, refer to the 01-01-End state of the Sublime Text in your Exercise Files.

Writing a class sector
- You can assign classes to HTML elements to create a reference point for styling. A class is an attribute that can be added to any HTML element, providing additional details about that element.
- To style a paragraph, add a class attribute to the paragraph tag and give it a name like "intro" to make it stand out. In CSS, use a dot (.) before the class name to differentiate it from HTML element selectors. For specific paragraph parts, use a span element with a class attribute, like "guarantee" to make the sentence orange and bold. In both cases, set the color and font-weight accordingly.

Grouping selectors
- If i want to make a certain item green i could do something like this "li {green}", but if i want to make more then 1 item green then i need to combine the "p" and "li" , "p li {green}"and it will apply it to all paragraphs even list.
- If we want to be more specific on the type of color we want the text to be then we need to  specify it, For example: if we want to make the text mineral green then we would add ,.mineral to the sector where .mineral is the class then in a HTML we specify by adding "spanmineral" mineralwater </s pan" his will make the word "mineral water" green too. So whenever you see selectors grouped together with commas, it means each of those items is a separate selector. Whether it is paragraphs, list items, or anything with the class "mineral," the text will be styled as green.

Decendent sectors
- The first list is an ordered list with mineral water as the main ingredient, with minimal natural raspberry flavor. The second list is an unordered list with different flavors. To style, group paragraphs, list items, and elements with "mineral" class, style ordered items blue and bold, and unordered items purple and uppercase.
- A descendant selector allows us to select list items that are descendants of either an ordered or an unordered list. The relationship can be direct or indirect, similar to a family tree.
- To apply styles using a descendant selector, use the code "OL LI" without the body tag. Set the color to blue and font weight to bold, affecting only list items in the ordered list. Remember to read CSS selectors from right to left, as they are read from left to right.
- Create a style that selects list items in the unordered list and makes them purple and uppercase. Check the code pen's final state in the exercise files for accuracy.

Unit 3: CSS Images ad Colors
 Identify a Color Scheme
 - Color palettes are essential for selecting a color scheme or specific colors for a website. If you have a design background, you can create one yourself. If you struggle with color choices, resources like Canva and Google's color palette generators are available. Canva is a friendly graphic design companion for non-designers, offering three methods for creating color palettes. The first method is displayed at the top of their webpage and can be found in your exercise files folder. Another option is to try their demo image.
 - Explore various color palettes, such as "Rosettes and Cream," to create designs with inspired colors and related combinations. Click on a palette to view a picture and explore options with purple.
 - Clicking the back button allows users to create a custom color palette by selecting their initial color and the system generates a complementary color combination.
 - Users can use color combinations like monochromatic, analogous, triadic, or tetradic to find matching colors. They can adjust color saturation or try variations. If using the color wheel is too advanced, users can browse available palettes categorized by keywords or upload images to generate a color palette.

Formatting Colors CSS
- The color chart provides examples of named colors, but your color palette may not have any. If the desired color doesn't have a name, hex codes, also known as hex values or hex format, are the most common online representation.
- Hex values are typically six-digits long and consist of numbers zero to nine and letters A to F. The first two digits represent red, the next two represent green, and the final two represent blue. These digits correspond to numbers ranging from zero to 255.
- RGB format uses Base 10 numbers to represent colors, including red, green, and blue, and can be represented as RGBA or RGBA. Alpha represents opacity and transparency, determining color visibility. Other color formats like HSL or HSLA may also be used.

Background and Text Colors in CSS
- We can also change the background color for elements. By using the "background-color" property and specifying a hex color, color the background behind specific elements. For readability, adjust the text color as well. For instance, set the text color to white using the hex code "FFF" or "FFFFFF" for a white background.
- To style an unordered list (ul), use a beige color from Canva as the background. The "body" HTML element can also be styled with a specific color like yellow. This allows for customization of the entire page's background color. You can select colors from the named color palette or create custom colors using Canva.

Understanding Images in CSS
- Images are frequently found on webpages. They can be added either in HTML or CSS. Firstly, we will discuss the image formats suitable for the web, and then explore how to include images using HTML and CSS.
- There are various image formats, like GIF, PNG, JPEG, bitmap, TIFF, and more proprietary formats like PSD. Traditionally, the web has supported three types of image formats. 

GIF:  Had limited colors but could include transparency and animation. 
PNG:  Had more colors and transparency but no animation. GIF and PNG were suitable for illustrations such as logos or cartoons. 
JPEG:  Stands for Joint Photographic Experts Group, was optimized for photographs and supported millions of colors but lacked transparency and animation

- WebP is a new image format that offers high compression for smaller file sizes, resulting in faster website loading times. It is expected to grow in popularity due to its versatility and efficiency in loading photos and illustrations quickly.
- To optimize image downloads, it is important to choose the right format, such as GIF, adjusting dimensions, trimming or cropping unnecessary parts, and resizing. Images taken directly from mobile phones or cameras are usually large and take longer to download.
- Tools like tinypng.com or Adobe Photoshop can be used to reduce image file sizes, improving website loading speed and user experience. Images can be included in webpages using HTML and CSS.
- HTML uses the image element to place images alongside text, while CSS allows for background images, which are decorative and not essential to the webpage's text.
----------------------------
Day 3: Today i was doing HTML & CSS exercise in freeCodeCampe and i continued this for the whole day.
Day 4 - 5: during the last 2 days i have just been doing excersises in freecodecamp and studying for the assessment we did on friday.
----------------------------------------------
# Week 4
Day 1: Today i am going to do summary on units 4 - 6 in the CSS and then i will focus on building my portfolio and improve on my teams website.

# Summary of units
Unit 4: CSS Boxes, Types and Sizes
Understanding Type in CSS
- In general, people who are not designers usually categorize fonts into two types: 
1.Serif.
2.Sans serif.
- Serif fonts have small lines at the ends of the letters called serifs. In the past, serif fonts were used for printed materials with long text blocks. When letters were manually set on a printing press, they were never perfectly aligned. The serifs helped connect the letters, making the text easier to read.
- Sans serif fonts have a modern appearance and are commonly used on the web for extended text due to their clean and easy-to-read appearance. The default font on the web is usually Times New Roman, but this depends on the font's source and device compatibility.
- To ensure compatibility, font stacks are often specified, including Arial, Helvetica, and sans serif. Other fonts safe to call from user devices include Verdana, Times, Times New Roman, Georgia, Trebuchet MS, and Comic Sans.
- Google offers over a thousand fonts for website use, sourced from the internet and loaded into the web browser. This course focuses on basic fonts on user devices. In real-world scenarios, development teams guide on font stacks in CSS.

Applying Type Formatting with CSS
- To improve the appearance of a webpage, add a font-family property to the body element and use a font stack of Arial, Helvetica, and Sans-serif.
- The web browser will evaluate these fonts in order, and if neither is available, the default Sans-serif font will be used. When Arial is removed, the plus sign shifts slightly, indicating Helvetica is the default Sans-serif font.
- It's important to note that perfect control over fonts across all devices is not necessary. Using multiple fonts can make the page look professional, and headings can be contrasted with a different font.
- Using multiple fonts on a page can enhance its professionalism and contrast headings with a different font across all devices.

Understanding and applying Size in CSS
- Web design uses absolute and relative sizing. Absolute sizes remain constant, while relative units adjust based on page size. Web designers prefer relative units for flexibility, as font sizes scale proportionally with the page.
- Web developers prefer the "rem" font size unit, which is equivalent to 16 pixels. Multiplying a font size by 16 yields a pixel size of approximately 24 pixels, while 0.8 rem is roughly 13 pixels. Online calculators can help with these calculations.
- The Point to REM Converter tool on codebeautify.org converts web design sizes to pixels, a useful tool for those preferring points in print design, allowing conversion between web and print units.

Understanding Box model in CSS
- HTML elements are like boxes with properties, including content, border, padding, and margin. Content is the text inside the box, while border is a line surrounding the content. Padding is the space between the border and content, with its own background color.
- To add a red border to a slide, use the CSS property "border: 1px solid red". For margins, use "margin: 1rem" to add one root em (root em) to all four sides, or "margin-right" to add the margin to the right side. Padding provides flexibility with fractional REMs for all or only one side.

Working with Border, Padding, and Margin in CSS
- The text discusses the issues with an image added to a page, including incorrect background leaves and spacing problems. To address these, the body element's default margin is set to zero, and the leaves are positioned 97% down the page.
- A footer element is added, and the background image is moved from the body to the footer. The headings have margins, but the text looks cramped against the edges.
- To create space, the padding property is used, and a decorative border is added at the bottom. The H2 and H3 headings have separate margins, and the top margin is set to zero and padding is added.
- The image is centered within a paragraph with a class of "circle" and the text-align property is set to center.
- The border-radius property allows for rounded corners, and the text-align property is set to center.
- By applying these CSS modifications, the page looks better with minimal CSS, allowing for a well-designed page with proper spacing and fonts.

Unit 5: Advanced CSS Properties and Concepts

Styling links with CSS
- Chrome's guest tab doesn't show visit history for certain courses, making links appear unvisited. To fix this, use HTML and CSS to style links. Specify a color code like dc267f to change text color, but links remain default blue. Use the "a" anchor tag to target links and set the color to 648fff, a nicer blue color. This will apply to all links, including visited ones.
- The "a:hover" state triggers when a link is hovered over, allowing color changes and underline removal. This feature was previously unavailable. To separate styles for visited and unvisited links, define blue as the "a:link" style for unvisited links and purple as the "a:visited" style for visited links. The hover style remains intact.
- In general, when you have links within long text, it is important to keep the underlines. This is especially helpful for people who may be colorblind or have disabilities that make it difficult for them to differentiate between the link and the surrounding text. However, if your links appear in a navigation bar or any other area where users expect to click and be redirected, you can remove the underlines in those specific situations. These are just a few simple tips to style your web page links in a visually appealing way.

Inheritance in CSS
- The text describes the process of styling a web page using Arial, Helvetica, and sans-serif fonts. The "body" element is set to Arial, and all HTML elements within it inherit the same Arial font.
- This is because font-related styles typically inherit, preventing a mishmash of different fonts. However, styles related to the box model, like borders, apply only to the specified element in the style.
- For example, using a selector "*" to select all elements on the page and apply the border to it instead of the body results in a chaotic web page.

Debugging CSS with borders and background colors
- To style an element, add a background color or border to reveal hidden information. For example, an unordered list (UL) can be styled with a border to display its full width, revealing its position on the page.
- The link within a list item (LI) is only as wide as its content, highlighting the distinction between block and inline elements. Block elements, like UL and LI, take up the full width of their container, while inline elements, like links (A), are only as wide as their content.
- To apply a hover effect to the LI, change the link to an LI (list item) and apply the "LI:hover" selector. This will cover the entire document width, allowing clicking only when hovering over the A element. To fix this issue, add the CSS style "display: block" to the A selector and define a hover state for the link.
--------------------------------------
