# Slowappka

Reactowa aplikacja Vite do nauki slowek i zdan z lokalnych pakietow JSON oraz wlasnych zestawow zapisanych w przegladarce.

## Komendy

```bash
npm install
npm run dev
npm run build
npm run preview
npm run lint
```

## Struktura

- `src/` - kod aplikacji React.
- `src/data/` - wbudowane zestawy importowane bezposrednio w aplikacji.
- `sets/` - lokalne pakiety JSON ladowane przez `import.meta.glob('/sets/*.json')`.
- `dist/` - zbudowana wersja publikowana przez GitHub Pages.

Wlasne zestawy tworzone w aplikacji sa przechowywane w `localStorage`.
