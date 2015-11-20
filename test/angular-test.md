<!--
{
"name" : "angular-test",
"version" : "0.1",
"title" : "Angular Concepts",
"description" : "Dive into AngularJS",
"tags" : "angularjs, javascript",
"freshnessDate" : 2015-06-01,
"license" : "CC BY 3.0"
}
-->


<!-- @section -->

# Conceptual Overview



Basic link

<!-- @link, "url" : "https://nodejs.org" -->

Basic link w text

<!-- @link, "url" : "https://nodejs.org", "text": "Install NodeJS" -->

Override link

<!-- @link, "url" : "https://nodejs.org", "text": "Learn more about Node.js", "imageUrl" : "http://code-maven.com/img/node.png", "title": "Official Node.js site", "description": "Node.js is a JavaScript runtime which uses an event-driven, non-blocking I/O model that makes it lightweight and efficient." -->

Not over-riden link with screenshot

<!-- @link, "url" : "https://nodejs.org", "text": "Install NodeJS", "prefer" : "screenshot" -->

Override link with screenshot

<!-- @link, "url" : "https://nodejs.org", "text": "Put to practice NodeJS", "imageUrl" : "http://code-maven.com/img/node.png", "title": "Node with Wiki", "description": "Best description ever, take this to heart and remember it for ages to come." , "prefer" : "screenshot" -->

Youtube videos

<!-- @link, "url" : "https://www.youtube.com/watch?v=5MgBikgcWnY", "text": "Install NodeJS", "prefer" : "embed" -->
<!-- @link, "url" : "https://www.youtube.com/watch?v=5MgBikgcWnY", "text": "Install NodeJS", "prefer" : "screenshot" -->
<!-- @link, "url" : "https://www.youtube.com/watch?v=5MgBikgcWnY", "text": "Install NodeJS" -->


Here we see that iframeable works.

<!-- @link, "url" : "https://nodejs.org", "text": "Install NodeJS", "iframeable" : true -->
