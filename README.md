# 🎓 EduPulse — International School ERP System

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-gold)
![License](https://img.shields.io/badge/license-MIT-navy)
![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Tailwind](https://img.shields.io/badge/Tailwind-3.4-38bdf8)

**نظام إدارة مدرسة دولية متكامل | International School Management System**

[Live Demo](#) • [Documentation](#) • [Features](#features) • [Installation](#installation)

</div>

---

## 📋 Overview | نظرة عامة

**EduPulse** is a comprehensive, enterprise-grade School ERP (Enterprise Resource Planning) system designed for international schools. Built with modern web technologies, it provides a complete solution for managing students, teachers, parents, attendance, exams, finance, transportation, and more.

**إيديو بالس** هو نظام متكامل لإدارة المدارس الدولية مبني بأحدث التقنيات. يوفر حلاً شاملاً لإدارة الطلاب، المعلمين، أولياء الأمور، الحضور، الامتحانات، الحسابات، المواصلات، وغيرها.

---

## ✨ Features | الميزات

### 🎯 Core Modules | الوحدات الأساسية

| Module | Description |
|--------|-------------|
| 📊 **Dashboard** | Real-time KPIs, charts, quick actions |
| 📈 **Analytics** | Advanced insights with radar charts, trends |
| 👨‍🎓 **Students** | Complete student management with search & filters |
| 👨‍🏫 **Teachers** | Teacher profiles, subjects, qualifications |
| 👨‍👩‍👧‍👦 **Parents** | Parent portal with children tracking |
| ✅ **Attendance** | 4 methods: QR, Face ID, Fingerprint, Manual |
| 📝 **Exams** | Exam scheduling, results, grade distribution |
| 📚 **Homework** | Assignment tracking with submission rates |
| 💰 **Finance** | Revenue, expenses, fee collection, invoices |
| 🚌 **Transportation** | Live GPS tracking, routes, drivers |
| 👔 **HR** | Employee management, payroll, contracts |
| 💬 **Messages** | Real-time messaging system |
| ⚙️ **Settings** | Language, theme, roles, permissions |

### 🎨 Design & UX | التصميم وتجربة المستخدم

- ✅ **Glassmorphism UI** — Modern frosted glass effects
- ✅ **Dark/Light Mode** — Full theme support
- ✅ **RTL/LTR Support** — Arabic & English with automatic layout flip
- ✅ **Responsive Design** — Mobile, tablet, desktop optimized
- ✅ **Navy Blue + Gold Theme** — Professional color palette
- ✅ **Cairo & Poppins Fonts** — Beautiful typography
- ✅ **Smooth Animations** — Micro-interactions throughout
- ✅ **Toast Notifications** — Success, error, warning, info alerts

### 🔐 Authentication & Security | الأمان

- ✅ Multi-portal login (Admin, Teacher, Student, Parent)
- ✅ Role-Based Access Control (RBAC)
- ✅ Session management with localStorage
- ✅ Secure password handling

### 📊 Data Visualization | عرض البيانات

- ✅ **Recharts** integration for beautiful charts
- ✅ Area charts, bar charts, line charts, pie charts
- ✅ Radar charts for performance analysis
- ✅ Real-time data updates
- ✅ Interactive tooltips and legends

---

## 🚀 Tech Stack | التقنيات المستخدمة

### Frontend
- **React 18** — UI library
- **TypeScript** — Type safety
- **Vite** — Build tool
- **Tailwind CSS** — Utility-first CSS
- **Lucide React** — Icon library
- **Recharts** — Chart library

### State Management
- **React Context API** — Global state
- **LocalStorage** — Persistent data

### Build & Deploy
- **Vite** — Fast builds
- **Single HTML output** — Easy deployment

---

## 📦 Installation | التثبيت

### Prerequisites
```bash
Node.js >= 18.x
npm >= 9.x
```

### Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/edupulse.git
cd edupulse

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

The app will be available at `http://localhost:5173`

---

## 🔑 Demo Credentials | بيانات الدخول التجريبية

| Portal | Email | Password |
|--------|-------|----------|
| **Admin** | admin@edupulse.com | admin123 |
| **Teacher** | teacher@edupulse.com | teacher123 |
| **Student** | student@edupulse.com | student123 |
| **Parent** | parent@edupulse.com | parent123 |

> 💡 **Tip:** Click any portal button on the login page to auto-fill credentials

---

## 📁 Project Structure | هيكل المشروع

```
edupulse/
├── src/
│   ├── components/
│   │   ├── Layout.tsx          # Main layout with sidebar
│   │   └── Toast.tsx           # Toast notification system
│   ├── context/
│   │   └── AppContext.tsx      # Global state (lang, theme)
│   ├── lib/
│   │   ├── translations.ts    # i18n (Arabic & English)
│   │   └── mockData.ts        # Sample data
│   ├── pages/
│   │   ├── LoginPage.tsx      # Authentication
│   │   ├── Dashboard.tsx      # Main dashboard
│   │   ├── AnalyticsPage.tsx  # Advanced analytics
│   │   └── Modules.tsx        # All other modules
│   ├── App.tsx                # Root component
│   ├── main.tsx               # Entry point
│   └── index.css              # Global styles
├── index.html
├── package.json
├── vite.config.ts
└── README.md
```

---

## 🎨 Customization | التخصيص

### Colors
The theme uses custom color palettes defined in `src/index.css`:
- **Navy Blue**: `navy-50` to `navy-950`
- **Gold**: `gold-50` to `gold-900`

### Fonts
- **Arabic**: Cairo (Google Fonts)
- **English**: Poppins (Google Fonts)

### Adding New Languages
Edit `src/lib/translations.ts` and add your language object.

---

## 🔄 Next Steps | الخطوات القادمة

### Backend Integration
- [ ] Node.js + Express API
- [ ] PostgreSQL database
- [ ] JWT authentication
- [ ] File upload system
- [ ] Email/SMS notifications

### Additional Features
- [ ] Payment gateway integration
- [ ] PDF report generation
- [ ] Mobile app (React Native)
- [ ] WhatsApp Business API
- [ ] Biometric attendance devices
- [ ] Parent mobile app
- [ ] Student mobile app
- [ ] Teacher mobile app

### DevOps
- [ ] Docker containerization
- [ ] CI/CD pipeline
- [ ] Cloud deployment (AWS/Azure/GCP)
- [ ] Database backups
- [ ] Monitoring & logging

---

## 🤝 Contributing | المساهمة

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License | الترخيص

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author | المؤلف

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com

---

## 🙏 Acknowledgments | شكر وتقدير

- [React](https://react.dev/) — UI framework
- [Tailwind CSS](https://tailwindcss.com/) — Styling
- [Lucide Icons](https://lucide.dev/) — Beautiful icons
- [Recharts](https://recharts.org/) — Chart library
- [Google Fonts](https://fonts.google.com/) — Cairo & Poppins

---

## 📞 Support | الدعم

For support, email support@edupulse.com or join our Slack channel.

---

<div align="center">

**Made with ❤️ for International Schools**

⭐ Star us on GitHub — it helps!

</div>
