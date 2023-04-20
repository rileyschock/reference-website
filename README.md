# reference-website
1. Naming conventions for all filenames, paths and folders
    - The naming conventions for all filenames should be lowercase with no spaces, however dashes are accepted. Path naming conventions should have the folders, assests and files inside the root folder for simple linking inside any .html files. Folder naming conventions should be similar to filenames.
2. Best practices for commit messages
    - Commit messages should have a minimum of 3 words and 10 characters, with proper spelling and grammar throughout. Commits should be written starting with a capital letter, an imperative verb, and no periods at the end.
3. What is HTML?
    - HTML stands for HyperText Markup Language, and is the standard language used in the creation of web pages. Markup symbols and code inserted into a .html file are intended to be displayed on the internet, which tells web browsers how to display various words and images.
4. Proper syntax for HTML tags
    - The tags used to define the purpose of text on a web page are composed from special characters: <, > and /. The proper tag syntax starts with a specific word or letter surrounded by angle brackets, then in between is its content, and ends with a forward slash and the same word or letter surrounded by angle brackets.
    - Ex: <p>This is a paragraph</p>
5. Explain or demonstrate commonly used html tags/elements:
   headings: <h1> <h2> <h3> <h4> <h5> <h6>
    - HTML heading tags are defined from h1-h6 and are used to display headings based on importance on the web page, h1 being the most importance and largest heading, and h6 being the least important and smallest heading.
   p: <p>This is a paragraph</p>
    - Paragraph tags are used to define a paragraph of text. It is a block-level element, meaning it always starts on a new line of text. There is spacing before and after each paragraph since all browsers add margins by default.
   lists: <ul> <ol> <dl>
    - In the HTML language, lists are used to display data in a structured format, and there are 3 types of lists in total: unordered lists (ul), ordered lists (ol), and definition lists (dl).
    - Unordered lists, or <ul>, is a list of items where the order of the items does not matter, and are typically displayed using bullet points.
    - Ex: <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
          </ul>
    - Ordered lists, or <ol>, is a list of items where the order of the items does matter, and are typically displayed with numbers.
    - Ex: <ol>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
          </ol>
    - Definition lists, or <dl>, is a list of items that consists of a term and its definition.
    - Ex: <dl>
           <dt>Term 1</dt>
           <dd>Definition 1</dd>
           <dt>Term 2</dt>
           <dd>Definition 2</dd>
           <dt>Term 3</dt>
           <dd>Definition 3</dd>
          </dl>
   a: <a href="URL">Link Text</a>
    - The <a> element is know as an anchor tag, and is used to create hyperlinks or anchor links which then defines a clickable link that allows users to navigate to another web page, a different section of the same web page, or any other URL.
   img: <img src="image_url" alt="image_description">
    - The <img> element is used to embed images into a web page. It allows users to display images, from photographs, to illustrations, and icons.
   q: <q>This is a quotation</q>
    - The <q> element is used to define an inline quotation and is used to enclose a short piece of text that is a direct quotation from another source.
   blockquote: <blockquote>This is a blockquote</blockquote>
    - Used to define a block-level quotation, blockquotes are an HTML elementused to enclose a longer quotation displayed as a separate block of text to distinguish it from the surrounding text.
   cite: <cite>Title</cite>
    - The <cite> element creates a reference to creative work, such as books, movies, or articles. Depending on the default or applied styles of the web page, it will normally display this title in italics.
   em: <em>Emphasized Text</em>
    - Text that is to be emphasized on a web page is done so by using the <em> element, which normally renders it in italics. It is often used to indicate that the specific text has special significance.
   strong: <strong>Strong Text</strong>
    - Text that is to be strongly emphasized on a web page is done so by using the <strong> element, which normally renders it in bold text. It is often used to indicate that the specific text has strong importance.
   b: <b>Bold Text</b>
    - the <b> element is used to define text that is to be displayed in bold.
   i: <b>Italicized Text</b>
    - the <i> element is used to define text that is to be displayed in italics.
   small: <small>This text is small</small>
    - Small text on a web page is generated by using the <small> element, which displays a smaller font size relative to the surrounding text.
