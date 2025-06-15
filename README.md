# AFClub - Plataforma de Clubes de Lectura

Una plataforma moderna para gestionar y participar en clubes de lectura, inspirada en [Fable.co](https://fable.co/).

## 🚀 Tecnologías

### Frontend
- Next.js 14+
- TypeScript
- Tailwind CSS
- React Query
- Zustand

### Backend
- Node.js
- Express
- TypeScript
- PostgreSQL
- Prisma ORM

## 🛠️ Instalación

### Requisitos Previos
- Node.js 20+
- PostgreSQL
- npm o yarn

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
npm install
# Crear archivo .env basado en .env.example
cp .env.example .env
# Editar .env con tus valores
npm run dev
```

## 📝 Estructura del Proyecto

```
/
├── frontend/          # Aplicación Next.js
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── services/
│   │   └── utils/
│   └── public/
├── backend/           # API Express
│   ├── src/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── models/
│   │   ├── middleware/
│   │   └── utils/
│   └── prisma/
└── shared/           # Tipos compartidos
    └── types/
```

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor, lee [CONTRIBUTING.md](CONTRIBUTING.md) para detalles sobre nuestro código de conducta y el proceso para enviarnos pull requests. 
