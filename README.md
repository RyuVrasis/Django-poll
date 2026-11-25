Answers to the questions

1. The browser first finds the server's IP address through DNS. It then opens a TCP connection and, for HTTPS, sets up encryption with a TLS handshake. It sends an HTTP request, and the server sends back a response, usually HTML. The browser reads that HTML, fetches the CSS, JS and images it needs, and then draws the page.

2. Servers are computers that provide services to the client by hosting web pages, sites and apps.Clients are internet connected device and the web accessing software thats available on the devices.They talk over network using the TCP,IP protocols with HTTP being the message format.

3. HTTP stands for hyper text transfer protocol.It sets the message format between client and server.Inside request, there 

4. GET is for fetching and accessing data. Its parameters go in the URL, so it can be bookmarked and cached, and well it shouldn't change anything on the server. Searching or opening a page uses GET while POST sends data in the request body and is meant for things that change data, like submitting a form, logging in or voting.

5. 200 - the request worked
   302- the requested web resource has been temporarily moved to different URL
   404- The server cannot find the requested resource. 
   500-It indicates that the web server encountered an unexpected condition that prevents it from fulfilling a request.

6. HTML is for structure and content. All the headings,paragraphs etc are governed by HTML.
CSS is used for presentation for eg color,fonts etc. Javascript is used to make the website interactive.

7. Site remembers you btw pages by the help of cookies and sessions. A cookie is a small text file that a website saves directly on the device through the browser while a session is a temporary data storage space created on the website's server to hold information about users visits.

8. Django technically matches the request's URL against the patterns in urls.py to decide which view is gonna handle it. then the view gets any data it needs from the database through the models, then passes that data to a template to build the HTML. The view returns this as an HttpResponse, which Django sends back to the browser.

9. It basically protects against cross site request forgery where another site makes the browser send a POST with the users cookies attached to the vote URL.


