A website opens on the screen through communication between a client, browser, server, and database. When a user types a URL (Uniform Resource Locator) into a web browser such as Google Chrome and presses Enter, the browser finds the website's server using DNS (Domain Name System) and sends an HTTP or HTTPS request to it. HTTP stands for Hypertext Transfer Protocol, which is used to transfer data between a browser and a web server, while HTTPS stands for Hypertext Transfer Protocol Secure, which encrypts the communication to protect data. The browser acts as the client, sending requests to the server, and the server processes the request and may retrieve or update information in a database. The server then sends an HTTP response containing a status code and resources such as HTML, CSS, JavaScript, and images. The browser interprets these resources and displays the website on the screen. This process is called the request-response cycle. A static website displays fixed content that generally remains the same for every visitor, whereas a dynamic website can generate or change content based on user input, database information, or other conditions. We can observe this communication by opening Chrome DevTools, selecting the Network tab, and refreshing a website to inspect its requests, responses, status codes, and resource types.

Screenshot of the Network Tab
Insert your own screenshot of Chrome DevTools here after completing the following steps:

Open Google Chrome and visit https://example.com.
Press F12 or Ctrl + Shift + I to open Chrome DevTools.
Select the Network tab.
Refresh the page using Ctrl + R.
Observe the requests and details such as Name, Status, Type, and Size.
Take a screenshot showing the website's network requests and save it as network-tab.png in your assignment folder.