# Frontend Application

This directory contains the Django web application.

## Quick Start

1. **Create virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set environment variables:**
   ```bash
   export DJANGO_SECRET_KEY="your-secret-key"
   export DJANGO_ALLOWED_HOSTS="localhost,127.0.0.1"
   export DJANGO_DEBUG="true"
   ```

4. **Run application:**
   ```bash
   python django_app.py runserver
   ```

5. **Access application:**
   - Open http://localhost:8000 in your browser

## Files

- `django_app.py` - Main Django application
- `requirements.txt` - Python dependencies

## Environment Variables

- `DJANGO_SECRET_KEY` - Secret key (required)
- `DJANGO_ALLOWED_HOSTS` - Allowed hosts (comma-separated)
- `DJANGO_DEBUG` - Debug mode (true/false)

## Development

```bash
# Run in development mode
export DJANGO_DEBUG="true"
python django_app.py runserver

# Run tests (if any)
python django_app.py test
```