# FabricAI: Intelligent Textile & Custom Garment Generation Engine

An AI-assisted multimodal application designed to transform raw fabric imagery and tailored measurement schemas into diverse garment design variations.

## Overview
- **Multimodal Ingestion:** Ingests fabric swatches (texture, weave, color) along with structured user measurement specs.
- **Design Synthesis:** Leverages Claude Vision and generative pipelines to produce diverse tailoring styles and pattern placements.
- **Tiered Access:** In-memory rate limiting and tier controls to explore free-tier vs. full-palette generation.

## Tech Stack
- **Frontend:** React / Next.js
- **Backend:** Python (FastAPI), Pydantic
- **AI/LLM:** Claude Code / Anthropic Vision API
- **Storage:** SQLite / PostgreSQL
