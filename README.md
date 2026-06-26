# TDE Módulo 2 — API REST com Flask

API REST com Flask para o TDE do Módulo 2 — Cibersegurança UFU.

## Rodar

```bash
pip install flask requests
python servidor.py
```

## Rotas

- `GET /api/soma?a=2&b=3` — soma via URL
- `POST /api/soma` — soma via corpo JSON
- `GET /api/protegido` — rota protegida por Bearer token