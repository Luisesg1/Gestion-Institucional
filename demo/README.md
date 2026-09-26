# Demo — Inventario Liceo San Martín

Demo estática (un solo `index.html`, sin build, sin dependencias). Vercel la sirve tal cual.

Artifact original: https://claude.ai/code/artifact/53966726-c2c9-4889-8d3c-8b1acf33dbe1

## Opción A — Vercel CLI (más rápido, solo esta carpeta)

```bash
cd demo
npx vercel          # crea preview (login la 1ª vez)
npx vercel --prod   # publica a producción
```

No preguntar build ni output: es sitio estático → dejar todo por defecto (Other).

## Opción B — Dashboard de Vercel (desde GitHub)

1. vercel.com/new → importar el repo `inventario-liceo`.
2. **Root Directory:** `demo`
3. **Framework Preset:** Other
4. **Build Command:** (vacío) · **Output Directory:** (vacío)
5. Deploy.

Cada push al repo redepliega. Para actualizar la demo: reemplazar `demo/index.html` y push.
