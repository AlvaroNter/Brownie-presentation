# Brownie · Presentación de funcionalidades Shopify

Sitio web de una sola página (scroll) que resume la propuesta de nuevas
funcionalidades de Shopify para Brownie.

## Archivos
- `index.html` — estructura y contenido
- `styles.css` — diseño editorial (paleta crema/caramelo, tipografías Cormorant Garamond + Jost)
- `script.js` — nav fija y animaciones de aparición al hacer scroll
- `netlify.toml` — configuración de publicación
- `informe.md` — contenido original

## Ver en local
Abre `index.html` en el navegador, o sirve la carpeta:
```
npx serve .
```

## Publicar en Netlify

### Opción A — Netlify Drop (lo más rápido, sin cuenta técnica)
1. Entra en https://app.netlify.com/drop
2. Arrastra **toda esta carpeta** a la zona de subida.
3. Listo: obtienes una URL pública al instante. Puedes renombrar el sitio en
   *Site settings → Change site name*.

### Opción B — Netlify CLI
```
npm install -g netlify-cli
netlify login
netlify deploy --dir . --prod
```
