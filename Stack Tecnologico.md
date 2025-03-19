### 🌐 **Frontend** (Separado del backend, en TypeScript)

- **Framework:** [Next.js](https://nextjs.org/) (SSR/SSG para mejor rendimiento y SEO)
    
- **UI:** [Tailwind CSS](https://tailwindcss.com/) (rápido y elegante)
    
- **State Management:** [Zustand](https://github.com/pmndrs/zustand) (más simple que Redux)
    
- **Componentes UI:** ShadCN (elegante y personalizable)
    
- **Autenticación:** NextAuth.js (fácil integración con Firebase)
    

### ⚙ **Backend** (TypeScript y PostgreSQL)

- **Framework:** [NestJS](https://nestjs.com/) (estructura modular y escalable)
    
- **ORM:** [Prisma](https://www.prisma.io/) (manejo de base de datos intuitivo)
    
- **Autenticación:** Firebase Auth + JWT
    
- **API:** REST o GraphQL (según necesidad)
    
- **Mensajería en tiempo real:** [Redis](https://redis.io/) con WebSockets
    

### 🧠 **Módulo de Cámaras de Seguridad (AI con Python y Firebase)**

- **Procesamiento de Video:** OpenCV + TensorFlow/PyTorch
    
- **Almacenamiento:** Firebase Storage
    
- **Base de Datos:** Firebase Firestore (para eventos de detección)
    
- **Backend de AI:** FastAPI (rápido y ligero para Python)
    

### 📦 **Infraestructura y DevOps**

- **Base de Datos:** PostgreSQL (puede estar en AWS RDS, Supabase o Railway)
    
- **Almacenamiento en la Nube:** Firebase Storage o S3
    
- **CI/CD:** GitHub Actions
    
- **Contenedores:** Docker
    
- **Hosting:** Vercel (para frontend) + AWS/GCP para backend