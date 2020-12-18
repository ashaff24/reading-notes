# Java Script

What do you know:
- It is the muscle for your page. It makes your page functional.
- It can store variables, iterate through arrays. It is more of a programming language

- **Java and Java Script are two different languages**

Variables - temporary storage of something

example: `var name = 'Roger'`
 with this, everytime JavaScript sees "name" it will replace it with Roger

 So, if you put `console.log(name + 'is your instructor'); 
 it would print out:
 Roger is your instructor

 Readings:
 
 **How HTML, CSS, and JavaScript Fit Together**
 - HTML - content
 - CSS - formatting
 - JS - function
 *Where possible, try to keep the three languages in separate files

 **Progressive Enhancement**
 - Three layers form the basis of approach to building web pages called Progressive Enhancement
 - Screen sizes, connection speeds, device capabilities all vary
 - Some users browse with JavaScript turned off, so need to make page that still works in that case
 - Keeping the layers in seperate files means that the page still works if the user cannot run or load JavaScript.

 **Linking to JavaScript**
 - Use `<script>` element with an src attribute that tells people where the JavaScript is stored
 - This tells the browser to find and load the script file
 - The source of the web page does not actually show the new element; it just shows the link to the JavaScript file
 - Most scripts are added just before the closing `</body>` tag
 - Placing script directly in the page:
    - `document.write()` writes content directly into the webpage
    - This is not always best
- When a browser comes across a `<script>` element, it stops to load the script and then checks to see if it needs to do anything
    - This can affect the loading time of pages

**Objects and Methods** (*see page 50 in JavaScript and JQuery book*)
- **Document Object** - represents the entire webpage
- **Method** - `write ()` method allows new content to be written into the page where the `<script>` element sits
- **Member Operators** - You can access members of an object by using a dot between the object name and the member you want to access
- **Parameters** - Each piece of info is called a parameter of the method

## Basic JavaScript Instructions
- Your instructions need to reflect how computers get things done
- A **script** is a series of instructions that a computer can follow one-by-one. Each individual step is known as a **statement**. Statements start on a new line and end in a semi-colon.
- JS is case sensitive
- **Code Blocks** - Statements surrounded by curly braces
- Write comments to explain what your code does
    - **Multi-line comments** - go between the `/* and */` characters
    - **Single-line comments** - anything following `//` on that line
- **Variables**
    - A script will have to temporarily store the bits of information it needs to do it's job. Stored in data in **variables**
    - Need to give computer VERY detailed instructions
    - Once you leave the page, browser will forget any info it holds
    - Variables can be used to represent values in your scripts that are likely to change
    - Results is said to be **calculated** or **computed**
    - Before using a variable, you have to **declare the variable**
        - Use a **variable keyword** and a **variable name**
        - *Rules for Naming a Variable*
            - Must begin with a letter, $, or _. Can NOT start with a number
            - Can contain letters, numbers $, or _. Can NOT use a - or a period.
            - Cannot use keywords or reserved words
                - **Keywords** - special words that tell interpreter to do something
                - **Reserved words** - may be used in a future version of JS
            - All variables are case sensitive
            - Use a name that describes the info stored
            -  If name is more than one word, first word is all lowercase, subsequent words start with a capital (i.e. firstName). This ic called camel case.
    - Next, assign a value to variable
        - Equals sign is used and is called an **assignment operator**
        - Until value is assigned, it is referred to as **undefined**
    - Once a value has been assigned to a variable, you can use the variable name to represent that value
- **Data Types**
    - **Numeric Data Types**
        - Used for handling numbers
        - No comma between larger numbers
        - Can use negative numbers and decimals
        - Can also be used to determine size of screen, moving position of an element, setting amount of time an element takes to load
    - **String Data Types**
        - Consists of letters and other characters
        - Enclosed within a pair of quotes (can be single or double)
        - Used when working with any kind of text
    - **Boolean Data Types**
        - True or False
        - Can only have one of two values
        - Think of it as either on or off
        - Can also be used when your coe can take more than one path


[<== Back](README.md)
