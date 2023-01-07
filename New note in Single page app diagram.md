```mermaid
sequenceDiagram
User->>Form: write something
User->>Form: click button
Form->>Server: HTTP POST https://fullstack-exampleapp.herokuapp.com/new_note_spa
Server-->>Form: status code 201
```