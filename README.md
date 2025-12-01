# PrepMaster for WooCommerce

> Automated prep sheet generation for restaurants - Turn your WooCommerce orders into actionable ingredient lists instantly.

[![License](https://img.shields.io/badge/license-GPL--2.0-blue.svg)](LICENSE)
[![WordPress](https://img.shields.io/badge/wordpress-5.0%2B-blue.svg)]()
[![WooCommerce](https://img.shields.io/badge/woocommerce-3.0%2B-purple.svg)]()
[![PHP](https://img.shields.io/badge/php-7.4%2B-blue.svg)]()

---

## 🎯 Problem

Running a restaurant or catering business with WooCommerce? Tired of:
- Manually calculating ingredient quantities from orders
- Spending 45+ minutes every morning with spreadsheets and calculators
- Over-ordering or under-ordering ingredients
- Kitchen staff confused about prep requirements
- Food waste from inaccurate calculations

## ✨ Solution

PrepMaster automatically syncs your WooCommerce orders and calculates exactly what ingredients you need to prep each day. No more manual calculations. No more mistakes.

---

## 🚀 Features

### Core Features
- ✅ **Auto Order Sync** - WooCommerce orders sync automatically
- ✅ **Smart Calculations** - Ingredient quantities calculated instantly
- ✅ **Multi-Restaurant** - Manage multiple locations/brands (based on plan)
- ✅ **Print Prep Sheets** - Clean, kitchen-ready printable format
- ✅ **Product Mapping** - Intelligent auto-mapping of products to recipes
- ✅ **Real-Time Updates** - See new orders as they come in

### Business Plan Features
- 📧 **Email Reports** - Send prep sheets directly to kitchen staff
- 👥 **10 Restaurants** - Perfect for multi-location operations

---

## 📦 Installation

### Method 1: Upload via WordPress

1. Download `prepmaster.zip` from [Releases](https://github.com/odgrande/prepmaster/releases)
2. Go to WordPress Admin → **Plugins** → **Add New** → **Upload Plugin**
3. Choose the downloaded ZIP file
4. Click **Install Now**
5. Click **Activate Plugin**
6. Go to **PrepMaster** → Create account or login

### Method 2: Manual Installation

1. Download and unzip `prepmaster.zip`
2. Upload the `prepmaster` folder to `/wp-content/plugins/`
3. Activate the plugin through WordPress Admin → **Plugins**
4. Go to **PrepMaster** → Create account or login

---

## 🎬 Quick Start

### Step 1: Create Restaurant
Go to **PrepMaster → Restaurants** and add your first restaurant (name, email, phone).

### Step 2: Build Packages
Go to **PrepMaster → Packages** and create menu items with ingredients:
- Example: "Wedding Package" contains: 10x Puff Puff, 15x Samosa

### Step 3: Map Products
Go to **PrepMaster → Product Mapping** and link WooCommerce products to packages:
- Click "Auto-Map All" for smart matching
- Or manually map each product

### Step 4: View Prep Sheet
Go to **PrepMaster → Prep Sheet**:
- Select date
- Click "Refresh" to see all ingredients needed
- Print or email to kitchen staff

---

## 💡 How It Works

```
Customer orders "Wedding Package" (Qty: 50)
         ↓
PrepMaster syncs order automatically
         ↓
Calculates: 500 Puff Puffs + 750 Samosas
         ↓
Displays on Prep Sheet
         ↓
Kitchen preps exact quantities
```

---

## 📋 Requirements

- **WordPress:** 5.0 or higher
- **WooCommerce:** 3.0 or higher
- **PHP:** 7.4 or higher
- **MySQL:** 5.6 or higher

---

## 💰 Pricing

| Plan | Restaurants | Price | Features |
|------|-------------|-------|----------|
| **FREE** | 1 restaurant | $0 | All core features |
| **PRO** | 3 restaurants | $79 one-time | All core features |
| **BUSINESS** | 10 restaurants | $149 one-time | All features + Email reports |

### Get PRO or BUSINESS
👉 [Purchase License Key](https://odgrandeng.gumroad.com/l/xvglwd)

---

## 📸 Screenshots

### Dashboard
![Dashboard](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

### Prep Sheet
![Prep Sheet](https://via.placeholder.com/800x400?text=Prep+Sheet+Screenshot)

### Package Management
![Packages](https://via.placeholder.com/800x400?text=Packages+Screenshot)

---

## 🎯 Use Cases

### Cloud Kitchens
Running multiple brands from one kitchen? Each brand gets its own packages and prep sheets.

### Catering Businesses
Handle large orders with complex recipes. Calculate ingredients for 500 guests in seconds.

### Restaurant Chains
Manage up to 10 locations with separate prep requirements.

### Meal Prep Services
Weekly meal prep made easy with accurate ingredient calculations.

---

## 🔧 Troubleshooting

### Orders not syncing?
1. Check WooCommerce is installed and activated
2. Go to PrepMaster → Product Mapping
3. Ensure products are mapped to packages

### Can't see prep sheet?
1. Make sure you have at least one restaurant created
2. Check that products are mapped to packages
3. Ensure orders exist for selected date

### Need more restaurants?
Upgrade to PRO (3 restaurants) or BUSINESS (10 restaurants) at [Gumroad](https://odgrandeng.gumroad.com/l/xvglwd)

---

## 🛠️ Technical Details

### Architecture
- **Frontend:** WordPress admin interface with AJAX
- **Backend:** Separate Node.js API with PostgreSQL database
- **License Management:** Freemius SDK
- **API Authentication:** JWT tokens

### API Endpoints
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User authentication
- `GET /api/restaurants` - Fetch restaurants
- `GET /api/packages` - Fetch packages
- `POST /api/prep-sheet` - Generate prep sheet

### Security
- All API requests authenticated with JWT
- Nonce verification on AJAX requests
- SQL injection prevention
- XSS protection
- Rate limiting on API

---

## 📝 Changelog

### Version 1.0.0 (December 1, 2024)
- 🎉 Initial release
- ✅ WooCommerce order sync
- ✅ Multi-restaurant support
- ✅ Package management
- ✅ Product mapping with auto-suggestions
- ✅ Prep sheet generation
- ✅ Print functionality
- ✅ Email reports (Business plan)
- ✅ Freemius integration for licensing

---

## 🤝 Support

### Need Help?
- 📧 Email: [odgrandeng@gmail.com](mailto:odgrandeng@gmail.com)
- ⏱️ Response time: Within 24 hours (weekdays)
- 🐛 Report bugs: [GitHub Issues](https://github.com/odgrande/prepmaster/issues)

### Before Contacting Support
1. Check the [Troubleshooting](#-troubleshooting) section
2. Ensure you're running the latest version
3. Verify system requirements are met

---

## 🎓 Documentation

### Video Tutorials (Coming Soon)
- [ ] Installation walkthrough
- [ ] Creating packages and ingredients
- [ ] Product mapping guide
- [ ] Generating prep sheets

### Written Guides
- [Installation Guide](#-installation)
- [Quick Start Guide](#-quick-start)
- [FAQ](https://github.com/odgrande/prepmaster/wiki/FAQ)

---

## 🚦 Roadmap

### Version 1.1 (Q1 2025)
- [ ] Ingredient inventory tracking
- [ ] Low stock alerts
- [ ] Cost calculations per dish
- [ ] Export prep sheets to CSV

### Version 1.2 (Q2 2025)
- [ ] Mobile app for kitchen staff
- [ ] Real-time prep status updates
- [ ] Recipe scaling calculator
- [ ] Nutrition information

### Version 2.0 (Q3 2025)
- [ ] Supplier integration
- [ ] Automatic purchase orders
- [ ] Multi-language support
- [ ] Advanced analytics

---

## 👨‍💻 Developer

**Bolarinwa Odunayo**
- GitHub: [@odgrande](https://github.com/odgrande)
- Email: odgrandeng@gmail.com

Built with ❤️ for restaurant owners who deserve better tools.

---

## 📄 License

This project is licensed under the GPL-2.0 License - see the [LICENSE](LICENSE) file for details.

This is free software: you are free to change and redistribute it. There is NO WARRANTY, to the extent permitted by law.

---

## 🌟 Show Your Support

If PrepMaster helps your business, please:
- ⭐ Star this repository
- 🐦 Share on Twitter
- 📝 Write a review
- 🎁 Recommend to other restaurant owners

---

## 🔗 Links

- **GitHub Repository:** https://github.com/odgrande/prepmaster
- **Download Free Version:** [Releases](https://github.com/odgrande/prepmaster/releases)
- **Buy PRO License:** https://odgrandeng.gumroad.com/l/xvglwd
- **Documentation:** [Wiki](https://github.com/odgrande/prepmaster/wiki)
- **Report Issues:** [Issues](https://github.com/odgrande/prepmaster/issues)

---

## 💬 Testimonials

> "PrepMaster saved us 10+ hours every week. The ROI was instant." - *Cloud Kitchen Owner*

> "Finally, a plugin that actually solves a real restaurant problem!" - *Catering Business*

> "The auto-mapping feature is genius. Setup took 15 minutes." - *Restaurant Manager*

---

## 🙏 Acknowledgments

- WordPress and WooCommerce communities
- Freemius for licensing infrastructure
- All beta testers and early adopters

---

**Made with ❤️ for restaurants that use WooCommerce**

Stop calculating. Start cooking. 👨‍🍳
