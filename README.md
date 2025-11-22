# 🚚 SmartLoad 3D

SmartLoad 3D is a lightweight **React + Vite + TypeScript** application for visualizing and managing **3D truck loading capacity**.  
It offers an interactive 3D truck model, box configuration, loading logic.

---

## ✨ Features

- 📦 **3D Truck Visualization**  
- 🚛 **Truck Capacity Configuration**  
- 🧱 **Box Management Dashboard**  
- 🔔 **Toast Notifications**  
- 📄 **Delivery Report Generation**  
- ☁️ **Optional Supabase Backend Integration**  
- ⚡ **Vite Fast Refresh + TypeScript**  
- 🎨 **Tailwind CSS for UI**

---

## 🖼️ Screenshots

(Add your images inside: `public/screenshots/`)

### 🧱 Dashboard View
![Dashboard](public/screenshots/dashboard.png)

### 🚚 3D Truck Visualization
![Truck 3D](public/screenshots/truck-3d.png)

### 📦 Add Box Page
![Add Box](public/screenshots/add-box.png)

---

## 🛠 Tech Stack

| Category | Technology |
|---------|------------|
| Framework | React + TypeScript |
| Bundler | Vite |
| Styling | Tailwind CSS |
| Linting | ESLint |
| Backend | Supabase (optional) |
| Extras | Custom Hooks + Utilities |

---

## 📁 Folder Structure

```
SmartLoad-3D/
├─ index.html
├─ package.json
├─ vite.config.ts
├─ tsconfig.json
├─ .env
│
├─ public/
│  ├─ placeholder.svg
│  ├─ robots.txt
│  └─ screenshots/
│
├─ src/
│  ├─ main.tsx
│  ├─ App.tsx
│  ├─ App.css
│  ├─ index.css
│  │
│  ├─ components/
│  │  ├─ Navigation.tsx
│  │  ├─ TruckVisualization.tsx
│  │  ├─ TruckCapacityConfig.tsx
│  │  └─ ui/
│  │
│  ├─ pages/
│  │  └─ AddBox.tsx
│  │
│  ├─ data/
│  │  └─ dummyData.ts
│  │
│  ├─ hooks/
│  │  ├─ use-mobile.tsx
│  │  └─ use-toast.tsx
│  │
│  ├─ lib/
│  │  ├─ supabase.ts
│  │  └─ utils.ts
│  │
│  └─ vite-env.d.ts
│
├─ postcss.config.js
├─ tailwind.config.ts
└─ eslint.config.js
```

---

## ▶️ Running Locally

### 1. Install dependencies
```sh
npm install
```

### 2. Start development server
```sh
npm run dev
```

### 3. Open in browser
```
http://localhost:5173
```

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to open issues or submit pull requests.

---

## 📜 License

MIT License © 2025 SmartLoad 3D