6. Explain block Elements and the list of block elements and why they are used:
    - In HTML, block-level elements are used to create structure in the document, or containers that start on a new line and take up the full width of their parent container. Some examples of these block elements are:
   html: <html lang="en">
    -  The basic structure and language of an HTML document starts at the <html> tag. It is the root element that defines the beginning and end of an HTML document, and is the top-level element over all the other elements on a web page.
   head:<head>
         <title>My Website</title>
        </head>
    - The head section of an HTML document contains meta-information about the document, such as the title, characters, and CSS styles. The contents of the <head> element are not displayed on the web page, but are used to provide important information to the browser and search engines.
   body:<body>
         <h1>Hello, world!</h1>
         <p>This is a website.</p>
        </body>
    - The main content of a web page is defined in the <body> element. It represents the content that is visible on a web page, such as text, images, videos, links, and other HTML elements.
   header: <header>
            <h1>My Website</h1>
            <nav></nav>
           </header>
    - Introductory or navigational content that appears at the top of a page, such as a site logo, a site title, and a navigation bar are usually found in the <header> element of an HTML document. This element is placed within the <body> of a web page.
   nav: <nav>
          <ul>
           <li><a href="#home">Home</a></li>
           <li><a href="#about">About</a></li>
           <li><a href="#contact">Contact</a></li>
         </ul>
       </nav>
    - The <nav> element in HTML is a semantic element used to create a navigation menu on a web page. It is commonly used to group together a collection of links or menus that facilitate navigation between different sections or pages of a website.
   main:
    - The <main> element is utilized to markup the primary content of a web page, including articles, sections, or any other content that holds the main focus of the page.
   section: <section>
             <h2>Section Title</h2>
             <p>This the section content.</p>
            </section>
    - A <section> in in HTML is a semantic element that is used to group related content together and represent a section of content in a web page. The <section> element is normally used with elements such as <article>, <header>, and <footer> in an HTML document.
   article:
   div: <div>This is the div conent.</div>
    - A generic container used to group and organize content within a web page is called a <div>, or division. Similar to the <section> element, it groups related content together however it has no semantic meaning, and is specifically for organization purposes.
   aside: <aside>
           <p>This is a related paragraph</p>
          </aside>
    - To represent content that is related to the content around it, the <aside> element can be used, which provides additional information or content that is not necessarily essential to the main content of the page but is still related to the web page.
   footer:<footer>&copy;Riley Schock 2023</footer>
    - The footer on a web page is representative of the bottom section, which normally contains metadata, copyright information, contact details, or similar content intended to be displayed at the bottom of the page.
   span: <p>This is a <span style="color: green;">green</span> paragraph.</p>
    - The <span> element is used for styling purposes to a specific section of text or inline content. Normally it is used for content such as applying CSS styles, and adding inline formatting.
7. Explain why accessibility is important and also explain the accessibility properties:
    - Accessibility is crucial when coding in HTML, since it ensures that web content is perceivable, navigable, useable, and most importantly understandable by as many people as possible, taking into account those with disabilities and/or impairments. Some examples of accessiblity properties include:
   landmark roles:
    - These are used to define different sections of content in a web page, providing structure and improving accessibility. For example, <header>, <nav>, <main>, and <article> are all landmark roles.
   aria labels:
    - Aria stands for 'Accessible Rich Internet Applications', and are attributes particularly for elements that do not have specific accessibility semantics. They provide additional information about the accessibility of web content for users with disabilities. For example, <a href="#" aria-label="Learn more about this content">Read more</a>. In this case 'aria-label' is used as an alternative to the visible text for the element.
   image alternative texts: <img src="image.png" alt="A bouquet of flowers sitting on a bedside table">
    - Image alternative text, or 'alt', is a description that is associated with an image, and by using the 'alt' attribute, it provides the image with a descriptive alternative in case the image cannot be displayed, or if an individual accessing the page has a disability or impairement.
8. What is CSS and how can we implement CSS to our html file?
    - CSS stands for Cascading Style Sheets and is a stylesheet language used for the presentation and styling of HTML documents. This language allows web designers to control the appearance of web pages such as font, color, margins, and padding. 
    - To implement CSS in an HTML file, you can use the following steps:
     1. Create a separate text file with a .css extension that will contain your CSS rules called "styles.css".
     2. In your HTML file, use the <link> element in the <head> section to link your CSS file to the HTML document. The href attribute should contain the file path or URL of your CSS file. The html file should have this text embeded: <link rel="stylesheet" href="styles.css">
9. What is the difference between CSS property and value?
    - A CSS property specifies the aspect of an element's style that you want to control. It is associated with a specific property name, and it determines what aspect of an element's appearance or layout you want to modify. An example of this is setting the font size in the header to 20px:
     header {
      font-size: 20px;
     }
    - A CSS value is the assigned value for a CSS property. It specifies to what length you want applied to a property. An example of this is setting the colour of the header to red using a CSS value:
     header {
     color: green;
     }


