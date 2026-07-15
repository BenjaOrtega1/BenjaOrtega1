# Publicación del perfil

## 1. Crear el repositorio especial

1. En GitHub, crea un repositorio público llamado exactamente `BenjaOrtega1`.
2. No agregues una plantilla inicial si subirás este paquete mediante Git.
3. Copia todo el contenido de esta carpeta a la raíz del repositorio.

## 2. Subir los archivos

```bash
git init
git add .
git commit -m "feat: create professional GitHub profile"
git branch -M main
git remote add origin https://github.com/BenjaOrtega1/BenjaOrtega1.git
git push -u origin main
```

## 3. Generar la animación de contribuciones

1. Abre la pestaña **Actions** del repositorio.
2. Selecciona **Generate contribution snake**.
3. Pulsa **Run workflow**.
4. El workflow generará la rama `output`.
5. Al terminar, recarga el perfil. La animación aparecerá automáticamente.

El workflow solicita únicamente `contents: write`, necesario para publicar los SVG en la rama `output`.

## 4. Configuración recomendada del perfil

- **Nombre:** Benjamin Ortega
- **Bio:** Software Developer | React, Supabase & IoT | Construyo soluciones que conectan interfaces, datos y dispositivos.
- **Ubicación:** Chillán, Chile
- **Sitio:** https://tecnoprint3d.cl
- **Estado:** Disponible para práctica profesional 💻

## 5. Repositorios para fijar

GitHub permite fijar hasta seis elementos. Orden recomendado:

1. Ofta-Life
2. CasaDolce
3. prototipo_curimapu
4. Invernadero
5. EstacionCalidadChill-n
6. Futuro repositorio público de TecnoPrint3D o portafolio personal

## 6. Revisión rápida

- Comprueba que las demos de Vercel continúen activas.
- Ejecuta el workflow una vez después de la primera publicación.
- Agrega LinkedIn al bloque de contacto cuando exista una URL pública definitiva.
- Actualiza la frase “estudiante de 4.º año” al cambiar tu situación académica.
