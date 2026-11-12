# Consulta de calificaciones 2027-1

Sitio estático preparado para GitHub Pages.

## Archivos que se publican

- `index.html`
- `data.json`

## Actualizar calificaciones

1. Coloque `calificaciones_grupos2027-1.xlsx` junto a `jsonconvert.py`.
2. Ejecute:

```powershell
python jsonconvert.py
```

3. Sustituya `data.json` en el repositorio y haga commit/push.

## Publicar en GitHub Pages

1. Cree un repositorio y copie `index.html` y `data.json` en la raíz.
2. En GitHub abra **Settings > Pages**.
3. En **Build and deployment**, seleccione **Deploy from a branch**.
4. Elija la rama `main` y la carpeta `/ (root)`.
5. Guarde los cambios.

> Aviso: GitHub Pages es público. `data.json` puede descargarse aunque la interfaz solicite grupo y boleta. No publique correos, teléfonos ni otros datos adicionales.
