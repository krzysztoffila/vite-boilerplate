# Vite z Tailwind CSS Boilerplate

## Instalacja

1. Sklonuj repozytorium:

```bash
git clone git@github.com:krzysztoffila/vite-boilerplate.git
cd vite-boilerplate
```

2. Instalacja
```bash
npm install
```

3. Uruchom lokalny serwer deweloperski:
```bash
npm run dev
```

## Build
Aby zbudować projekt do produkcji, wykonaj poniższą komendę:
```bash
npm run build
```
Wynikiem będzie gotowy do wdrożenia folder 'dist'.

# Dodawanie nowych styli Tailwind CSS

Edytuj plik `src/styles/index.css` aby dodać niestandardowe style Tailwind. Przykład:

```css
/* src/styles/index.css */

@import 'tailwindcss/base';
@import 'tailwindcss/components';
@import 'tailwindcss/utilities';

/* Dodaj niestandardowe style poniżej */
```
# Zasoby

- [Vite Documentation](https://vitejs.dev/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
