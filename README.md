# nz-podcast-knowledge-graph

## Overview
 A project to analyze and visualize relationships in New Zealand based podcasts by building a knowledge graph. This repository uses the PodcastIndex API to collect podcast data, processes it to extract entities and relationships, and constructs a structured knowledge graph. Perfect for exploring podcast trends, content connections, and semantic search applications.

## Project Structure 

```
nz-podcast-knowledge-graph/
├── src/
│   ├── db.pkl              # Download the full podcast index sqlite file
│   ├── data_processor.py   # Cleans data & extracts entities
│   └── kg_builder.py       # Neo4j knowledge graph builder
├── data/
│   ├── raw/                # Raw JSON responses
│   └── processed/          # Cleaned CSV/JSON files
├── docs/
│   ├── API_REFERENCE.md    # Podcast Index API integration guide
│   └── DESIGN.md           # Knowledge graph schema
├── tests/                  # Unit & integration tests
└── requirements.txt        # Python dependencies
```

## Data Sources
Data sourced from Podcast Index.
You can download the full podcast index as [a sqlite3 file](https://podcastindex.org/)
Or using API to access the database
For this example I download the database

## How to Contribute
Fork the repository.  
Create a feature branch (git checkout -b feature/your-feature).
Submit a Pull Request.  # nz-podcast-knowledge-graph
