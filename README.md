# LibrarySim
A python program that simulates a library. Users are able to check out and return books. We will use the Open Library API to get information about the books.

library_simulator/
├── src/                     # All source code lives here
│   ├── __init__.py          # Makes 'src' a recognizable Python package
│   ├── main.py              # The entry point that ties everything together
│   ├── models.py            # Defines data structures (Book, Patron, Checkout)
│   ├── database.py          # Handles all sqlite3 connections and SQL queries
│   ├── api_client.py        # Manages the urllib requests to the Open Library API
│   └── ui.py                # Contains our cmd loop or tkinter visual elements
├── data/                    # Directory for local, persistent storage
│   └── library.db           # The SQLite database file (created automatically)
├── docs/                    # For system specifications
│   └── architecture.md      # Great for storing UML diagrams or design notes
├── .gitignore               # Tells Git to ignore files like library.db or __pycache__/
└── README.md                # Project overview, setup steps, and run instructions
