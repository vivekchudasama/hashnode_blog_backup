## Everything you need to know about HTML 5!

Introduction to HTML
--------------------

HTML, also known as HyperText Markup language, is a language we use to structure web pages. It's a required basic skill if you want to become a web developer one day. HTML is fairly easy to learn, so it's suitable for beginners looking to get started in this field.

HTML is also known to be paired up with CSS (Cascading Style Sheets) and JavaScript. In a simple explanation, HTML acts as the skeleton of a website. It structures and gives the website shape. CSS acts as the skin of the website, that defines how things look, from the size of the text, fonts, positioning, spacing, and more. JavaScript acts as the muscles of the website, which makes the website functioning and dynamic. You'll focus on HTML for now, and you'll learn more about the website anatomy mentioned before later on.

Please note that HTML isn't a programming language, rather it's a markup language. HTML doesn't have control flows, like loops and functions, like programming languages. Its only job is to define the basic content of a website, like the headings, paragraphs, images, and many more. In this series of articles, you'll learn everything you'll need to know to get started with HTML!

For this article, which is part one of the series, you'll learn about:

*   The Basics of the Web
    
*   The Basics of HTML Elements
    
*   The Structure of HTML Documents
    
*   Links in HTML
    

Let's get started with the basics of the web!

The Basics of the Web
---------------------

Before we get our hands dirty and explore the world of web development, we should first know how the web works! That's how it is. What is the web? How do people access it? How are they created? How does it work? We'll learn the answers to those questions in this part of the article.

So, what is the web?

