# 🚚 MilesConnect

**Real-time fleet tracking & management system**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=for-the-badge&logo=mapbox&logoColor=white)

---

## ✨ Features

🗺️ **Live Fleet Map** — Track all vehicles in real-time on interactive maps

🚗 **Vehicle Management** — Monitor status, location & availability

👨‍✈️ **Driver Portal** — Dedicated mobile-friendly driver dashboard

📦 **Shipment Tracking** — Create, assign & track deliveries

🔔 **Smart Alerts** — Real-time notifications for drivers

🔗 **Public Tracking** — Shareable tracking links for customers

📞 **AI Voice Assistant** — Customer support with Retell AI

---

## 🚀 Quick Start

```bash
# Clone & Install
git clone https://github.com/itanishqshelar/milesconnect-demo.git
cd milesconnect-demo && npm install

# Configure environment
cp .env.example .env.local
# Add your Supabase & Mapbox keys

# Run
npm run dev
```

Open [localhost:3000](http://localhost:3000)

---

## 🔧 Environment Variables

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key
NEXT_PUBLIC_MAPBOX_TOKEN=your_mapbox_token
RETELL_API_KEY=your_retell_key
```

---

## 📱 Portals

| Portal          | Route        | Description                   |
| --------------- | ------------ | ----------------------------- |
| Admin Dashboard | `/dashboard` | Fleet overview & management   |
| Driver App      | `/driver`    | Shipment updates & navigation |
| Customer Portal | `/customer`  | Track shipments & support     |
| Public Tracking | `/track`     | Shareable tracking page       |

---

## 🌐 Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/itanishqshelar/milesconnect-demo)

---

## 📄 License

MIT © [Tanishq Shelar](https://github.com/itanishqshelar)
