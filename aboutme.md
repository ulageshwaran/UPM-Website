# UPM Technologies Website

A professional corporate website built with Django, showcasing our digital agency's portfolio and services in web design, development, and hosting.

## 🚀 About

UPM Technologies is a digital agency specializing in creating modern web solutions. This repository contains our corporate website that serves as both our portfolio and a lead generation platform.

## ✨ Features

- **Responsive Design**: Fully responsive layout built with Bootstrap 5
- **Portfolio Gallery**: Interactive project showcase with filtering and lightbox
- **Contact System**: Functional contact form with email notifications
- **Newsletter Integration**: Email subscription system
- **Service Pages**: Dedicated pages for Web Development and Poster Design tariffs
- **Team Profiles**: Meet our talented development team

## 🛠️ Technology Stack

- **Backend**: Django 5.0.7 (Python 3.x)
- **Database**: SQLite
- **Frontend**: HTML5, CSS3, Bootstrap 5, JavaScript (jQuery)
- **Storage**: AWS S3 (Production) / Local (Development)
- **Email**: SMTP integration for contact forms
- **Additional Libraries**: Isotope.js, Lightbox, WOW.js

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/upm-technologies.git
cd upm-technologies
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory with the following variables:
```env
SECRET_KEY=your_secret_key
DEBUG=True
AWS_ACCESS_KEY_ID=your_aws_key
AWS_SECRET_ACCESS_KEY=your_aws_secret
EMAIL_HOST_USER=your_email
EMAIL_HOST_PASSWORD=your_password
```

5. Run migrations:
```bash
python manage.py migrate
```

6. Start the development server:
```bash
python manage.py runserver
```

## 📂 Project Structure

```
upm-technologies/
├── core/                 # Project configuration
│   ├── settings.py
│   └── urls.py
├── upm/                  # Main application
│   ├── models.py        # Database models
│   ├── views.py         # Request handlers
│   ├── forms.py         # Form definitions
│   └── urls.py          # URL routing
├── templates/           # HTML templates
├── static/              # CSS, JS, Images
├── manage.py
├── requirements.txt
└── .env                 # Environment variables (not in repo)
```

## 🎯 Key Pages

- **Home**: Landing page with hero section and service overview
- **About**: Company information and mission
- **Services**: Web design, hosting, and graphic design services
- **Projects**: Portfolio gallery with completed work
- **Team**: Developer profiles
- **Contact**: Contact form with map integration
- **Tariff Pages**: Pricing for web development and poster design

## 🔐 Security

- Sensitive credentials managed via environment variables
- CSRF protection enabled
- Secure email handling with SMTP

## 🚀 Recent Improvements

- ✅ Migrated sensitive data to `.env` file
- ✅ Conditional AWS S3 storage (development vs production)
- ✅ Fixed frontend loader/spinner behavior
- ✅ Code refactoring following PEP 8 conventions

## 👥 Team

- **Mohanraj M** - Backend Developer
- **Prasanth A S** - Frontend Developer
- **Ulageshwaran E** - Full Stack Developer

## 📝 License

This project is proprietary software owned by UPM Technologies.

## 📧 Contact

For inquiries, please visit our [contact page](https://upmtechnologies.com/contact) or email us at upmtechnologies@gmail.com

---

**Built with ❤️ by UPM Technologies**