Based on [Wikipedia](https://en.wikipedia.org/wiki/World_Wide_Web),

> "The World Wide Web, commonly known as the Web, is an information system enabling documents and other web resources to be accessed over the Internet."

The web is an interconnected system of public web pages that you can access using the internet. You can imagine it as a very very big library of websites, where all these websites, inside the library, are connected. The web is different from the internet, search engines, and browsers.

The internet is a network that helps you use the web. Search engines are a tool that allows you to browse the "books", or websites, in this so-called library (the web). Browsers are special software that gets data from the web and projects them into your device. You use the browser to access the internet. Some popular ones are Chrome, Firefox, Edge, Brave, Opera, and more.

These websites inside the web are most likely to be made using HTML and CSS, which are the languages used to create basic websites. Websites are hosted inside something called a web server. Your browser will project the HTML and CSS code. Some websites also use a programming language called JavaScript to make their websites dynamic. We'll cover more about that in another series.

Large websites, that are updated regularly and use CMS (Content Management System), blogging tools, or e-commerce services (like Amazon or eBay) are most likely to use more complex technologies in the web server, like databases. We'll not cover those things, yet, and we'll focus on learning HTML and CSS to make simple websites.

Also, there have been many different versions of HTML and CSS, since the web was first invented. Currently, the latest version of HTML and CSS is HTML5 and CSS3. Remember that HTML5 and CSS3 is the version of HTML and CSS, they are not different thing.

Now, you know what is the web, but how does it work? As you know, websites are hosted in something called a web server. A web server is a special kind of computer that uses protocols to respond to requests made on the web. Its main job is to store, process, and deliver the web pages to the users. This web server could be anywhere in the world.

When you visit a website, your browser will connect to a DNS (Domain Name System) server. These things act like a phone book, but instead of phone numbers, they tell your browser the IP address of the website's web server. An IP address is a randomly generated number, up to 12 digits that are separated with a full stop. Every device connected to the web has unique IP addresses, similar to phone numbers.

After that, your browser will try to "request" the website from the web server, from the IP address we've received from the DNS server. The web server will deliver the web page that you've requested and your browser will project them on your device. This whole process mostly happens in less than a second! But it will usually depend on your internet connection speed. This whole thing is made possible by the presence of the internet!

Basic HTML Elements
-------------------

You'll hear this word a lot when learning about HTML: elements. What is it?

HTML consists of a bunch of different elements, and it defines everything you can see on your web page! Most elements have an opening tag, content, and a closing tag. Take a look at the example below.

Copy

    <p>Hello, World!</p>
    

The example above uses the element

, which defines a paragraph in HTML. The content of the element's value is wrapped around the opening tag and closing tag. Here's a closer look at the anatomy of an HTML element, that I grabbed from the [MDN](https://developer.mozilla.org/en-US/) website.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1660457708409/4sGu9DGP-.png?auto=compress,format&format=webp)

As you can see, the element above contains three things:

*   The opening tag. It consists of the name of the element (in this case, it's p for paragraph), wrapped in a pair of brackets. It defines the start of the element.
*   The content. It's the content of the element displayed (in this case, it will display the text 'My cat is very grumpy' on the web page). Everything wrapped up inside the opening tag and closing tag is the content of the element.
*   The closing tag. It's similar to the opening tag, but it got a forward slash (/) before the name of the element. It defines the end of the element.

You can try writing your first HTML element (if you haven't tried doing that) on your own! You can use the paragraph element like the example shown before. We'll learn more about more elements as we move on, and you'll be able to build your web page sooner than you think!

HTML Structure
--------------

Alright, so we've learned about the basics of elements in HTML. In a website, there will be a lot of different kinds of HTML elements in use. You'll see the headings, paragraphs, and more.

Everything in HTML is a built-in structure. I mean, it's what HTML is used for, right? We'll dive deep into the structure in this part. Let's take a look at an example of an HTML document.

Copy

    <!DOCTYPE html>
    <html lang="en-US">
      <head>
        <meta charset="utf-8">
        <title>My Website</title>
      </head>
      <body>
        <h1>Big Cats</h1>
        <p>Some text here</p>
      </body>
    </html>
    

Let's look at the structure of the HTML code above here. Here we have:

*   `<!DOCTYPE html>` is the doctype, and it tells the browser that your code is written in HTML. It's highly recommended that you start your HTML document with this at the top, and that's all you need to know.
    
*   `<html></html>` wraps the content of the page inside of this element. This element is also known as the root element. Beware of that word. This element may contain attributes, such as the lang which are set to "en". The lang defines the language of the HTML document, and it's currently set to English ("en"). This is useful to include to help the browser recognize the language of the web page. We'll take a closer look at attributes later on.
    
*   `<head></head>` contains information about the metadata and information of the website that the search engine will use. Normal viewers won't be able to see this directly, as it won't be shown on a normal browser window.
    
*   `<body></body>` contains everything the viewer can see on the browser. It displays the text, images, videos, and more.
    

That's it for the basic structure of an HTML document. We'll discuss more of the elements inside of the body, but let's take a closer look at the head element.

*   `<meta>` sets the metadata of the web page. This element may contain attributes, such as the charset which are set to UTF-8. The UTF-8 contains the most characters written in the human language, so to avoid problems in the future, it's recommended to add this to your HTML document.
    
*   `<title></title>` sets the title of the web page, which you can see in the browser tab the page is loaded in.
    

Now let's take a look inside the body element. The elements inside the body element will be shown on the web page.

*   `<h1></h1>` defines a heading. The number 1 in h1 defines the hierarchy or the order of the heading. There are headings from h1 to h6, going from largest to smallest, that currently exist.
*   `<p><p>` defines a paragraph, which is used for paragraphs, or just any "normal-sized" texts on your web page.

More About HTML Attributes
--------------------------

You may have seen some attributes inside some of the HTML elements shown in the examples. Here's a more detailed explanation of it.

Attributes provide additional information about the elements. All elements may have an attribute included in the opening tag of the element. Here's an example of an element using an attribute that we've seen before.

Copy

    <html lang="en-US">
    

The attribute is inserted inside of the `HTML` opening tag, after the word 'HTML' in this case. As you know, the `lang` attribute defines the language of the document, and it's currently set to `en` for English. [Here's](https://meta.wikimedia.org/wiki/Template:List_of_language_names_ordered_by_code)a list of languages and their code if you want more information.

You can see from the previous example that attributes give an element more information. You'll often use attributes when writing HTML code. Here's another example of HTML attributes in use from the code we've seen before.

Copy

    <meta charset="utf-8">
    

This attribute gives more information to the `meta` element, about the `charset` defines the character encoding for the HTML document, and it's currently set to `utf-8`, which is the most popular encoding for the web. Don't worry if you're confused with those words, for now, you just need to know that it's recommended to set up those things when writing HTML code. Now let's look at how we make links!

Links in HTML
-------------

Has one of your friends sent you a URL to a YouTube video before? You'll have to click, on them to watch the video right? That's what a link is. It's a thing you click on that brought you to a specific address. Usually in a form of a direct URL of the address, or maybe shorten into a word (hyperlink) like [this](https://www.youtube.com/watch?v=iik25wqIuFo). Try to click on it!

I'm sorry for that. Anyway, to make you feel better, let's learn how to create links, just like that, on HTML!

To link something in HTML, you'll use the `a element, which stands for 'anchor'. No idea why it's named like that. Here's an example.

Copy

    <p>Click <a>here!</a></p>
    

I wrapped the word 'here!' in the anchor tag, as we'll turn that word into a hyperlink (the link which is shortened into words, like the rickroll link earlier). Next, we'll add the attribute to the opening anchor tag.

Copy

    <p>Click <a href="https://example.com" target="_blank">here!</a></p>
    

The `href` stands for 'HyperText Reference', which defines the destination of the link. When you click on the link, it will take you to the destination that's set on the `href` attribute. Good thing we've learned about that before! Also, we have the `target` attribute set to `_blank`. Looks weird, but make sure that when you click the link, it will open on another tab, so the user won't leave the website. Try to see the difference between when you use the target element, and when you don't. Anyway, the code before will function similarly to this (without the fancy font).

Click [here!](https://example.com)

Try making your hyperlink in HTML!

Summary
-------

Here's the summary of this article.

*   HTML is the language we used to structure the web page.
*   The web is a collection of public web pages, and it works with the presence of the internet.
*   HTML is made up of elements, that may contain attributes.
*   In an HTML document, we have the `doctype`, the `HTML` element (also known as the root element), the `head` element that contains the information for the browser, and the `body` element that contains the things we can see on the web page.
*   We use the `a element to define links in HTML.

Also, you'll understand the code we've seen at the start!

Copy

    <!DOCTYPE html>
    <html lang="en-US">
      <head>
        <meta charset="utf-8">
        <title>My Website</title>
      </head>
      <body>
        <h1>Big Cats</h1>
        <p>Some text here</p>
      </body>
    </html>
    

In the next article of the series, we'll learn more about texts! Stay tuned for that, and thank you for reading until the end! Consider following, and if you have any comments, suggestions, or questions, or if you caught a foolish error made in the article that you want me to fix, be sure to leave them in the comments below!

Thanks for reading!

Credits
-------

[developer.mozilla.org/en-US](https://developer.mozilla.org/en-US/)

[w3schools.com](https://www.w3schools.com/)

[Vivek Chudasama](https://vivekchudasama.com/)