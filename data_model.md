
# Project Members only

```mermaid
---
title: Micro reddit
---
erDiagram
    USER ||--o{ POST : write
    USER {
        int id
        string name
        string email
        string password
        datetime created_at
        datetime updated_at
    }
    POST {
        int id
        string title
        text body
        int author_id 
        datetime created_at
        datetime updated_at
    }
```