# Demo assets (bundled with the template)

These files ship with the marketplace template so buyers can run a working storefront **without supplying their own images or 3D models**.

## Product thumbnails (`products/`)

| File | License |
|------|---------|
| `*.svg` / `*.png` | MIT — created for this project, free to modify and redistribute |

Use paths like `assets/demo/products/bag.png` in seed data or admin product images.

## 3D models (`models/`)

Lightweight demo GLBs (~2–3 MB) ship in the buyer zip:

| Path | Use |
|------|-----|
| `assets/demo/models/bag-demo.glb` | Bags category |
| `assets/demo/models/shoes-demo.glb` | Shoes category |

Seed and storefront defaults point here. Upload your own `.glb` via Admin → Products for production catalogs.

Optional Khronos CC0 samples (`avocado.glb`, `water-bottle.glb`):

```bash
npm run demo:models
```

Heavy photogrammetry sources under `src/assets/models/` are **not** included in the marketplace zip (size limit). See `docs/CUSTOMIZATION.md`.
