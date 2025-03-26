# WEB PROGRAMMING TUTORIALS
# HTML BASICS
# Starting with skeleton <!DOCTYPE HTML>
# <html> tag is the root tag of the element
# <head> tag contains the metadata of the element
# <title> tags set the title of the webpage
# <body> tag contaiins the content of the webpage
# <h1> to <h6> tags to define headings
# <p> tag to define a paragraph
# <pre> tag to define a preformatted text
# <a> tag to insert a hyperlink
# <img> tag to insert an image
# <audio> tag to insert an audio file alongwith control which showcase the mediaplayer and if you want to play by default in browser then use autoplay as an attribute and loop as an atttribute to play in loop
# <video> tag to insert a video file alongwith control which showcase the mediaplayer and if you want to play by default in browser then use autoplay as an attribute and loop as an attribute to play in loop.
# <link rel="icon" type="image/jpg" href="/images/favicon.jpg"> tag used to add favicon to the webpage
<!-- Formatting text>
# <b> tag to define bold text
# <i> tag to define italic text
# <u> tag to define underlined text 
# <s> tag to define strikethrough text
# <sup> tag to define superscript text
# <sub> tag to define subscript text
# <mark> tag to define highlighted text
# <small> tag to define small text
# <del> tag to define deleted text
# <ins> tag to define inserted text
# <abbr> tag to define an abbreviation
# <address> tag to define an address
# <cite> tag to define a citation
# <code> tag to define a code
# <dfn> tag to define a definition
# <kbd> tag to define a keyboard input
# <q> tag to define a quotation
# <samp> tag to define a sample output
<!-- Group together HTML>
# <div> block container to group elements for styling purposes tag to group together HTML elements
# <span> inline container to group elemnts for stying purposes tag to group together inline HTML elements
<!-- List items>
# <li> tag to define a list item
# <ul> tag to define an unordered list
# <ol> tag to define an ordered list
# <dl> tag to define a definition list
# <dt> tag to define a definition term
# <dd> tag to define a definition description
<!-- Tables>
# <table> tag to define a table
# <tr> tag to define a table row
# <th> tag to define a table header cell
# <td> tag to define a table data cell
# <thead> tag to define a table header
# <tbody> tag to define a table body
<!-- Buttons>
# <button> tag to define a button
<!--Forms Creation>
# <form> tag to define a form and we need an attribute "action" to specify the url where the form data will be sent and method to specify the HTTP method to such as GET or POST. GET is used to send data to the server and is used for insensitive data and POST is used to send data to the server and it is used for sensitive data.
# <input> tag to define an input field used with attribute "type" to specify the type of input field such as text, password, radio, checkbox, submit and "id" to specify the id of the input field.
# <label> tag to define a label for an input field used with an attribute "for" to specify the id of the input field. 
<!--Header and Footer Creation>
# <header> tag to define a header section
# <footer> tag to define a footer section
<!-- CSS Section>
# Inline, Internal, External CSS
# Inline CSS: <style> tag used to define a style within the HTML document
# Internal CSS: <style> tag used within the <head> section of the HTML document
# External CSS: <link> tag used to link an external CSS file to the HTML document in external css we need to create a page name style.css and write the css code in it and then link it to the html page using <link> tag; in this we design by uisng <html>, <head>,<para> and <body> or incase if we are using "id" then we use # with the id name and in case if we are using "class" then we use . with the class name.
# CSS Selectors
# CSS Selectors are used to select HTML elements to apply styles to them
# CSS Selectors can be used to select elements based on their id, class, tag name,
# attribute, and pseudo-class
# CSS Properties
# CSS Properties are used to define the styles of the selected elements
# CSS Units
# CSS Units are used to specify the values of CSS Properties
# CSS Units can be used to specify the values of CSS Properties in different units such as pixels,
# ems, exs, percentages, and more
# CSS Box Model
# The CSS Box Model is a concept in CSS that describes the layout of an HTML element
# The CSS Box Model consists of four parts: margin, border, padding, and content
# CSS Box Model Properties
# CSS Box Model Properties are used to define the styles of the different parts of the CSS Box Model
# CSS Box Model Properties can be used to define the styles of the margin, border, padding,
# and content of an HTML element
# CSS Flexbox
# CSS Flexbox is a layout mode in CSS that allows you to create flexible and responsive layouts
# Fonts and Colors for fonts and colors we use CSS properties such as font-family, font-size, color, background-color, etc; in case of color we use hex code, rgb, rgba, hsl, hsla, etc ; in case of font we use font-family, font-size, font-style, font-weight, etc and for fonts-family we can also use google fonts and font awesome icons by embedding the link in the head section of the html page such as "<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">" or we can downlowad the font and in the style.css file we can write the code such as "@font-face { font-family: 'font name'; src: url('font file name such as font/Roboto.tff file'); }" and then we can use the font name in the style.css file such as "font-family: 'font name';
#border for borders we use the attributes like border-style, border-width, border-color, border-radius, etc but instead of using in three different lines of code for border-style, border-width, border-color we can do it in one single line of code such as "border: 1px solid black;" and for border-radius we can use the code such as "border-radius: 10px;" and for border-radius we can use the code such as "border-radius: 10px;" 
#Shadow for shadow we use the attribute box-shadow and we can use the code such as "box-shadow or text-shadow with the values such as 0px 0px 10px black;" and for text-shadow we can use the code such as "text-shadow: 0px 0px 10px black.
#Margin and Padding for margin and padding we use the attributes such as margin, padding, margin-top, margin -bottom, margin-left, margin-right, padding-top, padding-bottom, padding-left, padding-right, etc and we can use the code such as "margin: 10px;" or "padding: 10px;"
# Float peoperty for float property we use the attribute float and we can use the code such as "float: left ;" or "float: right;" and for float property we can use the code such as "float : none;" to remove the float property; flow-root property for flow-root property we use the attribute flow-root and we can use the code such as " flow-root: flow-root;" if the content is getting overlapped then we can use the code such as "flow-root: flow-root; overflow: hidden ;" to remove the overlapped content; 
<!-- Pagination is a method by which document is separated into pages, and numbers are given -->