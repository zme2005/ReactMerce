# ReactMerce — Modern E-Commerce Frontend

A fully-featured single-page e-commerce application built with **React**, designed with a clean UI, smooth animations, and a scalable architecture.  
This project demonstrates modern React development practices — routing, state management, form handling, API integration, and a dynamic user experience powered by Tailwind CSS and multiple third-party libraries.

---

## 🚀 Features

### 🛍️ Core E-Commerce Features
- Add/remove products from **Wishlist**
- Add/remove items from **Cart**
- Dynamic product listing with category filtering
- Persistent data (LocalStorage + JSON Server API)
- Real-time updates without page reload (SPA)

### 🔐 Authentication
- User registration & login system
- User data stored in JSON Server (mock database)
- Protected routes for authenticated pages

### 🎨 UI / UX Enhancements
- **Dark Mode / Light Mode** toggle
- Fully responsive design (mobile-first)
- Smooth **Lottie animations**
- Image/product sliders using **Swiper**
- Lazy Loading for performance optimization

### 🧰 Technical Stack
- **React + React Generate CLI**
- **Axios** for API calls  
- **Zod** for schema validation  
- **React Hook Form** + RHF Resolver  
- **Tailwind CSS**  
- **Swiper.js**  
- **JSON Server** (Mock REST API)  
- **Local Storage** for cart/wishlist persistence  

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/ReactMerce.git
cd ReactMerce
2️⃣ Install dependencies
bash
Copy code
npm install
3️⃣ Start JSON Server (API)
bash
Copy code
npx json-server --watch db.json --port 4000
4️⃣ Run the development server
bash
Copy code
npm run dev
🗂️ Project Structure
css
Copy code
src/
 ├── components/
 ├── context/
 ├── pages/
 ├── hooks/
 ├── validations/
 ├── assets/
 └── App.jsx
🔧 Scripts
Script	Description
npm run dev	Starts Vite dev server
npm run build	Builds project for production
npm run preview	Previews build output
json-server	Runs API server

📘 APIs
All data is provided by JSON Server:

bash
Copy code
http://localhost:4000/products
http://localhost:4000/users
http://localhost:4000/cart
http://localhost:4000/whishlist
You can modify db.json to extend or adjust the API endpoints.

🛡️ Validation (Zod + React Hook Form)
Strong form validation for login/register

Instant error messages and schema-based validation

🌓 Theme Support
Supports Dark Mode and Light Mode with automatic UI state persistence.

📷 Screenshots (Optional)
If you want, send me screenshots and I’ll embed them here.

🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to update.

📄 License
This project is open-source under the MIT License.

⭐ Show Your Support
If you like this project, give it a star ⭐ on GitHub!

yaml
Copy code

---

If you want:
✅ deployment instructions  
✅ badges (React / Vite / Tailwind / JSON Server)  
✅ a banner image  
✅ more advanced documentation (API tables, contribution guide)  

Just tell me!






