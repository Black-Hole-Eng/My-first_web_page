"""
This project has helped me learn some basic HTML and CSS.
I created a simple web page with all my information as a portfolio. 

I got to learn that Hyper Text Markup Language (HTML) provides a description of the structure of a web page. 
HTLM elements are formed using tags, which serves as descriptors for each piece of content of the page. 

Some HTML elements include:
- <p></p>: Paragraphs
- <h1></h1>: Highest-level heading
- <h6></h6>: Lowest-level heading
- <img>: An image
- <a></a>: An anchor (hyperlink to things like other HTML pages, files, email addresses and more.

Most of those elements contain both opening and closing tabs to indicate where an element starts and ends. The <img> tag is an exception. 

A basic HTML file consists of:
- A doctype declaration <!DOCTYPE html>
- The second line is the "<html>" tag with its closing on the last line of the file
- Within the root <html>, we place "<head>" and "<body> elements
- Underneath the <head>, we have <title> for the webpage. 
- The <body> contains the main content of an HTLM file -- the information that is rendered by the web browser. Note that there is only one <body> element with an HTLM file.
- Within the <body> element, we have a high-level heading (<h1>) and a paragraph (<p>). 

 ![Screenshot from 2022-08-01 00-55-08](https://user-images.githubusercontent.com/101457312/182051842-444c3dd3-1b9e-4a18-a708-e4b0c6ac0657.png)


We can connect a HTML page to other web pages by creating a hyperlink using the anchor tag as in the example below: 
<a href="mailto:m.amzat@alustudent.com">Email</a>

We will want to include a bulleted or number list in web page content.
- Unordered lists: We must use the <ul> tag, with nested <li> tags
- Ordered lists: We must use the <ol> tag to declare the list. 


Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML. It describes how elements should nbe renderd on screen, an paper, in speech, or on other media. In other words, it is used to selectively style HTML elements.
p {
   color: green;
}  
This is called a ruleset. The selector "p" defines the element to be styled; a paragraph. The selector in a ruleset is the only thing outside of the curly braces. The declaration (color: green;) must contain a colon (:) to separate the property from its value and each declaration must be separated by a semicolon (;).

We can also select multiple elements and apply a single ruleset to all of them by separating multiple selectors by commas.
p, li, h1 {
   color: yellow;
}

I have also learned about fonts and text. 
Moreover, CSS layout is based on the box model:
- padding: Space around the content,
- border: the solid line that is just outside the padding
- margin: The space around the outside of the border. 
Here, I've got to manipulate:
- width of elements
- background-color
- color
- text-shadow

In a nutshell, those are the knowledge I've acquired with 4 days since I started learning about HTML and CSS. I wish I could create something more appealing, but I look forward to enhancing my understanding through practice and rendering better results in the days to come.
