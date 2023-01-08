# gamelogger
Keep track of your collection, choose what to play next, log your plays

```mermaid
graph LR
    B(App)
    B --> C{POST}
    B --> D{GET}

    C --> E(Log Plays)
    C --> F(Log Games)
    C --> J(Create User)

    D --> G(Plays Data)
    D --> H(Games List)
    D --> I(Suggestions)
    D --> K(User Data)
```