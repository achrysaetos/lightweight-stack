# Lightweight Stack

Optimized for DX and speed. Check out the tutorial [here](https://fastapi.tiangolo.com/tutorial/sql-databases/).
1. `python3 -m venv venv` (first time only)
2. `source venv/bin/activate`
3. `pip3 install sqlalchemy pydantic fastapi uvicorn` (first time only)
4. `uvicorn backend.main:app --reload`
5. `cd frontend` && `npm run dev`

**Backend:**
* FastAPI
* SQLite

**Frontend:**
* Vite, React, TypeScript
* Chakra UI
