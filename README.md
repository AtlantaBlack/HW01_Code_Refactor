# HW01_Code_Refactor
 Refactoring Horiseon website for web accessibility 

 https://atlantablack.github.io/HW01_Code_Refactor/

**Version 2**

Version 2 focusses on optimising the header and footer sections.

**Changes made to HTML**
```
• Replaced <div> tag in the header with <nav> to create the navigation bar
• Added <span> tag with img role and aria-label for better accessibility
```

**Changes made to CSS**
```
• The following selectors were modified in some way:
    .header h1 .seo changed to .seo
    .header div changed to nav
    .header div ul changed to ul
    .header div ul li changed to li
• Consolidated font-family for header and footer into one selector
```

--

**Version 1.1**

Fixed formatting of README Version 1 to make it readable. No changes made to HTML or CSS documents at this stage.

Version 1 copied as follows:

To start off, we are making broad-scale changes/additions to the HTML document in order to categorise each section of the content. A title for the website will also be added.

For CSS, we are making a simple adjustment: changing header and footer class selectors so they become regular header/footer element selectors.

**Changes made to HTML**
```
• Added a title for the website
• Changed the following div elements for better accessibility:
    <div class="header"> to <header>
    <div class="footer"> to <footer>
• Added <main> tag to body of text
```
**Changes made to CSS**
```
• Moved 'a' and 'p' element selectors to a spot underneath 'body' element selector
• Removed the class identifier from all header and footer selectors (header/footer selectors are now basic element selectors)
```
--

 Version 1

 To start off, we are making broad-scale changes/additions to the HTML document in order to categorise each section of the content. A title for the website will also be added.

For CSS, we are making a simple adjustment: changing header and footer class selectors so they become regular header/footer element selectors.

 Changes made to HTML:
 • Added a title for the website.
 • Changed the following div elements for better accessibility:
    <div class="header"> to <header>
    <div class="footer"> to <footer>
 • Added <main> tag to body of text.
 
 Changes made to CSS:
• Moved 'a' and 'p' element selectors to a spot underneath 'body' element selector.
• Removed the class identifier from all header and footer selectors (header/footer selectors are now basic element selectors)
 
