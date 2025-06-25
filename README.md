# Simple Website
## Info
Simple static website

---

## Stack

- Node.js + Jest (tests)
- Docker (deploy)
- GitHub Actions (CI/CD)
- Nginx (static web server)
- SSH deploy on VPS

---

## Local launch

```bash
npm install        
npm test           
npm run build    
docker build -t my-web-site .
docker run -p 8080:80 my-web-site
