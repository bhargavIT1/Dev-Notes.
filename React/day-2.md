What is Content Delivery Network(CDN)? and What are its use cases?

A Content Delivery Network (CDN) is a group of servers placed in different locations around the world that work together to deliver website content faster to users.

Think of it like this:

Imagine Netflix has only one server in the USA.
If someone from India watches a movie, the data has to travel a very long distance, so loading becomes slower.

Now imagine Netflix stores copies of that content on servers in many countries, including India.
When you open Netflix in India, the content is delivered from the nearest server instead of the USA.
That nearby server is part of a CDN.

What does a CDN store?

CDNs mainly store:

Images
Videos
CSS files
JavaScript files
Fonts
Website pages
App downloads

These are called static assets.

Main Uses of CDN
1. Faster Website Loading

The biggest use.

A CDN sends data from the closest server to the user, reducing distance and loading time.

Example:

Without CDN → Server in USA serves Indian user
With CDN → Indian CDN server serves Indian user

Result:

Faster websites
Faster video streaming
Better user experience
2. Reduces Load on Main Server

Instead of millions of users hitting one server, the traffic gets distributed across many CDN servers.

This prevents:

Server overload
Crashes during heavy traffic
3. Better Performance During High Traffic

Websites like:

Amazon
YouTube
Facebook

use CDNs because millions of users access them simultaneously.

4. Protection Against DDoS Attacks

A CDN can absorb huge amounts of fake traffic and protect the original server.

This improves security.

5. Improves Availability


So websites remain online even during failures.
If one CDN server fails, another nearby server can still deliver content.

Cross Origin:
 The crossorigin attribute in the script tag enables CrossOrigin Resource Sharing (CORS) for loading external JavaScript
files from different origin than the hosting web page. This
allows the script to access resources from the server hosting
the script, such as making HTTP requests or accessing data.

