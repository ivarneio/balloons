# balloons

Õhupallileht. Luu on see `index.html`. Nahk on JSON.

Sündmusi ei ole. Pildid on neli galeriid.

## Lukus

`index.html` — riba, kangelane, kastide avamine, neli galeriid, raamat, keeled.

## Sina muudad

- `tekstid.json` — nupud, pealkirjad, menüü (et / en / ru / tr)
- `sisu.json` — pikad lõigud
- `seaded.json` — telefon, Facebook, Instagram
- `pildid.json` — neli galeriid (`id`, `pealkiri`, `pildid`)
- `pildid/` — failid, mille nimed on `pildid.json` sees
- `hero.jpg`, `hero-mobiil.jpg`, `parmu.jpg`

## pildid.json

```json
[
  { "id": "figuurid", "pealkiri": { "et": "Figuurid" }, "pildid": ["koer.jpg"] },
  { "id": "kaared", "pealkiri": { "et": "Kaared" }, "pildid": ["kaar.jpg"] },
  { "id": "peod", "pealkiri": { "et": "Peod" }, "pildid": ["pidu.jpg"] },
  { "id": "kingitused", "pealkiri": { "et": "Kingitused" }, "pildid": ["kink.jpg"] }
]
```

Kaanepilt on iga galerii esimene fail. Suur vaade näitab ainult selle galerii pilte.
