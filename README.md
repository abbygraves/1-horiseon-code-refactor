# **HTML and CSS Git Challenge: Code Refactor**

## **Description**

The purpose of this project was to ensure that the codebase met accessibilty standards and functionality requirements for a published website so that the website was optimized for search engines and customers needs.

<br/>

## **Table of Contents**

- [Why I Did It](#why-i-did-it)
- [What I Started With](#what-i-started-with)
- [Modifications](#modifications)
- [What I Learned](#what-i-learned)

<br/>

## **Why I Did It**
Horiseon, a marketing agency, needed to ensure that their codebase for their website met accessibility standards. The agency provided me with their working codebase requesting minor modifications, improved formatting, and a clean up (consolidation) of the index.html and style.css files. Once complete, the website would be optimized for search engines as well as Horiseon's customers.

<br/>

## **What I Started With**
I began with an index.html and style.css file both containing code that made up the majority of the visual aspects, the information, and functions seen on Horiseon's homepage. I was also given a mock-up of what the finished site should look like. 

```md
![mock-up](assets/images/mock-up.png)
```

To begin, I determined the areas that were in need of improvment in both files:

### <ins>HTML</ins>
+ Formatting
+ Structure
+ `title` element
+ Link functionality
+ Over usage of `div` element
+ Accessible image elements

### <ins>CSS</ins>
+ Order of the rules
+ Multiple different classes <br/> containing duplicate code
+ Class names too specific
+ Lack of comments 

<br/>

## **Modifications**
+ Corrected HTML formating which consisted of making the proper indentations and moving components so that the code flowed from top to bottom following the structure of the website 
+ Gave the website a descriptive and concise `<title>`
+ Replaced `<div>` elements with defining semantic elements to organize the code as well as make it more accessible
+ Made the branding in the `<header>` clickable to direct users back to the homepage by adding an `<a>` element with an `href` value of `"index.html"`
+ Added an `id` attribute to the Search Engine Optimazation card so that the corresponding `<nav>` element within the `<header>` would navigate to the correct portion of the page
+ Included descriptive `alt` attributes for all simple images on the homepage as well as `alt` attributes containing no text for the decrotive images to ensure screen readers can properly identify significant vs. insignificant images 
+ Rearranged CSS rules according to the semantic structure of the HTML
+ Consolidated CSS rules that contained duplicate code into more generic classes
+ Defined the CSS for the `<span>` element by nesting the selector within the `.header` class to encourage simplicity and organization
+ Added comments to the CSS file

<br/>

## **What I Learned**
This project taught me the importance of simplicity, structure, and organization when writing code. The orginal code I was given was difficult to decipher and very crowded. The use of semantic elements can drastically change the way code is read and allows the developer as well as accessibility tools such as screen readers to follow a locical structure thus making the content easier to understand. Not only do semantic elements make code more visually appealing, but they also have the capability to optimize websites for search engines. This is extremely important for any business that's looking to reach a wide range of customers. 