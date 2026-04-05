You are a senior AI engineer, bioinformatics researcher, and full-stack architect.

Upgrade my existing project "BioGPT - DNA AI Web Application using NVIDIA Evo2" into a 10/10 production-grade, research-level platform with advanced AI, biological validation, and scalable architecture.

Current Stack:
- Backend: FastAPI (Python)
- Frontend: Next.js + Tailwind CSS
- AI: NVIDIA Evo2 API (DNA generation)
- Deployment: Vercel + Render

Your task is to TRANSFORM this into an industry-level + GSoC-winning + research-grade project.

---

### 1. ARCHITECTURE UPGRADE
Redesign the system with:
- Modular backend (routers, services, utils)
- Add database (PostgreSQL or MongoDB)
- Add Redis caching (for generation results)
- Add background workers (Celery / FastAPI BackgroundTasks)
- Clean folder structure with scalability in mind

---

### 2. AUTHENTICATION SYSTEM
Implement:
- JWT-based authentication
- Signup/Login APIs
- Protected routes
- User-specific generation history stored in DB

---

### 3. BIOLOGICAL INTELLIGENCE LAYER (VERY IMPORTANT)
Add real bioinformatics logic:
- GC content calculation
- Sequence validation (only A, T, G, C)
- Motif detection (start/stop codons like ATG, TAA, TAG, TGA)
- Sequence scoring system
- Mutation simulation (random + controlled)
- FASTA format support (import/export)

---

### 4. ADVANCED AI PIPELINE
Improve prompt → DNA conversion:
- Use embedding-based semantic mapping
- Improve seed generation algorithm
- Add multi-model support (future-ready design)
- Add deterministic + stochastic modes
- Add parameter presets (scientific, creative, stable)

---

### 5. ANALYTICS DASHBOARD
Create frontend dashboard with:
- GC content visualization (charts)
- Sequence length distribution
- Mutation comparison view
- History analytics
- Use chart libraries (Recharts or Chart.js)

---

### 6. FRONTEND ENHANCEMENT
Upgrade UI:
- Add tabs (Generate | History | Analytics)
- Add loading skeletons
- Add error boundaries
- Improve DNA visualization (color + grouping)
- Add dark/light mode
- Add drag & drop FASTA upload

---

### 7. PUBLIC API + RATE LIMITING
Expose:
- Public API endpoints
- API key system
- Rate limiting (per user/IP)

---

### 8. TESTING + CI/CD
Add:
- Unit tests (pytest)
- API tests
- GitHub Actions pipeline
- Linting + formatting

---

### 9. DEPLOYMENT IMPROVEMENT
Make it production-grade:
- Dockerize backend
- Use environment-based configs
- Add logging + monitoring
- Setup scalable deployment (Render/Vercel ready)

---

### 10. BONUS (MAKE IT STAND OUT)
Add at least 2 of these:
- BLAST-like similarity checker
- Sequence comparison tool
- Download as FASTA/JSON
- Shareable result links
- Real-time collaboration (optional)

---

### OUTPUT FORMAT
Give me:
1. Full upgraded folder structure
2. Backend code (modular FastAPI)
3. Frontend code (Next.js components)
4. Database schema
5. Key algorithms (GC content, mutation, etc.)
6. Deployment steps
7. Final improved README.md (professional, resume-ready)

Make everything clean, modular, production-ready, and easy to run.

DO NOT give explanations — give full implementation.
