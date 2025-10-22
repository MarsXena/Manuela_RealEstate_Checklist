# 🏡 Buyer & Seller Checklist – Manuela Acevedo

A simple, mobile-friendly web app designed for real estate clients to stay organized through the home buying and selling process.

Created for **Manuela Acevedo, Licensed Real Estate Salesperson** at **Exit Realty Connections**.

---

## 🌟 Features

### 1. Buyer & Seller Checklist
- Interactive checklists to help clients stay on track  
- Progress is saved locally (no accounts or tracking)  
- Clean, modern white-and-gold design  

### 2. Open House RSVP
- Embed a **Google Form** for guests to RSVP  
- Generate **Google Calendar** links  
- Create downloadable **.ics files** for Outlook and Apple Calendar users  

---

## 🧭 How to Use

### Hosting (GitHub Pages)
This site runs entirely on static HTML, CSS, and JavaScript — no backend required.

1. Upload `index.html` and `open-house.html` to your GitHub repository.  
2. Enable **GitHub Pages** (Settings → Pages → Deploy from branch → `main`).  
3. Access your live site at `https://<your-username>.github.io/manuela-checklist/`.

### Open House Forms (one per event)
Each new Open House can have its own form and event page:

1. Create a new **Google Form** for the specific Open House.  
2. In Google Forms, click **Send → <> Embed**, then copy the iframe HTML.  
3. Paste it into `open-house.html` where marked, or save as a new file (e.g., `open-house-123main.html`).  
4. Use the page’s **Google Calendar** and **.ics** buttons to generate event links/files for that specific open house.

---

## 📞 Contact

**Manuela Acevedo**  
Licensed Real Estate Salesperson  
Exit Realty Connections  
📧 [Manuela@ExitRealtyConnections.com](mailto:Manuela@ExitRealtyConnections.com)  
📞 [917-682-7543](tel:+19176827543)

---

## ⚙️ Tech Info
- HTML5 + CSS3 + JavaScript (no frameworks)  
- Uses `localStorage` for checklist persistence  
- Built by Jerushah Gracey (Integrated Eight | B2B Creative Marketing) with ChatGPT (Randolph)  
- Licensed under [MIT License](LICENSE)
