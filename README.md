# Sharifjon - Smartphone Store for Uzbekistan

A modern, clean, and professional e-commerce website for a smartphone store targeting customers in Uzbekistan with full Uzbek language support.

## 🚀 Features

- **Modern Design** - Beautiful and responsive UI with dark mode support
- **Product Catalog** - Browse and filter smartphones by category and price
- **Shopping Cart** - Add products to cart and manage quantities
- **User Profile** - SMS-based authentication with phone verification
- **Admin Panel** - Manage products, view orders, and track statistics
- **Mobile Responsive** - Fully optimized for all devices
- **Dark Mode** - Toggle between light and dark themes
- **Notifications** - Real-time notifications for user actions
- **Uzbek Language** - Complete Uzbek language support

## 🛠️ Tech Stack

- **Frontend**: React 18.2.0
- **Framework**: Next.js 14.0.0 / Vite
- **State Management**: Zustand
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Routing**: React Router v6

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/jsc0ding/sharifjon.git
cd sharifjon
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

## 📱 Pages

- **Home** - Landing page with carousel and featured products
- **Products** - Product listing with filters and sorting
- **Catalog** - Advanced catalog with grid/list view options
- **Product Detail** - Detailed product information with specifications
- **Cart** - Shopping cart management
- **Checkout** - Order checkout process
- **Profile** - User profile with SMS verification
- **Admin** - Admin dashboard for managing products and orders
- **Deals** - Special offers and promotions

## 🔐 Admin Panel

Access the admin panel at `/admin`
- **Demo Password**: `admin123`
- Add, edit, and delete products
- View and manage orders
- Track sales statistics

## 👤 User Profile

Create a profile at `/profile`
- Phone number verification via SMS
- View order history
- Manage saved addresses
- Track spending

## 🎨 Customization

### Colors
Edit `src/index.css` to customize the color scheme:
- Primary color: `#0066FF`
- Accent color: `#FF6B6B`

### Language
All text is in Uzbek. To add more languages, edit `src/i18n/uz.json`

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**Sharifjon E-Commerce Team**

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For support, email info@sharifjon.uz or open an issue on GitHub.

---

**Sharifjon** - Modern E-commerce for Uzbekistan 🇺🇿

## Features

### 🎨 Design
- **Light & Dark Mode**: Full theme support with smooth transitions
- **Responsive Layout**: Mobile, tablet, and desktop optimized
- **Modern Tech Style**: Minimalist design with Tailwind CSS
- **Professional UI**: Clean cards, soft shadows, and proper spacing

### 🛍️ Shopping Features
- **Hero Section**: Featured smartphones and promotions
- **Product Cards**: Image, name, price in UZS, discount badge, buy button
- **Category Filters**: iPhone, Samsung, Xiaomi, Huawei, Google, OnePlus
- **Search Bar**: Live product search
- **Product Detail Page**: Gallery, specs, reviews, ratings
- **Shopping Cart**: Add/remove items, quantity management
- **Checkout**: Multi-step checkout with shipping and payment info
- **Order Confirmation**: Order tracking and confirmation

### 👨‍💼 Admin Dashboard
- **Dashboard Overview**: Sales stats, revenue, orders, users
- **Product Management**: Add, edit, delete products
- **Order Management**: View and manage orders with status tracking
- **User Management**: Manage customer accounts
- **Analytics**: Sales charts and performance metrics

### 🌐 Localization
- **Uzbek Language**: Full UI in Uzbek (uz)
- **Currency**: All prices in UZS (Uzbek Som)
- **Local Formatting**: Proper number and date formatting

## Tech Stack

- **Frontend**: React 18
- **Routing**: React Router v6
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Language**: JavaScript (ES6+)

## Project Structure

```
├── src/
│   ├── components/
│   │   ├── Header.jsx          # Navigation header with search
│   │   ├── ProductCard.jsx     # Reusable product card
│   │   └── Footer.jsx          # Footer with links
│   ├── pages/
│   │   ├── Home.jsx            # Home page with hero & featured
│   │   ├── Products.jsx        # Product listing with filters
│   │   ├── ProductDetail.jsx   # Product detail page
│   │   ├── Cart.jsx            # Shopping cart
│   │   ├── Checkout.jsx        # Multi-step checkout
│   │   └── AdminDashboard.jsx  # Admin panel
│   ├── store/
│   │   └── store.js            # Zustand stores (theme, cart, auth)
│   ├── data/
│   │   └── products.js         # Sample product data
│   ├── i18n/
│   │   └── uz.json             # Uzbek translations
│   ├── App.jsx                 # Main app component
│   ├── main.jsx                # Entry point
│   └── index.css               # Global styles
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
└── README.md
```

## Getting Started

### Prerequisites
- Node.js 16+ and npm

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Open browser to `http://localhost:3000`

### Build for Production

```bash
npm run build
npm run preview
```

## Key Pages

### Home Page
- Hero section with featured products
- Feature highlights (fast shipping, free delivery, secure shopping)
- Featured products grid
- Promotional banner
- New arrivals section

### Products Page
- Product grid with filtering
- Category filters (iPhone, Samsung, Xiaomi, etc.)
- Price range slider
- Specs filters (RAM, Storage, Battery, Camera)
- Sort options (newest, price, rating)
- Responsive grid layout

### Product Detail Page
- Product image gallery
- Detailed specifications
- Customer reviews and ratings
- Quantity selector
- Add to cart button
- Related products
- Wishlist and share options

### Cart Page
- Cart items with images
- Quantity adjustment
- Remove items
- Order summary with subtotal, shipping, tax
- Proceed to checkout button

### Checkout Page
- Multi-step checkout (Shipping → Payment → Review)
- Shipping information form
- Payment details form
- Order review
- Order confirmation with order number

### Admin Dashboard
- Dashboard overview with stats
- Product management (CRUD operations)
- Order management with status tracking
- User management
- Sales analytics and charts

## Customization

### Colors
Edit `tailwind.config.js` to customize the color palette:
```js
colors: {
  primary: '#0066FF',      // Main blue
  secondary: '#6B7280',    // Gray
  accent: '#FF6B35',       // Orange
  success: '#10B981',      // Green
  warning: '#F59E0B',      // Yellow
  error: '#EF4444',        // Red
}
```

### Products
Edit `src/data/products.js` to add/modify products with:
- Name, brand, price, images
- Specifications (RAM, storage, battery, camera, display)
- Categories and ratings
- Stock status

### Translations
Edit `src/i18n/uz.json` to modify Uzbek translations or add new languages.

## Features Highlights

✅ **Fully Responsive** - Works on all devices
✅ **Dark Mode** - Complete dark theme support
✅ **Uzbek Language** - Full UI in Uzbek
✅ **Modern Design** - Clean, professional interface
✅ **State Management** - Zustand for cart and theme
✅ **Product Filtering** - Multiple filter options
✅ **Admin Panel** - Complete management interface
✅ **Checkout Flow** - Multi-step secure checkout
✅ **Performance** - Optimized with Vite
✅ **Accessibility** - Semantic HTML and ARIA labels

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - feel free to use this project for commercial purposes.

## Support

For issues or questions, please create an issue in the repository.

---

**Sharifjon** - Modern E-commerce for Uzbekistan 🇺🇿
#   s h a r i f j o n  
 "# sharifjon" 
