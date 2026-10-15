# ReviewLens

**Development of a Web-Based User Review Analysis System to Support Managerial Decision-Making in Food Service Chains.**

## Project Overview
ReviewLens is an analytical B2B web platform designed for food-service chains. The system aggregates customer reviews from permitted sources and utilizes machine learning (Aspect-Based Sentiment Analysis) to analyze sentiment across six key operational metrics: food, service, price, atmosphere, cleanliness, and speed. 

The platform is specifically designed to process texts in Russian, Kazakh, and mixed languages (including code-switching within a single sentence). This provides branch managers and chain owners with precise, actionable insights rather than abstract star ratings.

## Team and Responsibilities
* **Dinmukhamed Zhambulkhan:** Frontend (React/TS), UX design, ML dataset preparation, NLP service development (Python/FastAPI).
* **Serik Aitkazyyev:** Backend (Spring Boot), Database design (PostgreSQL), RBAC (Role-Based Access Control) implementation, CSV import pipeline.
* **Academic Supervisor:** Orazova Arailym Zhanbolatkyzy.

## Technology Stack
* **Frontend:** React, TypeScript, Vite.
* **Backend:** Java (Spring Boot, Spring Security).
* **Database:** PostgreSQL (with Flyway migrations).
* **ML / NLP:** Python, FastAPI, XLM-R (Transformers), TF-IDF.

## Repository Structure
* `docs/` - Project documentation, requirements
* `diagrams/` - Architectural diagrams (System Context, Use Cases, ERD, Component, Sequence) in PNG and source .drawio formats.
* `src/` - Source code for the system (Frontend, Backend, ML service - currently in development).

## System Prototype (UX)
The interactive map-first prototype is available at the following link:
[Figma Prototype: ReviewLens](https://www.figma.com/proto/ipjaR2S6O2tREbeMLZ9ovc/ReviewLens-%E2%80%94-Astana-Branch-Analytics-UX-%7C-Bilingual-MVP?node-id=2-27&p=f&t=PothkLp4mmfbt0bp-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2)

## Project Status
* **Phase:** Architecture design and requirements analysis.
* Task tracking and project management are formally conducted via our repository's issue tracker: [GitHub Issues Board](https://github.com/Zhmblkhn/restaurant-review-analyzer/issues).