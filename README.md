# Botify Pro

Plataforma de gestión de bots construida con Next.js 14 y FastAPI.

## Stack Tecnológico

- **Frontend**: Next.js 14 (App Router, TypeScript, Tailwind CSS)
- **Backend**: Python FastAPI (Vercel Serverless Functions)

## Estructura del Proyecto

```
Botify_pro/
├── app/              # Next.js App Router
├── api/              # FastAPI backend
│   └── index.py      # Endpoints de la API
├── public/           # Archivos estáticos
├── vercel.json       # Configuración de Vercel
├── requirements.txt  # Dependencias de Python
└── package.json      # Dependencias de Node.js
```

## Desarrollo Local

### Instalar dependencias:

```bash
npm install
```

### Ejecutar el servidor de desarrollo:

```bash
npm run dev
```

El frontend estará disponible en [http://localhost:3000](http://localhost:3000)

## API Endpoints

- `GET /api` - Hello World
- `GET /api/health` - Health check

## Despliegue

El proyecto está configurado para desplegarse en Vercel con soporte para:
- Next.js static y server-side rendering
- Python serverless functions para la API

```bash
vercel deploy
```