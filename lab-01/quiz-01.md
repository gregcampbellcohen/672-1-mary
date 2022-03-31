# Quiz 1

1. The advantage of using a live server in lieu of the index.html file is that the web page is available to other users, and we are better able to analyze the webpage for issues and debug it. It is clear the local server is running correctly if the browser address begins with http:// and includes a numeric IP address.

<!-- Good!  Also: The local web server mimics a production environment (the host that we share to the world). The local web server hosts our page and allows a browser to make an http request. A successful request will return a rendered web page. If problems occur, such as broken links or errors in our code, the browser's Console will report information that can help debug our code and optimize our page.-->

2. ids only pertain to one element, while classes (can) apply to a group of elements.

<!-- We also use CSS to address and select desired HTML elements and manipulate them with JavaScript. -->


3. console.log("Hello World");

## 4


### A solution

```html
<p>
    <font color="#448ee4">I</font> love 
    <font color="#448ee4">web</font> mapping 
    <font color="#448ee4">and</font> 
    <a href="https://leafletjs.com/">Leaflet</a> 
    <font color="#448ee4">is</font> an 
    <font color="#448ee4">awesome</font> web 
    <font color="#448ee4">mapping</font> library!
</p>
```

(I understand the instructions here to be one HTML paragraph, precluding the use of CSS; I think I'd ordinarily create a highlight class)

### Example output
<p><font color="#448ee4">I</font> love <font color="#448ee4">web</font> mapping <font color="#448ee4">and</font> <a href="https://leafletjs.com/">Leaflet</a> <font color="#448ee4">is</font> an <font color="#448ee4">awesome</font> web <font color="#448ee4">mapping</font> library!</p>

### Another example

We can change the default style of an element to make the shorten syntax.

```html
<style>
    /* Apply style to native bold element inside another element to shorten code */
    #crazySentence b {
    color: #448ee4;
    }

    /* Style link element */
    #crazySentence a {
    color: #000;
    text-decoration: underline;
    }
    
</style>

<body>
    <div id="crazySentence"> 
        <b>I</b> love <b>web</b> mapping 
        <b>and</b> <a href="http://leafletjs.com/">Leaflet</a> 
        <b>is</b> an <b>awesome</b> web
        <b>mapping</b> library! 
    </div>
</body>
```

<style>
    /* Apply style to native bold element inside another element to shorten code */
    #crazySentence b {
    color: #448ee4;
    }

    /* Style link element */
    #crazySentence a {
    color: #000;
    text-decoration: underline;
    }
    
</style>

<body>
    <div id="crazySentence"> 
        <b>I</b> love <b>web</b> mapping 
        <b>and</b> <a href="http://leafletjs.com/">Leaflet</a> 
        <b>is</b> an <b>awesome</b> web
        <b>mapping</b> library! 
    </div>
</body>
