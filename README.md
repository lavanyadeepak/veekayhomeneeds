# VEE KAY HOME NEEDS Website

## Overview
This repository contains a simple static webpage created for **VEE KAY HOME NEEDS**, a supplier of homemade traditional South Indian food products.  
The page highlights product offerings such as **Appalam, Vadagam, Pickles, Powders, Vathal, Thokku**, and more, along with important announcements and contact information.

## How to Use This Template for Your Business

1. **Fork this repository**
2. **Edit `index.html`:**
   - Replace business name and contact details
   - Update WhatsApp number in the order form
   - Modify the announcement section
3. **Update products:**
   - Edit the product data in [specify where - JSON file? inline HTML?]
4. **Customize colors/branding:**
   - Modify CSS variables in `styles.css`
5. **Deploy to GitHub Pages:**
   - Go to Settings → Pages → Select main branch
   - Your site will be live at `https://yourusername.github.io/yourrepo`
---

## Technologies Used
- Pure HTML, CSS, JavaScript (no framework dependencies)
- WhatsApp Business API integration
- Geolocation API for delivery address capture
- Responsive design for mobile-first experience
- 
## Features
- 📜 **Welcome Message** – Introduction and gratitude note to customers.  
- 📢 **Announcements** – Price revision notice (effective 5th March 2025) and order deadline (25th February 2025).  
- 🛍️ **Product Catalog** – Organized listing of items with:
  - Item name (Tamil + English)
  - Weight
  - Price
- 🚚 **Shipping Note** – Clear mention that shipping charges are extra.  
- 📞 **Contact Information** – Phone number for placing orders.  
- © **Footer** – Copyright notice.

- ## WhatsApp Order Integration
Orders are automatically formatted and sent via WhatsApp with:
- Customer details (name, mobile, address)
- GPS location (if permitted)
- Itemized order with quantities and prices
- Total estimated cost

**To customize:** Update the WhatsApp number in line [X] of `script.js`

---

## Project Structure
