# HW01_Code_Refactor

 The objective of this project is to refactor the code for Horiseon's website to ensure better accessibility. 

 https://atlantablack.github.io/HW01_Code_Refactor/

---

## Version 5

Alt text properties for images have been changed to null. Originally, alt text descrptions were added to all images so that the presence of each image would be noted, but upon further consideration, these images (which are in the main content box, sidebar, and the big display) are there for decorative purposes, rather than to provide information.

**Changes made to HTML**

• aria-label for `div class="hero"` removed

• alt-text removed from images within section and aside tags

**Changes made to CSS**

• No changes made

---

## Version 4

Version 4 optimises the content in the sidebar to the right. The div box will be changed to an aside element. The font-family property inside the `aside` selector is removed as it was redundant; the same property is found inside the `body` selector.

**Changes made to HTML**

• Synced class name changes for main-content `div` and `section` tags

• Changed `div class="benefits"` to `aside`

• Changed `div` tags within aside to `section` tags

• Added alt-text for images in `aside`

**Changes made to CSS**

• Renamed the following class selectors to be more specific:
```
    .content changed to .content-container
    .content-text changed to .main-content
    .content-text img changed to .main-content img
    .content-text h2 changed to .main-content h2
```

• Changed .benefits class selector to `aside` element selector

• Consolidated the following class selectors into one class `.benefits`: 
```
    .benefit-lead
    .benefit-brand
    .benefit-cost
```

• Consolidated the following h3 class selectors into one class `.benefits h3`:
```
    .benefit-lead h3
    .benefit-brand h3
    .benefit-cost h3
```

• Consolidated the following img class selectors into one class `.benefits img`:
```
    .benefit-lead img
    .benefit-brand img
    .benefit-cost img
```

• Removed font-family from `aside` selector

---

## Version 3

Version 3 optimises the main body of content on the left. The large image displayed above the content area and sidebar is given text so it is not missed by screen readers.

**Changes made to HTML**

• Modified `div class="hero"` to include img role and aria-label for big display image

• Changed `div` tags to `section` tags

• Added alt-text to images within `div class="content"`


**Changes made to CSS**

• Moved .benefits selector below .content-text selector

• Consolidated the following class selectors under one main class selector `.content-text`:
```
    .search-engine-optimization
    .online-reputation-management
    .social-media-marketing
```

• Consolidated the following img class selectors into one class `.content-text img`:
```
    .search-engine-optimization img
    .online-reputation-management img
    .social-media-marketing img
```

• Consolidated the following h2 class selectors into one class `.content-text h2`:
```
    .search-engine-optimization h2
    .online-reputation-management h2
    .social-media-marketing h2
```

• Moved font-family from `nav` and `content-main` into `body`

---

## Version 2

Version 2 focusses on optimising the header and footer sections.

In the header, a `div` container was replaced with `nav` to create the navigation bar. In the footer, a `span` with image role and aria-label was added to the love-heart emoji.

Some CSS classes were renamed to 

**Changes made to HTML**

• Replaced `div` tag in the header with `nav`

• Added `span` tag with img role and aria-label


**Changes made to CSS**

• The following selectors were modified for better organisation:
```
    .header h1 .seo changed to .seo
    .header div changed to nav
    .header div ul changed to ul
    .header div ul li changed to li
```

• Consolidated font-family for header and footer into one selector

---

## Version 1

To start off, we are making broad-scale changes/additions to the HTML document in order to categorise each section of the content. A title for the website will also be added.

For CSS, we are making a simple adjustment: changing header and footer class selectors so they become regular header/footer element selectors.

**Changes made to HTML**

• Added a title for the website

• Changed `div class="header"` to `header`
    
• Changed `div class="footer"` to `footer`

• Added `main` tag to body of text

**Changes made to CSS**

• Moved `a` and `p` element selectors to a spot underneath `body` element selector

• Removed the class identifier from all header and footer selectors
