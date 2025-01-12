# IoT Monitoring Tool

Acest proiect ajută la monitorizarea dispozitivelor IoT într-o rețea locală folosind FastAPI și `arp-scan`.

## Cum funcționează
- Detectează dispozitivele conectate în rețea.
- Oferă un endpoint API pentru listarea dispozitivelor.

## Instrucțiuni
1. Instalează dependențele necesare:
   ```bash
   pip install fastapi uvicorn

Asigură-te că ai instalat arp-scan (pentru Linux).

Rulează in serverul:
Comanda:   python backend/app.py

Accesează API-ul la http://localhost:8000/devices.
         

