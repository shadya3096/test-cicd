# test-cicd
Tarea 2: Administración de sitios web (principios básicos de CI/CD y despliegue de sitios web utilizando herramientas gratuitas)


---

## 🚀 Despliegue automático

Este proyecto utiliza **GitHub Actions + GitHub Pages**.

### 📌 Descripción

Este proyecto implementa un flujo de integración y despliegue continuo (CI/CD) utilizando **GitHub Actions** para publicar automáticamente un sitio web estático en **GitHub Pages**.

El objetivo principal es automatizar el proceso de despliegue cada vez que se realizan cambios en la rama principal (`main`), específicamente cuando se hace merge de un Pull Request.

---

## ⚙️ ¿Cómo se configuró el workflow?

El workflow fue configurado mediante un archivo YAML ubicado en la siguiente ruta:
.github/workflows/deploy.yml


### 🔄 Evento que dispara el workflow

El flujo se ejecuta automáticamente cuando ocurre un evento de tipo:

- `push` sobre la rama `main`

Esto permite que cada vez que se haga merge de un Pull Request a `main`, el despliegue se realice sin intervención manual.

```yaml
on:
  push:
    branches:
      - main

---

## 🌍 Ver sitio en producción

Una vez desplegado, podrás verlo en:
https://shadya3096.github.io/test-cicd/
