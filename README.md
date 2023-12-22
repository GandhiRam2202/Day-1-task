# 1.Write a blog on Difference between HTTP1.1 vs HTTP2

[HTTP 1.1 and HTTP 2 ](https://medium.com/@gandhiramparthi/http-was-originally-proposed-in-1989-by-tim-berners-lee-who-was-a-coauthor-of-the-1-0-55a3b8b869cb)

# 2.Write a blog about objects and its internal representation in Javascript

[Objects](https://medium.com/@gandhiramparthi/objects-and-its-internal-representation-in-javascript-da0582bc5b46)


# -------------------------------------------------------

# 1.Write a blog on Difference between HTTP1.1 vs HTTP2

# HTTP

## HTTP 1.1 and HTTP 2 
HTTP was originally proposed in 1989 by Tim Berners-Lee, who was a coauthor of the 1.0 specification. HTTP/1.0 (released in 1996) was “stateless”: each new request from a client established a new connection instead of handling all similar requests through the same connection between a specific client and server

### Versions Of HTTP

- HTTP/0.9–1991-Obsolete
- HTTP/1.0–1996-Obsolete
- HTTP/1.1–1997-Standard
- HTTP/2–2015-Standard
- HTTP/3–2022-Standard

## HTTP1.1 vs HTTP2

The Internet is all about Speed And Transfer the data from Client to Server in safe and secure

HTTP 1.1 is speaking in ***plain text*** “Hi dude How are you” but with HTTP 2 it is using like a secret code a compact, efficient set of signals that convey the same message . ***HTTP 2 uses a binary framing layer***

### Multiplexing 
+ Think of downloading multiple files on HTTP 1.1. Each file creates a separate lane, like cars on a road. If one file gets stuck, everything behind it grinds to a halt. HTTP 2 changes the game by allowing multiple “data streams” to travel down a single, supercharged highway. It’s like sending several packages in one truck, ensuring everything arrives smoothly and quickly.

### Header Compression : 
+ HTTP requests and responses come with “headers” information packets like sender and recipient addresses. In HTTP 1.1, these headers can get wordy, slowing down communication. HTTP 2 applies a clever trick called **HPACK**: it identifies and stores repeated information, sending only the unique bits each time. It’s like having a shared dictionary for common phrases, making communication concise and efficient.

### Server Push : 
+ Imagine a waiter knowing exactly what you want before you even order. That’s the magic of server push in HTTP 2. The server can anticipate what resources you’ll need next (like scripts or styles for a webpage) and proactively send them along, eliminating the need for extra requests and delays.

### The Verdict: 
+ So, who wins the crown? HTTP 2, hands down. Its binary language, multiplexing, header compression, and server push features all contribute to a significantly faster, smoother web experience. Faster loading times, reduced bandwidth usage, and improved responsiveness — that’s the kind of performance boost HTTP 2 brings to the table.

### The Takeaway : 
+ While HTTP 1.1 will likely be around for a while, the future belongs to HTTP 2. If you’re a website owner, upgrading to HTTP 2 is a no-brainer. For users, it translates to a faster, more enjoyable web experience. So, the next time you’re online, remember the silent workhorse behind the scenes, HTTP 2, ensuring your web journey is swift and smooth!


# -------------------------------------------------------

# 2.Write a blog about objects and its internal representation in Javascript

[Objects](https://medium.com/@gandhiramparthi/objects-and-its-internal-representation-in-javascript-da0582bc5b46)

# Objects and its Internal Representation in Javascript
+ Imagine a bag filled with various items: books, keys, photos, each with its own purpose and relationship to the others is called Object

### Objects stored in memory :
+ Here’s where things get intriguing. Unlike primitive data types that directly hold their values, objects are stored as references. Think of it as a treasure map pointing to the actual location where the object’s data resides. This opens up a thrilling world of prototypal inheritance, where objects can inherit properties and methods from their ancestors, forming a hierarchical lineage that makes code reuse a breeze.

+ So, what does this treasure map look like? Inside the memory, an object is represented as a collection of key-value pairs. These keys, often strings, act as labels identifying the properties and methods. The values can be anything from simple numbers to functions. This key-value structure allows for dynamic manipulation of object properties, making them incredibly versatile and powerful.

# Building Your Own Worlds : 
+ Creating objects in Javascript is like constructing your own mini-universes. We use object literals, those curly braces filled with key-value pairs, to define properties and methods. This power to sculpt data into custom, reusable entities is what makes objects the cornerstones of complex applications.

# Basics : 
+ Now, we’ve just scratched the surface! There’s a whole ocean of advanced object features to explore, like private properties, getters and setters, and object destructuring . Each adds another layer of complexity and flexibility, empowering you to build intricate and efficient code.

# A Newfound Appreciation for Objects : 
+ By understanding the internal representation of objects, we gain a deeper appreciation for their power and flexibility. We see them not just as bags of data, but as intricate mechanisms, the gears of modern Javascript applications. So, next time you write an object, remember this journey into its inner workings. You’ll see them with newfound respect, as the versatile tools they truly are.