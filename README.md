# challenge-1-accessibility

* Task: Modify starter HTML and CSS code to make Horiseon webpage more accessible and more optimized for SEO

# User Story

* AS A marketing agency
* I WANT a codebase that follows accessibility standards
* SO THAT our own site is optimized for search engines

# Acceptance Criteria

* GIVEN a webpage meets accessibility standards
* WHEN I view the source code
* THEN I find semantic HTML elements
* WHEN I view the structure of the HTML elements
* THEN I find that the elements follow a logical structure independent of styling and positioning
* WHEN I view the image elements
* THEN I find accessible alt attributes
* WHEN I view the heading attributes
* THEN they fall in sequential order
* WHEN I view the title element
* THEN I find a concise, descriptive title

# CHANGES:

# HTML
* changed div sections to semantic HTML header, footer, nav, section, article
* changed title from generic name more descriptive title about the page
* edited the id on search engine optimization to make the link work
* changed h3 to h2 for the benefits header
* added comments in HTML that described each section to make it easier to understand the flow of the page
* added alt description tags to all of the images and graphics in the page for accessibility
* changed class names in content and benefit section to combine same CSS rules
* removed class from header and footer

# CSS 
* added comments in CSS to describe each section
* changed header and footer from class (.header) to html selector (header) to eliminate unnecessary classes
* combined CSS rules for benefits sections and content sections to remove duplicates
* changed selectors in CSS to reflect semantic elements changes in HTML
* rearragned CSS rules to create logical flow

