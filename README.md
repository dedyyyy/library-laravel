# library-laravel
for RECRUITMENT MedUp

### Installation 
By using Valet
```
$ cd library-laravel
$ valet park
$ php artisan migrate
```
### Endpoint API

GET http://library-laravel.test/api/library/

POST http://library-laravel.test/api/library/
          with Content-Type application/json and JSON body as
```
{
        "ISBN": "9781449337711",
        "title": "Designing Evolvable Web APIs with ASP.NET",
        "subtitle": "Harnessing the Power of the Web",
        "author": "Glenn Block, et al.",
        "publicationDate": "2007-04-14 00:00:00",
        "publisher": "O'Reilly Media",
        "pages": 538,
        "description": "Design and build Web APIs for a broad range of clients‰ÛÓincluding browsers and mobile devices‰ÛÓthat can adapt to change over time. This practical, hands-on guide takes you through the theory and tools you need to build evolvable HTTP services with Microsoft‰Ûªs ASP.NET Web API framework. In the process, you‰Ûªll learn how design and implement a real-world Web API.",
        "website": "http://chimera.labs.oreilly.com/books/1234000001708/index.html"
    }
```

DELETE http://library-laravel.test/api/library/9781449337711

PUT http://library-laravel.test/api/library/9781449337711
  with Content-Type application/json and JSON body as
```
{
        "ISBN": "9781449337711",
        "title": "Designing Evolvable Web APIs with ASP.NET",
        "subtitle": "Harnessing the Power of the Web",
        "author": "Glenn Block, et al.",
        "publicationDate": "2007-04-14 00:00:00",
        "publisher": "O'Reilly Media",
        "pages": 538,
        "description": "Design and build Web APIs for a broad range of clients‰ÛÓincluding browsers and mobile devices‰ÛÓthat can adapt to change over time. This practical, hands-on guide takes you through the theory and tools you need to build evolvable HTTP services with Microsoft‰Ûªs ASP.NET Web API framework. In the process, you‰Ûªll learn how design and implement a real-world Web API.",
        "website": "http://chimera.labs.oreilly.com/books/1234000001708/index.html"
    }
```



### Dummy data

