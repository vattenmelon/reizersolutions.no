# reizersolutions.no

Nettsiden til Reizer Solutions AS (org.nr. 936 734 146). Statisk HTML og CSS uten byggesteg, publisert med GitHub Pages.

## Filer

- `index.html` – forsiden
- `assets/styles.css` – stilark
- `favicon.svg` – ikon
- `404.html` – feilside
- `CNAME` – eget domene for GitHub Pages

## Publisering

1. Push til `main`.
2. I repoet på GitHub: Settings → Pages → Source: «Deploy from a branch», branch `main`, folder `/ (root)`.
3. Pek DNS for `reizersolutions.no` til GitHub Pages (A-poster 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153, og CNAME `www` → `vattenmelon.github.io`).

Skal siden kun ligge på `vattenmelon.github.io/reizersolutions.no`, slett `CNAME`.

## Lokal forhåndsvisning

```
python3 -m http.server 8000
```

Åpne <http://localhost:8000>.
