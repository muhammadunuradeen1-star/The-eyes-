# The Eyes — Approved User Flows

## Polling Unit Agent

```text
Dashboard
  └── Upload
      └── Election Type
          ├── Presidential Election
          │   └── Election Status
          │       ├── Successful Election
          │       │   ├── Upload Form EC8A
          │       │   ├── Fill E-Form
          │       │   ├── Upload Video
          │       │   └── Upload Duplicate Copy
          │       ├── Over Voting
          │       │   ├── Upload Form EC8A
          │       │   ├── Fill E-Form
          │       │   ├── Upload Video
          │       │   └── Upload Duplicate Copy
          │       └── Violence
          │           ├── Upload Form EC40G
          │           ├── Fill E-Form
          │           ├── Upload Video
          │           └── Upload Duplicate Copy
          ├── National Assembly Election (Senate)
          ├── National Assembly Election (House of Representatives)
          └── Gubernatorial Election
```

The three non-presidential election workflows have their selection screens defined, but their detailed downstream requirements have not yet been fully supplied. Do not invent those workflows.

## Ward Collation Agent

```text
Dashboard
  ├── View Upload
  │   ├── Presidential Election
  │   ├── National Assembly Election (Senate)
  │   ├── National Assembly Election (House of Representatives)
  │   └── Gubernatorial Election
  │
  ├── Upload
  │   ├── Presidential Collation
  │   ├── House of Assembly Collation (Senate)
  │   ├── House of Assembly Collation (House of Reps)
  │   └── Gubernatorial Collation
  │       └── Status
  │           ├── Successful Ward Collation
  │           ├── Over Voting
  │           ├── Violence
  │           └── Expose
  │
  └── Votes
```

### Ward submission evidence

Successful Ward Collation:
- EC8A
- E-Form
- Duplicate Copy
- Video

Over Voting:
- EC8A
- Duplicate Copy
- Video
- E-Form

Violence:
- EC40G
- E-Form
- Video
- Duplicate Copy

Expose:
- Original Copy
- Altered / Fake Copy
