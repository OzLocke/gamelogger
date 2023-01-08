```mermaid
erDiagram
    User }|..o{ Games : ownership
    Games ||..o{ Plays : "has had"
    User }|..o{ Plays : "has had"
```