# Personal Library Management System (PLMS)

CSE 443 – Object-Oriented Analysis and Design, Gebze Technical University, Fall 2026
Team **Coastline Software**

| Member | Student ID |
|---|---|
| Ramazan Atakan Giray | 230104004011 |
| Yalçın Eren Onat | 230104004002 |
| Fatih Mehmet Serenli | 220104004012 |

## Deliverable #1 – Requirements Analysis Document

| File | Content |
|---|---|
| [`docs/CSE443_PLMS_RAD_Coastline.pdf`](docs/CSE443_PLMS_RAD_Coastline.pdf) | Requirements Analysis Document, issue 1.1 (PDF) |
| [`docs/CSE443_PLMS_RAD_Coastline.docx`](docs/CSE443_PLMS_RAD_Coastline.docx) | Same document, editable Word version |
| [`docs/diagrams/`](docs/diagrams) | All 19 figures of the document as PNG files |

The document follows the course RAD template:

1. Introduction – purpose, scope, objectives and success criteria, acronyms, references
2. Current system – how personal collections are managed today
3. Proposed system – 82 functional requirements (EARS) in 12 modules, 33 nonfunctional requirements (FURPS+), scenarios, 24 use cases, analysis object model, sequence/activity/state machine diagrams and UI mock-ups
4. Glossary of terms
5. Priority (MoSCoW)
6. Traceability – problem statement → requirements → use cases → analysis classes

## The system in short

PLMS helps the owner of a home collection of books and DVDs (the *librarian*) to catalog items and their physical copies, enrich them with data from Google Books and OMDb, lend copies to friends and family (*patrons*) with due dates, reservations and fines, keep custom lists and track reading/viewing progress.

- **Platforms:** progressive web application (PWA) – runs in the browser and can be installed on Windows, macOS, Linux, Android and iOS.
- **Accounts and sync:** each library belongs to an account; the data is kept in a cloud database and synchronised across the user's devices.
- **Offline:** every device keeps a local copy; everything except registration, password reset, online metadata and e-mail works offline and is synchronised when the connection returns.

## Repository structure

```
CoastlinePLMS/
├── README.md
└── docs/
    ├── CSE443_PLMS_RAD_Coastline.docx
    ├── CSE443_PLMS_RAD_Coastline.pdf
    └── diagrams/        figures 3.1 – 3.19 of the RAD
```

Later deliverables (system design, implementation and tests) will be added to this repository.
