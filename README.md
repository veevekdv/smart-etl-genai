# Smart ETL with GenAI Enrichment

This project is a **Spring Boot application** that builds a smart ETL pipeline to ingest raw product data, clean it, and enrich missing or inconsistent fields using a Generative AI model. It’s designed for data engineers who want to combine traditional ETL pipelines with modern AI-based data enrichment.

## 🚀 Features

- Read raw data from CSV files.
- Clean and standardize text fields.
- Automatically generate missing descriptions using a GenAI model (e.g., OpenAI GPT).
- Store cleaned and enriched data in a relational database.
- Built with Spring Boot and Spring Batch.
- H2 database for easy local development.
- Expose REST endpoints to trigger and monitor pipeline jobs.

## 📂 Project Structure

- `src/main/java/com/example/smartetl/domain/` — Domain entities.
- `src/main/java/com/example/smartetl/batch/` — ETL job and step configurations.
- `src/main/java/com/example/smartetl/web/` — REST controllers.
- `src/main/resources/products.csv` — Sample input data.

## ⚙️ Technologies

- **Spring Boot** — Application framework.
- **Spring Batch** — ETL pipeline orchestration.
- **Spring Data JPA** — Database persistence.
- **H2** — In-memory database for local dev.
- **OpenAI API** — For AI-based data enrichment (GPT models).

## 🏃 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/smart-etl-genai.git
   cd smart-etl-genai
