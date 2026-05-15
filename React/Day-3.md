What is defer?

If we run a web page in the browser using only JavaScript, the problem is that HTML parsing stops. This means the browser stops reading and understanding the HTML code because it is busy downloading and executing the JavaScript code, which can slow down the page loading process.
But if we use defer, the HTML will continue to parse while the JavaScript is being downloaded. After the HTML is fully parsed, the JavaScript will execute.So, defer does not block HTML parsing, executes JavaScript after the HTML loads, and maintains the order of scripts.
