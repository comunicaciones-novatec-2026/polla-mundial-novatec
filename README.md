# 🏆 Polla Mundialista Novatec 2026

Dashboard web estático para el seguimiento de la polla del Mundial 2026 de Novatec Solutions.

## Estructura

```
polla-mundial-novatec/
├── index.html          ← Dashboard principal (todo-en-uno)
├── assets/
│   └── logo.png        ← Agrega el logo de Novatec aquí
└── README.md
```

## Uso local

Abre una terminal en esta carpeta y ejecuta cualquiera de estos:

```bash
# Python 3
python3 -m http.server 8080

# Node (npx)
npx serve .

# VS Code: instala la extensión "Live Server" y haz clic en "Go Live"
```

Luego abre `http://localhost:8080` en el navegador.

> **¿Por qué un servidor local?** El navegador bloquea fetch() en archivos `file://` por CORS.
> Con un servidor local funciona correctamente.

## Datos

Lee en tiempo real desde el Google Sheet público:
`https://docs.google.com/spreadsheets/d/1aNkKIpN1w65YvUUi6yOHlw9OO05EUYvCSqeU5nOGXiA`

No requiere API key ni autenticación.

## Actualizar datos

Haz clic en el botón **🔄 Actualizar datos** en la esquina superior derecha del dashboard.
Los datos también se cargan automáticamente al abrir la página.
