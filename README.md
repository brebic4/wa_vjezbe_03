# Pizza Vue aplikacija 🍕

## 📦 Preduvjeti

Prije pokretanja projekta potrebno je imati instalirano:

- **Node.js** (preporučena verzija: LTS)
- **npm** (dolazi uz Node.js)
- Git

Provjera instalacije:

```bash
node -v
npm -v
```

---

## 🚀 Pokretanje backend poslužitelja (Express)

1. Klonirajte repozitorij:

```bash
git clone <https://github.com/brebic4/wa_vjezbe_03.git>
```

2. Uđite u backend direktorij (pizza-express):

```bash
cd pizza-express
```

3. Instalirajte potrebni paket:

```bash
npm install
```

4. Pokrenite Express poslužitelj:

```bash
node index.js
```

Ostavite Express poslužitelj pokrenut, te otvorite novi terminal

---

## 🖥️ Pokretanje frontend aplikacije (Vue 3)

1. U drugom terminalu uđite u frontend direktorij (npr. `pizza-vue`):

```bash
cd pizza-vue
```

2. Instalirajte potrebni paket:

```bash
npm install
```

3. Pokrenite frontend aplikaciju:

```bash
npm run dev
```

4. Aplikacija će biti dostupna na adresi (ovisno o Vite konfiguraciji):

```
http://localhost:5173
```

---

## 🔗 Povezivanje frontenda i backenda

Frontend aplikacija koristi **Axios** za komunikaciju s backendom te šalje HTTP zahtjeve prema:

```
http://localhost:3000
```

Prije pokretanja frontenda OBAVEZNO pokrenuti backend poslužitelj.

---

## 🛠️ Tehnologije

- **Frontend:** Vue 3, Vite, Tailwind CSS
- **Backend:** Node.js, Express
- **HTTP komunikacija:** Axios

---

## ✅ Napomena

Ako aplikacija ne dohvaća podatke:

- provjerite je li backend pokrenut
- provjerite portove (`3000` za backend, `5173` za frontend)
- provjerite CORS postavke na backendu

---