Sample POST data to endpoint http://library-laravel.test/api/library/
```
[
    {
        "ISBN": "9781449325862",
        "title": "Hehe",
        "subtitle": "A Working Introduction",
        "author": "Richard E. Silverman",
        "publicationDate": "2002-08-13 00:00:00",
        "publisher": "O'Reilly Media",
        "pages": 234,
        "description": "This pocket guide is the perfect on-the-job companion to Git, the distributed version control system. It provides a compact, readable introduction to Git for new users, as well as a reference to common commands and procedures for those of you with Git experience.",
        "website": "http://chimera.labs.oreilly.com/books/1230000000561/index.html"
    },
    {
        "ISBN": "9781449325863",
        "title": "New Post",
        "subtitle": "A Working Introduction",
        "author": "Richard E. Silverman",
        "publicationDate": "2002-08-13 00:00:00",
        "publisher": "O'Reilly Media",
        "pages": 234,
        "description": "This pocket guide is the perfect on-the-job companion to Git, the distributed version control system. It provides a compact, readable introduction to Git for new users, as well as a reference to common commands and procedures for those of you with Git experience.",
        "website": "http://chimera.labs.oreilly.com/books/1230000000561/index.html"
    },
    {
        "ISBN": "9781449331818",
        "title": "Learning JavaScript Design Patterns",
        "subtitle": "A JavaScript and jQuery Developer's Guide",
        "author": "Addy Osmani",
        "publicationDate": "2001-07-12 00:00:00",
        "publisher": "O'Reilly Media",
        "pages": 254,
        "description": "With Learning JavaScript Design Patterns, you'll learn how to write beautiful, structured, and maintainable JavaScript by applying classical and modern design patterns to the language. If you want to keep your code efficient, more manageable, and up-to-date with the latest best practices, this book is for you.",
        "website": "http://www.addyosmani.com/resources/essentialjsdesignpatterns/book/"
    },
    {
        "ISBN": "9781449337711",
        "title": "Designing Evolvable Web APIs with ASP.NET",
        "subtitle": "Harnessing the Power of the Web",
        "author": "Glenn Block, et al.",
        "publicationDate": "2007-04-14 00:00:00",
        "publisher": "O'Reilly Media",
        "pages": 538,
        "description": "Design and build Web APIs for a broad range of clients‰ÛÓincluding browsers and mobile devices‰ÛÓthat can adapt to change over time. This practical, hands-on guide takes you through the theory and tools you need to build evolvable HTTP services with Microsoft‰Ûªs ASP.NET Web API framework. In the process, you‰Ûªll learn how design and implement a real-world Web API.",
        "website": "http://chimera.labs.oreilly.com/books/1234000001708/index.html"
    },
    {
        "ISBN": "9781449365035",
        "title": "Speaking JavaScript",
        "subtitle": "An In-Depth Guide for Programmers",
        "author": "Axel Rauschmayer",
        "publicationDate": "2001-02-14 00:00:00",
        "publisher": "O'Reilly Media",
        "pages": 460,
        "description": "Like it or not, JavaScript is everywhere these days-from browser to server to mobile-and now you, too, need to learn the language or dive deeper than you have. This concise book guides you into and through JavaScript, written by a veteran programmer who once found himself in the same position.",
        "website": "http://speakingjs.com/"
    },
    {
        "ISBN": "9781491904244",
        "title": "You Don't Know JS",
        "subtitle": "ES6 & Beyond",
        "author": "Kyle Simpson",
        "publicationDate": "2027-12-15 00:00:00",
        "publisher": "O'Reilly Media",
        "pages": 278,
        "description": "No matter how much experience you have with JavaScript, odds are you don‰Ûªt fully understand the language. As part of the You Don‰Ûªt Know JS series, this compact guide focuses on new features available in ECMAScript 6 (ES6), the latest version of the standard upon which JavaScript is built.",
        "website": "https://github.com/getify/You-Dont-Know-JS/tree/master/es6%20&%20beyond"
    },
    {
        "ISBN": "9781491950296",
        "title": "Programming JavaScript Applications",
        "subtitle": "Robust Web Architecture with Node, HTML5, and Modern JS Libraries",
        "author": "Eric Elliott",
        "publicationDate": "2001-07-14 00:00:00",
        "publisher": "O'Reilly Media",
        "pages": 254,
        "description": "Take advantage of JavaScript's power to build robust web-scale or enterprise applications that are easy to extend and maintain. By applying the design patterns outlined in this practical book, experienced JavaScript developers will learn how to write flexible and resilient code that's easier-yes, easier-to work with as your code base grows.",
        "website": "http://chimera.labs.oreilly.com/books/1234000000262/index.html"
    },
    {
        "ISBN": "9781593275846",
        "title": "Eloquent JavaScript, Second Edition",
        "subtitle": "A Modern Introduction to Programming",
        "author": "Marijn Haverbeke",
        "publicationDate": "2014-12-14 00:00:00",
        "publisher": "No Starch Press",
        "pages": 472,
        "description": "JavaScript lies at the heart of almost every modern web application, from social apps to the newest browser-based games. Though simple for beginners to pick up and play with, JavaScript is a flexible, complex language that you can use to build full-scale applications.",
        "website": "http://eloquentjavascript.net/"
    },
    {
        "ISBN": "9781593277574",
        "title": "Understanding ECMAScript 6",
        "subtitle": "The Definitive Guide for JavaScript Developers",
        "author": "Nicholas C. Zakas",
        "publicationDate": "2003-09-16 00:00:00",
        "publisher": "No Starch Press",
        "pages": 352,
        "description": "ECMAScript 6 represents the biggest update to the core of JavaScript in the history of the language. In Understanding ECMAScript 6, expert developer Nicholas C. Zakas provides a complete guide to the object types, syntax, and other exciting changes that ECMAScript 6 brings to JavaScript.",
        "website": "https://leanpub.com/understandinges6/read"
    }
]
```
