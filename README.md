# GWB Checker

Interactive viewer / editor for [GeodynamicWorldBuilder](https://github.com/GeodynamicWorldBuilder/WorldBuilder) `.wb` files.

Paste a `.wb` JSON, see the features drawn in map view, drag control points to edit,
cut arbitrary A–A′ / B–B′ cross sections coloured by composition model, and copy the
edited script back out.

**Live:** https://wanlin001.github.io/gwb-checker/

- Runs entirely in the browser — nothing is uploaded.
- 中文 / English interface (toggle at top right, remembered in `localStorage`).

## Local use

Just open `index.html`, or:

```
python3 -m http.server 8000
```

## License

MIT
