# test-cicd
Tarea 2: Administración de sitios web (principios básicos de CI/CD y despliegue de sitios web utilizando herramientas gratuitas)


---

## 🚀 Despliegue automático

Este proyecto utiliza **GitHub Actions + GitHub Pages**.

### 🔄 ¿Cuándo se despliega?

El sitio se publica automáticamente cuando:

- ✔️ Se hace **merge a la rama `main`**

---

## ⚙️ Workflow (GitHub Actions)

El flujo realiza:

1. 📥 Checkout del repositorio  
2. 📦 Empaquetado del sitio  
3. 🌍 Deploy en GitHub Pages  

Ubicación del workflow:
.github/workflows/deploy.yml

---

## 🌍 Ver sitio en producción

Una vez desplegado, podrás verlo en:
