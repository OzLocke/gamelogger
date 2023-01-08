```mermaid
erDiagram
    User }|..o{ Games : owns
    Games ||..o{ Plays : "has been played"
    User }|..o{ Plays : "has played"
    User }|..o{ Plays : "has won"
```