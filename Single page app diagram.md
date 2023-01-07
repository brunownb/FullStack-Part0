```mermaid
sequenceDiagram
browser->>Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/spa
Server-->>browser: HTML-code
browser->>Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/main.css
Server-->>browser: main.css
browser->>Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/spa.js
Server-->>browser: spa.js
browser->>Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/data.json
Server-->>browser: data.json
```