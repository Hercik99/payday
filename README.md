# Strona Payday (GitHub Pages)

Strona zawiera stronę główną (`index.html`), pomoc (`support.html`) i politykę prywatności (`privacy.html`) w wersjach PL i EN, z jasnym i ciemnym motywem.

## 1. Wstaw swój e-mail (raz)
W Terminalu, w tym folderze:
```
sed -i '' 's/{{EMAIL}}/twoj@adres.pl/g' *.html
```
Przycisk „Postaw mi kawę” prowadzi już do https://buymeacoffee.com/hercik.

## 2. Publikacja
1. github.com → **New repository** → nazwa np. `finanse` → Public → Create.
2. **Add file → Upload files** → przeciągnij całą zawartość tego folderu (razem z `img/` i `.nojekyll`) → Commit.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. Po 1–2 minutach strona działa pod `https://hercik99.github.io/finanse/`.

## 3. Adresy do App Store Connect
- Privacy Policy URL: `https://hercik99.github.io/finanse/privacy.html`
- Regulamin (EULA, opcjonalnie): `https://hercik99.github.io/finanse/terms.html`
- Support URL: `https://hercik99.github.io/finanse/support.html`
- Marketing URL (opcjonalnie): `https://hercik99.github.io/finanse/`
