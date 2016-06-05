---
layout: post
title: Chrome Developer Tools
---
Chrome Developer Tools

Most browsers have what are known as Developer Tools. These tools allow us to inspect an element on a page, see where that element lives within the HTML document, and see what CSS properties and values are being applied to it. Most of these tools also include a box model diagram to show the computed size of an element.

To see the Developer Tools in Google Chrome, click “View” within the menu bar and navigate to “Developer” and then “Developer Tools.” This loads a drawer at the bottom of the browser window that provides a handful of tools for inspecting our code.

Clicking the magnifying glass at the bottom of this drawer enables us to hover over and then click on different elements on the page to review more information about them.

Overall, there are eight main groups of tools available view Developer Tools:

Elements
Resources
Network
Sources
Timeline
Profiles
Audits
Console

Elements

The Elements panel lets you view structured information about the current page. You can use the Elements panel for a variety of tasks:

Inspect the HTML & CSS of a web page.
Test different layouts.
Live-edit CSS.

Resources

The Resources panel lets you inspect your application's local data sources, including IndexedDB, Web SQL databases, local and session storage, cookies, and Application Cache resources. You can also quickly inspect your application's visual resources, including images, fonts, and stylesheets.

Network

The Network panel records information about each network operation in your application, including detailed timing data, HTTP request and response headers, cookies, WebSocket data, and more. The Network panel helps you answer questions about the network performance of your web application, such as:

Which resources took the longest time to load (duration)?
Who initiated a particular network request?
How much time was spent in the various network phases for a particular resource?

Timeline

The Timeline panel lets you record and analyze all the activity in your application as it runs. It's the best place to start investigating perceived performance issues in your application.

Profiles

The Profiles panel lets you profile the execution time and memory usage of a web app or page.

Audits

The Audit panel can analyze a page as it loads. Then provides suggestions and optimizations for decreasing page load time and increase perceived (and real) responsiveness. 

Console

Utilizing the console gives you the ability to:

Log diagnostic information to help debug your web page or application.
Enter commands that interact with the document and the Chrome DevTools. You also may evaluate normal JavaScript expressions. 
