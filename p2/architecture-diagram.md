flowchart LR
    subgraph Client-side
        UI[user-interface]
    end

    subgraph Server-side
        S[service]
        DB[(database)]
    end

    UI -- HTTP --> S
    S -- JDBC --> DB

