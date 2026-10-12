# Nargiz — 13 oktyabr

Tək fayllı statik sayt (`index.html`). Build yoxdur.

## Şəkillər

Şəkilləri `photos/` qovluğuna bu adlarla qoy:

- `photos/nargiz-1.jpg` — sol kart ("та самая улыбка")
- `photos/nargiz-2.jpg` — orta kart ("именинница")
- `photos/nargiz-3.jpg` — sağ kart ("всегда на высоте")

Fayl yoxdursa, kart avtomatik köhnə Unsplash şəklini göstərir. Şaquli
(4:5) şəkillər ən yaxşı görünür. Hər birini ~1400px enə qədər kiçilt.

## Vercel

Vercel → Add New → Project → bu repo → Framework: **Other**, build
command boş, output directory boş → Deploy.

## Lokal baxış

```bash
python3 -m http.server 8000   # sonra http://localhost:8000
```
