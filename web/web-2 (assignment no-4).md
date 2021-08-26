```sequence
browser->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note

server-->browser: no response

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes

server-->browser: HTML-code

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css

server-->browser: main.css

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js

server-->browser: main.js

browser->server:  HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json

server-->browser: [{content: "Hello from Australia!", date: "2021-08-16T10:12:07.824Z"}]



browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js

server-->browser: main.js




```

