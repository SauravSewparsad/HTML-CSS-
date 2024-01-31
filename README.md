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


Unit 5: HTML Working with Graphics and Images

<b>Images:<b>
-
