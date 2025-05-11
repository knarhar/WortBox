# WortBox

A full-stack web application with Django backend and React frontend.

## Project Structure

```
wortbox/
├── frontend/          # React frontend
└── backend/          # Django backend
```

## Backend Setup

1. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run migrations:
```bash
python manage.py migrate
```

4. Start the development server:
```bash
python manage.py runserver
```

The backend will be available at `http://localhost:8000`

## Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
bun install
```

3. Start the development server:
```bash
bun dev
```

The frontend will be available at `http://localhost:3000`

## Development

- Backend API runs on port 8000
- Frontend development server runs on port 3000
- CORS is configured to allow requests from `http://localhost:3000` 