# Mini Jaffle Shop

A compact data engineering project for processing retail order data using Python, PostgreSQL, and SQL.

## Overview

Mini Jaffle Shop demonstrates an end-to-end data pipeline that transforms raw retail data into structured, analysis-ready datasets. The project focuses on data quality, relational database design, and reproducible data processing.

## Tech Stack

- **Language:** Python
- **Database:** PostgreSQL
- **Data Transformation:** SQL
- **Testing:** pytest

## Key Features

- Extract and process raw retail order data.
- Clean and validate records before loading.
- Store structured data in PostgreSQL.
- Use SQL queries to analyze customer orders and sales.
- Test data transformations and validation logic.

## Project Structure

```text
mini-jaffle-shop/
├── data/
│   └── raw/
├── sql/
│   ├── schema.sql
│   └── models/
├── src/
│   ├── extract.py
│   ├── transform.py
│   └── load.py
├── tests/
│   └── test_transform.py
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/mini-jaffle-shop.git
cd mini-jaffle-shop
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

**Windows**
```bash
.venv\Scripts\activate
```

**Linux/macOS**
```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure PostgreSQL

Create a PostgreSQL database and configure the connection using environment variables. Refer to `.env.example` for the required settings.

### 5. Run the pipeline

Pipeline execution commands will be added as the implementation is completed.

## Project Goals

- Build reliable Python data-processing workflows.
- Apply relational database design and SQL querying.
- Implement data validation and automated tests.
- Maintain a clear, reproducible project structure.

## Future Improvements

- Incremental data loading and duplicate prevention.
- Analytical data models for customer and sales metrics.
- Pipeline logging and error handling.
- Data-quality reporting and dashboard integration.

---

**Status:** Under development.
