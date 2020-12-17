# HTML

- Hypertext Markup Language

- index.html - this is what your primary or home page will be called (standard)
    - GitHub will look for "index.html" first, followed by README
- Used to create structure of paragraphs and headings (the bones/foundation of your website)
    - *Tags* 
        - Establish structural components
        - There will be an opening tag and a closing tag (closing tag has an extra / in it as seen below)
            - `<p></p>`
            - `<body></body>`
            - `<header></header>`
            - `<img></img>`
        - *See pages 23-24 in HTML and CSS book*
    - *Attributes*
        - Provides additional information about an element 
        - Appear at the opening tag and have a name and a value separated by an equals sign
        - The name indicates what kind of extra info and is written in lowercase
        - Value is the info or setting for the attribute and should be placed in double quotes
            - `<p lang="en-us">Paragraph in English</p>`
    - `<Head>` and `<Title>`
        - This contains information about the page and shows up on the browser window, instead of in the actual page

- *Evolution of HTML*
    - HTML 4 (1997)
    - XHTML (2000)
        - Started adding in XML
        - Every element needed a closing tag
        - Attribute names lowercase
        - Attributes required a value in double quotes
        - No longer use deprecated elements
        - Every element opened in another should be closed inside same element
        - Works seamlessly with other programs
        - A few different versions of this
    - HTML5
        - Work in progress
    - DOCTYPES
        - Each webpage should begin with this to tell a browser which version of HTML is being used
    - Comments in HTML
        - Do not show up on browser
        - Useful when looking back at it later and make code easier to understand
        - `<!-- -->`
    - ID Attribute
        - Uniquely identifies that element
        - No two elements on same page have same value
        - Also known as a global attribute
    - Class Attribute
        - Identify several elements as being different from the other elements on the page
        - Can share same value
        - Using these does not affect presentation of an element unless CSS rule indicates it should be displayed differently
    - Block Elements
        - Some elements always start on a new line in browser window
        - `<h1>, <p>, <ul>, <li>`
    - Inline Elements
        - Some elements will always continue on the same line
        - `<a>, <b>, <em>, <img>`
    - Grouping Text and Elements in a block
        - The `<div>` element allows you to group a set of elements together in one block level box
        - Can be several other elements inside a `<div>` element, so good to add a comment after closing `<div/>` tag
    - Grouping Text and Elements Inline
        - Use `<span>` 
        - If it contains a section of text where there is no other element to differntiate it OR
        - Contains a number of inline elements
    - Iframes
        - Adding a little window where you can see another page
        - Like having a Google Maps image
        - `<iframe>`
    - Info About Pages
        - `<meta>`
        - Not visble to users but tells search engines about your page, who created it and whether it is time sensitive
        - Empty element so does not have a closing tag
    - Escape Characters
        - If you want to use HTML code characters just as their regular characters, have to use an escape character
        - *Small list on page 194 of HTML and CSS book*

- *HTML5*
    - In the most recent version of HTML, the usage of some elements have changed
    - Many no longer require the `<div>` elements
    - Headers and Footers
    Can be used for main header/footer that appear at top or bottom of every page OR for an individual article or section in page
    - Navigation
    Contains major navigational blocks on the site
    - Articles
    Acts as a container for any section of a page that could stand alone
    - Asides
    When used inside an article, it gives info related to the article, but that is not essential. When used outside an article, it is a container for content related to the whole page
    - Sections
    Groups related content together and generally each have their own heading (should not be used to wrap the entire page)
    - Heading Groups
    Group together a set of headings so they are treated as one (not frequently used)
    - Figures
    Can have any content referenced from the main flow (images, videos, graphs, etc). It should also contain a `<figcaption>` to describe the content
    - Sectioning Elements
    When there is no other element to group a set of elements, use `<div>`
    - Linking around Block-Level Elements
    Use an `<a>` around a block level that contains child elements. This turns the whole thing into a link
    - Helping Older Browsers Understand
    Use the following line of CSS which states which new elements should be rendered as block-level elements
        - `header, section, footer, aside, nav, article, figure, figcaption {display: block;}`
        

- Add CSS to make the site look good
- JavaScript makes the site functional 

## Code in a Content Management System
- In some cases, you will log into a special admin section of webiste to control it
- The tools in this section usually allow you to edit parts of the page instead of the whole thing
- You will generally not see the tag components
- May use a single template to control all pages for a section
- People can add info to the webiste and change presentation and it will automatically update every page
- Will often be given a *text editor*
    - Gives you options for style, adding links or inserting images
    - Behind the scenes, these are adding HTML code to your text

## Process and Design

### *Target Audience*

- Ask questions

    - Age range?
    - Women or men?
    - Which country?
    - Urban or rural?
    - Average income?
    - Level of education?
    - Marital/family status?
    - Occupation?
    - What kind of device to access the web?

- Create fictional visitors
    - This can help influence design decisions

- *Why* are people visiting this website?
Create a list of reasons why people would be coming to the site

    -Key Motivations
        - Entertainment?
        - Personal or professional goal?
        - Essential or luxury?

    - Specific Goals
        - General info/research/something specific?
        - Already familiar with product?
        - Time sensitive?
        - Deciding whether to buy?
        - Need to contact you?

- What information your visitors need
    - Look at each of the reasons why people will be visiting the site to determine what they need to achieve those goals
        - Will they be familar with subject area or need intro?
        - Familiar with the product or need background?
        - Most important features?
        - What is special that differentiates us?
        - Ommon questions people ask about this subject area?
    - If you do not answer their needs, they are likely to go elsewhere

- How often does it need to be updated?
    - Some sites need updating frequently, some remain more static
        - How often do the same people return to purchase?
        - How often is stock updated or service changed?
        - How often is subject updated?
        - What percentage would return for regular updates?
    - Figure out how often people are likely to revisit your site. This will indicate how often you need to update
    - Set a schedule for updating

### Site Maps
- Start to organize site into sections or pages
- Create a diagram of the pages
- Card sorting
    - Place each piece of info on a piece of paper and organize related info into groups
- The pages will inform how users navigate through the site
- Important to reflect the public's understanding of the subject when organizing

### Wireframes
- Sketch of key info that needs to go on each page
- Shows hierarchy of info 
- Shows how much space the info needs
- Don't include any visual info (color schemes, fonts, etc)
- If you just show a site design to a client, they may only focus on how it looks, not how it will provide information to the public
- Need to organize and prioritize information to communicate message and help users find what they are looking for
   
#### *Visual hierarchy*
- The order in which your eyes perceive what they see
- Created by adding visual contrast between items being shown
- Helps users focus on key messages and then guide them to other messages
- Most users do not read entire pages, but skim instead
- Use size, color and style
- Images attract the eye first

#### *Grouping and Similarity*
- Group related content into blocks or chunks
    - Proximity
    - Closure
    - Continuance
    - White space
    - Color
    - Borders
- Present certain types of info in a similar visual style so users can associate that style with a particular type of content
    - Color
    - Size
    - Orientation
    - Texture
    - Font
    - Shape

#### Designing Navigation
- Concise
Limit to 8 options in a menu
- Clear
Choose single words for each link (not phrases)
- Selective
Primary navigation (often appears across the top of the site or down lefthand side) should only reflect sections or content of site
- Context
Let the user know where they are in the website at the moment
- Interactive
Each link should change when hovered over or clicked on
- Consistent
Secondary navigation can change from page to page, but primary navigation should stay the same throughout the site

       


