# 💖 Para Ashly

Una pequeña página web **interactiva** hecha con cariño: corazones que flotan,
piropos que salen al tocar la pantalla, mensajes con efecto de máquina de
escribir y una lluvia de corazones al final.

Todo está en un solo archivo (`index.html`) — no necesita instalar nada.

## 🌐 Publicarla en internet (para mandar el link)

El repo ya trae un **workflow** que la sube sola a **GitHub Pages**. Solo tienes
que activarlo una vez:

1. Sube los archivos a GitHub:
   ```bash
   git add .
   git commit -m "Página para Ashly 💖"
   git push
   ```
2. En GitHub, entra a tu repo → **Settings** → **Pages**.
3. En **Build and deployment → Source**, elige **GitHub Actions**.
4. Espera ~1 minuto. Tu link quedará así:
   **https://142563.github.io/Ashly/**

Cada vez que hagas `git push`, la página se actualiza sola. ✨

## ✏️ Cambiar textos y piropos

Abre `index.html` y busca el bloque **"Personaliza aquí"** (cerca del final).
Ahí puedes cambiar:

- `NOMBRE` — el nombre de ella.
- `PIROPOS` — la lista de cositas bonitas que salen al tocar.
- `TW1` y `TW2` — los dos mensajes largos que se escriben solos.

> Ojo: el nombre también aparece escrito en el texto de las escenas (busca
> "Ashly" en el HTML) por si quieres ajustarlo a mano.

## 📱 Probarla en tu compu

Solo haz doble clic en `index.html` y se abre en el navegador. El botón 🔇
arriba a la derecha activa un sonidito suave.
