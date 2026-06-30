# Personalized Investment Planner for U.S. Migrants

This project is an intelligent financial planning and investment assistant designed explicitly for U.S. immigrants and migrants. It helps users navigate the unique complexities of the U.S. financial system—accounting for visa dynamics (such as OPT or H1B restrictions), cross-border remittances, personal risk tolerances, and cultural financial goals—to build structured, personalized wealth management strategies.

---

## Features
- Dynamic visa-aware investment horizon adjustment (e.g., customized settings for OPT vs. Green Card holders)
- Personalized Dollar-Cost Averaging (SIP) and target asset allocation advice
- Contextual tracking of cross-border financial commitments (remittances)
- Integrated AI conversational assistant for real-time iterative financial planning and follow-ups
- Persistent user state management with full historic audit tracking of generated financial plans

---

## Tech Stack
- **Backend:** FastAPI, Python, OpenAI API (GPT-4)
- **Frontend:** Streamlit
- **Data Persistence:** PostgreSQL / Cloud Database (via Backend API integration)
- **Infra:** Docker, Render.com (Cloud Hosting)

---

## API Endpoints

* `POST /invest` – Process financial profile metadata and generate a personalized investment strategy
* `GET /history` – Retrieve the collection of the last 10 historical financial profiles and strategy plans
