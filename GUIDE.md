# 🚀 Så här publicerar du Seated på GitHub Pages

Följ dessa steg — tar ungefär 5 minuter.

---

## Steg 1 — Skapa ett GitHub-konto
Om du inte redan har ett:
👉 Gå till https://github.com och klicka **Sign up**

---

## Steg 2 — Skapa ett nytt repository
1. Logga in på GitHub
2. Klicka på **+** uppe till höger → **New repository**
3. Namnge det: `seated` (eller vad du vill)
4. Välj **Public**
5. Klicka **Create repository**

---

## Steg 3 — Ladda upp filerna
Du har fyra filer att ladda upp:
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.png`
- `icon-512.png`

På repository-sidan:
1. Klicka **uploading an existing file** (eller **Add file → Upload files**)
2. Dra alla fem filer till rutan
3. Klicka **Commit changes**

---

## Steg 4 — Aktivera GitHub Pages
1. Gå till **Settings** (kugghjulet uppe till höger på repository-sidan)
2. Scrolla ner till **Pages** i vänstermenyn
3. Under **Source** → välj **Deploy from a branch**
4. Branch: välj **main**, mapp: **/ (root)**
5. Klicka **Save**

---

## Steg 5 — Vänta 1–2 minuter
GitHub bygger sidan. Du ser en grön banner med din URL när det är klart:

```
https://DITT-ANVÄNDARNAMN.github.io/seated/
```

---

## Steg 6 — Lägg till på hemskärmen (Android)
1. Öppna URL:en i **Chrome** på din Android-telefon
2. En banner dyker upp längst ner: **"Lägg till på hemskärmen"** — tryck på den
3. Alternativt: tryck på ⋮ (tre punkter) → **Lägg till på hemskärmen**
4. Tryck **Installera**

Nu finns Seated som en ikon på hemskärmen — precis som en riktig app! 🎉

---

## Viktigt — Uppdatera Google API-nyckeln
Nu när appen ligger på en publik URL, gå till:
👉 https://console.cloud.google.com/apis/credentials

Klicka på din API-nyckel → **Application restrictions**:
- Välj **HTTP referrers**
- Lägg till: `https://DITT-ANVÄNDARNAMN.github.io/*`

Det skyddar nyckeln så den bara fungerar från din app.
