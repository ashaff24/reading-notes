# CSS

## What do you know?

- Cascading Style Sheets
- The style portion of the webpage
- How does it differ from HTML?
    - Comes after the HTML
    - Uses different text/language
- Reads from top to bottom (ordering matters)
- Include values like size of text or images
- Add it directly into the HTML page or have its own page and link to the HTML
    - Used to be that everything is all on one page
    - Getting away from that due to scalability 
    - If you are rewriting the same code over and over again, and you have one area that's the same on every webpage, you would have to go to every single webpage and make whatever change you wanted. 
    - If you have CSS in it's own document, you can specifically target any section of html on any page and change it all in one swipe instead of having to go to every page individually
    - **Scope of responsibility** - HTML is only responsible for the html, CSS is only responsible for css, JS is only responsible for JS. That way you can look at individual parts to fix a problem instead of going through an entire page. Makes troubleshooting easier.

- Applies to different html elements. Important to use **IDs** and **classes** to target different areas on my webpage.

## Readings

### Intro to CSS

- CSS allows you to create rules that specify how the content of an element should appear
- Pretend there is an invisible box around each HTML element
    - **Block Elements** - Look like they start on a new line
    - **Inline Elements** - Flow within the text and do not start on a new line
- Associate rules with HTML elements
    - Selectors and Declarations are separated by a colon
    - **Selector** - indicate which element the rule is applying to
    - **Declaration** - Indicates how the elements referred to should be styled
        - **Property** - Indicates the aspect of the element you want to change
        - **Value** - Specify the settings you want to use for the chosen property
        - Properties and Values are separated by a semi-colon
- Using external CSS
    - `<link>` element - tells browser where to find the CSS file used to style the page
    - Lives inside the `<head>` element
    - Uses three attributes
        - `<href>` - specifies the path to the CSS file
        - `<type>` - specifies type of document linked to (text/css)
        - `<rel>` - speifies relationship between the HTML page and the file it is linked to (stylesheet)
    - An HTML page can use more than on CSS stylesheet
    - Advantages:
        - Allows all pages to use the same style rules
        - Keeps content seperate from formatting
        - Can change styles across all pages by just changing one file
- Using internal CSS
    - Place them inside a `<style>` element inside the `<head>` 
- CSS **selectors**
    - Allow you to target rules to specific elements
    - Case sensitive - must match element names and attribute values exactly
    - See page 238 in HTML and CSS book for examples
- **Cascading**
    - **Last Rule** - If two selectors are identical, last one will take precedence
    - **Specificity** - More specific rule will take precedence
    - **Important** - Can add `!Important` after any property value to indicate it should be more important than any other rules applied to that element
- **Inheritance**
    - Certain values are inherited by child elements, so you don't have to apply properties to as many elements
    - Other values are not inherited, generally because it could result in a messy webpage
    - Can force inheritance by using `inherit` for the value of the properties
- Different versions of browsers and CSS
    - Some browsers display a few CSS properties in unexpected ways
    - Test site in multiple browsers and versions before launching site
    - **Browser quirk** or **CSS bug** - When a CSS property does not display as expected

### Color
- **Foreground color**
    - Allows you to specify the color of text inside an element
        - RGB Values
        - Hex Codes
        - Color Names
- Comments - Anything between `/*` and `*/` will not be interpreted by the browser and can be used to write comments for coders
- **Background color**
    - Sets background color for HTML element
    - Use same three methods as foreground color
    - If no color specified, will be transparent
    - Make sure to set color even if white because users can set their own browser background colors
- To find color you want, you can use a color picker
    - colorschemedesigner.com
- Other values
    - **Hue**
    - **Saturation** - refers to the amount of gray in a color
    - **Brightness** - refers to amount of black in a color
    - **Lightness** - refers to the amount of black OR white in a color
- **Contrast**
    - Enusre there is enough contrast for text to be legible
    - Low contrast - Text is harder to read
    - High contrast - Easier to read, but too much can make it hard to read a lot
    - Medium contrast - For long spans of text, improves readability
- **Opacity**
    - rgba
    - Only affects the element on which it is applied (not child elements)
    - To create a fallback for browsers that can't read this, specify an rgb color and put it BEFORE the rgba
- **HSL Colors**
    - Alternative way to specify colors
    - Hue, saturation, lightness
    - Fourth value which represents **transparency** - hsla
    - As with rgba, not all browsers recognize it, so have a fallback

[<== Back](README.md)