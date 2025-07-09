# How to write an HTML Boilerplate

![some alt text](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*1u2p917cvlyP6SuHcq3t0Q.jpeg)

When creating a new website, the first step is to set up your HTML boilerplate — a basic structure of an HTML document that acts as the foundation for your webpage. This boilerplate ensures that your webpage is compatible with modern browsers and ready for further development.

*In this article, you’ll learn what an HTML boilerplate is, why it’s important, and how to write one from scratch.*



### 🔍 What is an HTML Boilerplate?
*An HTML boilerplate is a template of standard HTML code that includes the essential elements of any web page. It typically contains:*

* The document type declaration (DOCTYPE)
* tags like:
  * html
  * body
  * head
* Metadata such as the character set, viewport settings, and title
* Links to CSS and JavaScript files   



### Basic HTML Boilerplate Code


```javascript

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1>Hello, world!</h1>
  <script src="script.js"></script>

</body>
</html>

```


### Explanation of Each Part
* **`<DOCTYPE>`** :
ells the browser you’re using HTML5.
* **`<html lang="en">`**:
The root of your HTML document. The lang attribute specifies the language.
* **`<head>`** :
Contains metadata (information about the document).



### Tips for Writing Your Boilerplate

1. *Use consistent indentation for readability.*
2. *nclude the viewport meta tag for responsive design.*
3. *Link your CSS and JavaScript files early for better project organization.*
4. *Validate your HTML using tools like W3C Validator.*




## Conclusion

Writing an HTML boilerplate is a small but essential step in building any web project. By understanding and creating your own boilerplate, you set the stage for clean, maintainable, and browser-friendly web development.

>Start every project with a solid HTML structure — your future self will thank you!



