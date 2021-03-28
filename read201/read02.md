# HTML

- Structural markup: the elements that you can use to describe both headings and paragraphs
- Semantic markup: which provides extra information; such as where emphasis is placed in 
a sentence, that something you have written is a quotation (and who said it), the
meaning of acronyms, and so on
HTML has six "levels" of
- headings:
- h1 is used for main headings
- p
To create a paragraph, surround the words that make up the paragraph with an opening p
tag and closing /p tag.
- b
By enclosing words in the tags <b> and </b> we can make characters appear bold.
- i
By enclosing words in the tags <i> and </i> we can make characters appear italic.
- sup
The sup element is used to contain characters that should be superscript such
as the suffixes of dates or mathematical concepts like raising a number to a power such
as 22
- br 
As you have already seen, the browser will automatically show each new paragraph or heading
on a new line. But if you wanted to add a line break inside the middle of a paragraph you can
use the line break tag br 
- hr 
To create a break between themes — such as a change of topic in a book or a new scene
in a play — you can add a horizontal rule between sections using the <hr /> tag.
- strong
The use of the strong element indicates that its content has strong importance.
For example, the words contained in this element might be said with strong emphasis.
By default, browsers will show the contents of a strong element in bold.
- em
The em element indicates emphasis that subtly changes the meaning of a sentence.
By default browsers will show the contents of an em element in italic.

- blockquote
The blockquote element is used for longer quotes that take up an entire paragraph. Note
how the p element is still used inside the blockquote element.
Browsers tend to indent the contents of the blockquote element, however you should not
use this element just to indent a piece of text — rather you should achieve this effect using CSS.
- The q.
 element is used for shorter quotes that sit within a paragraph. Browsers are
supposed to put quotes around the q element, however Internet Explorer does not —
therefore many people avoid using the q element.
- the abbr : 
If you use an abbreviation or an acronym, then the abbr element can be used. A title
attribute on the opening tag is used to specify the full term.
- cite
When you are referencing a piece of work such as a book, film or research paper, the
cite element can be used to indicate where the citation is from.
In HTML5, cite should not really be used for a person's name — but it was allowed in
HTML 4, so most people are likely to continue to use it.
- the dfn
The first time you explain some new terminology (perhaps an academic concept or some
jargon) in a document, it is known as the defining instance of it.
The dfn element is used to indicate the defining instance of a new term.
The address
The address element has
quite a specific use: to contain
contact details for the author of
the page.
It can contain a physical address, but it does not have to. For example, it may also contain a
phone number or email address.
ins
del
The ins element can be used to show content that has been inserted into a document, while
the del element can show text that has been deleted from it.
The content of a ins element is usually underlined, while the content of a del element
usually has a line through it.
- s
The s element indicates something that is no longer accurate or relevant (but that
should not be deleted).
Visually the content of an s element will usually be displayed with a line through the center.


Introducing CSS :
CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that
element should look
Internal CSS
by placing them inside a < style > element. (< style type="text/css" > code < /style>)

External CSS
The element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It should use three attributes:

href specify the path to the CSS file.
type specify the type of document being linked to.
rel specify the relationship between the HTML page and the file it is linked to.
- {} = Applies to all elements in the document
h1, h2, h3 {} = Matches element names
- .note {} = Matches an element whose class attribute has a value that
matches the one specified after the period (or full stop) symbol
- #introduction {} = Matches an element whose id attribute has a value that
matches the one specified after the pound or hash symbol
- li>a {} = Matches an element that is a direct child of another
- p a {} = Matches an element that is a descendent of another specified
element (not just a direct child of that element)
- h1+p {} = Matches an element that is the next sibling of another
- h1~p {} = Matches an element that is a sibling of another, although it
does not have to be the directly preceding element



java script: Comments used in JavaScript to explain what the code does, and can be written in two ways:

/* Multi-Line Comments */
// Single-Line Comments
Variables (var): The containers for storing data values

Data types
Numeric for numbers
String for letters and characters
Boolean for true or false
Declaring variables and assigning them values can be written in different ways:

Declaring variables and assigning values in the same statement.
Declaring variables on the same line, then assigning values to each.
Declaring some variables on the same line, then declaring others and assigning a value on the next line.
Naming variables rules:

The name must begin with a letter, dollar sign ($), or an underscore (_). It must not start with a number.
The name can contain letters, numbers, dollar signs ($), or an underscore (_). A dash(-) or a period (.) in a variable name must not be used.
Keywords or reserved words cannot be used.
The capital letter differs from the lowercase letter.
Variable name should describe the kind of information that the variable stores
"Camel Case" is a recommended way to write variables containing more than one word


