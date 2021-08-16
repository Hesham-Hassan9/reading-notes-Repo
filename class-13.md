# The past, present and future of local storage for web applications:

Persistent local storage is one area where native client applications have an advantage over web applications. For native applications, the operating system usually provides an abstraction layer to store and retrieve application-specific data such as preferences or runtime state. These values may be stored in the registry, INI files, XML files, or elsewhere depending on the platform agreement. If your native client application needs local storage beyond key/value pairs, you can include your own database, come up with your own file format, or any number of other solutions.

Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

What we really want is

* a lot of storage space
* on the client
* that persists beyond a page refresh
* and isn’t transmitted to the server

Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.

## A Brief History of Local Storage Hacking Before HTML5
Initially, there was only Internet Explorer browser. Or at least, that's what Microsoft wanted the world to think. To that end, and as part of the first major browser wars, Microsoft invented many cool things and included them in their browser wars, namely Internet Explorer. One of those things was called DHTML behaviors, and one of those behaviors was called userData. userData allows web pages to store up to 64KB of data per domain, in an XML-based hierarchical structure. (Trusted domains, such as intranet sites, can store 10 times that much. And hey, 640KB should be enough for anyone.) IE doesn't offer any form of permissions dialog, and there's no allow-in available.

## Input storage in HTML5
What I will refer to as "HTML5 Storage" is a specification called Web Storage, which at one time was part of the proper HTML5 specification, but was broken down into its own specification for uninteresting political reasons. Some browser vendors also refer to "Local Storage" or "DOM Storage". The naming situation is made more complicated by some related emerging standards, with similar names, which I will discuss later in this chapter.

## Use HTML5 storage
HTML5 storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The specified key is a string. Data can be of any type supported by JavaScript, including strings, booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to force the retrieved data to the expected JavaScript data type.

## HTML5 storage in progress
Let's see HTML5 storage in action. Relive the Halma game we created in the board class. There is a small problem with the game: if you close the browser window in the middle of the game, you will lose your progress. But with HTML5 storage, we can save progress locally, within the browser itself. Here is a live show. Make a few moves, then close the browser tab, and then reopen it. If your browser supports HTML5 storage, the demo page should magically remember your exact location within the game, including the number of moves you've made, the position of each piece on the board, and even whether a particular piece is selected.