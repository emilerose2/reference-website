# reference-website


1. Naming convention for all filenames, paths and folders
-No spaces are allowed. Only "-" "." "_" are allowed.

2. Best practices for commit messages
-Minimum 3 words & 10 characters
-Proper spelling & grammar
-Capital starting letter, no period
-Must start with an imperative verb: Create, Fix, Add, Solve, etc.
-Pretend every commit starts with the phrase: “This commit will…”

3. What is HTML?
-HTML stands for the HyperText Markup Language which is the standard format to display documents in a web browser.

4. Proper syntax for HTML tags
-starts and ends with "<" ">"
-Often uses "/" 

5. Explain or demonstrate commonly used html tags/elements:
(headings: h1-h6) - h1 defines the most important heading of the page while h6 defines the least important. There should only be one h1 represented per page. 
(p) - P represents a paragraph used to group related content.
(lists: ul, ol, dl) - ul is used when creating a listing in unordered fashion, while ol is used when creating an ordered list such as in numeric fashion. dl represents definition lists which are used to group terms with their definitions. 
(a) - "a" is used to define a hyperlink which will link to another page or website.
(img) - "img" is used to embed an image.
(q) - "q" is used to define a quotation.
(blockquote) - "blockquote" is used when the quotation is from another source.
(cite) - "cite" is used when tagging creative work such as music, books, movies, etc.
(em) - "em" is used to imply emphasis within text. 
(strong) - "strong" is used for context with strong importance and typically displayed in bold.
(b) - "b" is used to indicate bold text without any importance 
(i) - "i" is used to display text with a different style or mood, often displayed with italic 
(small) - "small" is used to display smaller sized text, often used for side comments and copyright logos.

6. Explain block Elements and also explain the list of block elements and why they are used from below: 
(html) - HTML is the standard language structure for creating webpages, and alows you to publish live online using this format.
(head) - Head is placed between HTML and Body and is a element container for matadata
(body) - Body tag defines where all of the pages content is kept, such as paragraphs, images, headings, etc. 
(header) - Headings are used to divide and represent introductory content.
(nav) - Used to define a set of navigation links.
(main) - Defines the main content of the webpage. 
(section) - Section defines are particular grouping which needs to be divided from itself. 
(article) - Used to identify independant, self contained content on the webpage.
(div) - Used to define a division or section in a HTML document.
(aside) - Aside is content which is undirectly related to surrounding content.
(footer) - Defines the bottom of the content page which usually contains copyright information, contact information, etc.
(span) - Span is used as an inline container to mark up part of a text section.
(small) - "small" is used to display smaller sized text, often used for side comments and copyright logos.

7. Explain why accessibility is important and also explain the accessibility properties like:
-Web accessibility is important because assistive technologies which help visually impaired users guide the web are needed for smooth user web page browsing. 
(landmark roles) - Used to identify sections of a webpage
(aria labels) - Used for providing a label for objects that can be read by assistive technology.
(image alternative texts) - Helps assistive technologie describe images to the reader.

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
-CSS, standing for "Cascading Style Sheets" is the language which allows you to structure your code in a organized layout fashion. To implement CSS you must link CSS with your HTML. CSS is used to for the presentation of displaying fonts, colors, and the general arrangement of text and images.  

9. What is the difference between CSS property and value (write explanation and an example code)
-In CSS property is the aspect of a selector such as selecting the color, line-height or letter-spacing. Where as for value it specifies the value type, such as RGB, hex, length and %. 
-an Example of this is;
p {
    color: red;
} 
("color" being the property and "red" being the value.)

10. Why do we use border-box property in CSS? 
-Border-box in CSS allows the browser to calculate and adjust elements width and height properties using border and padding values. Content will automatically adjust itself to fit within the Border-box values. 

11. Explain different type of ways we can add spacing to an element
-In order to add extra spacing between elements in the CSS page you must apply padding and margin properties. Padding allows you to calculate the distance between content area and border value. Margin helps calculates extra space around an element.

12. What is the main difference between margin and padding?
-The main difference between margin and padding is padding represents the elements inner space between while margin is the exterior space around the elements border. 

13. What are different types of display properties?
-Most notibaly the primary display properties are inline/inline-block, flex/inline-flex, grid/inline-grid and many more. In order to implement grid/flex layouts you must apply these display properties.  

14. Write a brief explanation of flexbox property 
-Flexbox property in short is a layout configuration which allows the user to distribute space between items in a one-dimensional layout using values such as align-items, flex-direction, etc.  

15. What are different types of flexbox properties and what is the major difference between them?
-As briefly mentioned above, the different types of flexbox properties contain, flex, justify and align values. Flexbox allows for fine tuning and each value adjustment varies from box sizes, box order, columns, rows, spacing, and more.

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property
-Flexbox property uses of a parent element such as "nav" and applies values such as "margin" and "padding" to position and precisely space the navigation to the users HTML page.

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
nav ul {
    margin: 0;
    padding: 0;
    list-style: none;
    display: flex;
  }

18. What is CSS grid property?
-CSS grid property is a property which allows you yo set and adjust implicit grid properties, some specifics include; grid-template-rows, grid-template-columns, grid-auto-flow, etc. 

19. Write the parent and two sub-properties used for CSS Grid Property
header {
    grid-column: 2 / 3;
    grid-row: 2 / 3;
}

20. What is the difference between display: flex and display: grid?
In short the difference between flexbox and display-grid is that flexbox allows you to only adjust either a row or a column in your layout, where as display-grid allows you to adjust both rows AND columns simultaneously.

21. What sub-property we use to divide elements in CSS Grid properties?
-To equaly devide sub sections in CSS grid we would use "fr" to represent the amount of times we would devide the grid.  

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)
-To divide a CSS grid we can use a unit of "fr" for example to divide into three it would be; 1fr, 1fr, 1fr. However to make things easier and more organized we can translate that to; 3, 1fr. Here is a code example;
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}

23. What is the area property in CSS grid we use for the child elements?
-In order to start and locate a grid's layout, we can apply to following properties to the child element.
-grid-column-start
-grid-row-start
-grid-row-end
-grid-column-end

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.
-To prevent displaying empty columns you must apply "grid-auto-columns". Here is a code example;
.container {
    grid-auto-columns: 1fr
}

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.
