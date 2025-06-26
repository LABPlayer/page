# page

This project uses MkDocs with the Material theme to generate a static website.

## Getting Started

### Prerequisites

- Python 3

### Setup

1.  **Create and activate a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

2.  **Install dependencies:**
    ```bash
    pip install mkdocs-material
    ```

### Running the Development Server

To start the local development server, run the following command. The site will be available at `http://127.0.0.1:8000`.

```bash
mkdocs serve
```

### Building the Site

To build the static site, run the following command. The static files will be generated in the `site` directory.

```bash
mkdocs build
```
