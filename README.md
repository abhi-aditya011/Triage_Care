# Triage Care - AI-Powered Medical Insurance Advisor

A comprehensive, modern web application for health insurance planning and medical wellness support. Triage Care uses AI and machine learning to provide personalized health insurance recommendations while offering a complete suite of healthcare tools and resources.

## 🌟 Key Features

### 🏥 Health Assessment Tools
- **BMI Calculator**: Instant body mass index calculation with health recommendations
- **Health Assessment**: Complete health profile evaluation with personalized advice
- **Symptom Checker**: AI-powered symptom analysis and guidance
- **Medication Tracker**: Manage and track your medications effectively

### 💰 Insurance Planning
- **Insurance Predictor**: ML-powered prediction of healthcare costs using Linear Regression
- **Personalized Recommendations**: Tailored insurance plans based on your health profile
- **Cost Analysis**: Detailed breakdown of expected medical expenses

### 🚑 Emergency Resources
- **Quick Access Emergency Numbers**: Indian emergency services (102, 100, 101, 1091, 1098)
- **Hospital Finder**: Instant Google Maps integration to find nearest hospitals
- **First Aid Guide**: Comprehensive CPR, choking, burns, stroke, and heart attack procedures
- **Mental Health Helplines**: 24/7 support with Tele MANAS and other services

### 🩸 Blood Bank & Donor Finder
- **Blood Bank Network**: Direct access to Indian Blood Bank database
- **Blood Group Compatibility**: Complete compatibility chart for all blood types
- **Donor Registration**: Information on becoming a blood donor
- **Emergency Blood Requests**: Quick access to blood donation resources

### 🧠 Mental Health Support ("Your Mind Matters")
- **Mood Tracker**: Interactive mood assessment with encouraging responses
- **Breathing Exercise**: Animated breathing circle for stress relief
- **Support Helplines**: 24/7 mental health helplines (Tele MANAS, AASRA, iCall)
- **Daily Affirmations**: Positive mental health messages
- **Soft UI Design**: Calming colors and smooth animations

### 📅 Appointment Booking
- **Schedule Consultations**: Book appointments with healthcare professionals
- **Multiple Departments**: General practice, cardiology, neurology, psychiatry, and more
- **Easy Management**: Track your upcoming appointments

## 🛠️ Technology Stack

- **Backend**: Flask 3.0 (Python)
- **Frontend**: HTML5, CSS3, Bootstrap 5.3, JavaScript
- **Machine Learning**: Scikit-learn 1.3.2 (Linear Regression)
- **Data Processing**: Pandas, NumPy
- **Icons**: Font Awesome 6.4.0
- **Typography**: Poppins, Inter, Nunito (for mental health section)

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/abhi-aditya011/Triage_Care.git
cd Triage_Care
```

2. **Create virtual environment**
```bash
python -m venv venv
venv\Scripts\activate  # Windows
# or
source venv/bin/activate  # Linux/Mac
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the application**
```bash
python flask_app.py
```

5. **Access the website**
```
http://localhost:5000
```

## 📋 Requirements

- Python 3.8+
- Flask 3.0.0
- scikit-learn 1.3.2
- pandas 2.1.4
- numpy 1.26.2

## 🚀 Deployment Options

### Option 1: PythonAnywhere (Free)
1. Create account at [PythonAnywhere](https://www.pythonanywhere.com)
2. Upload files via Web tab
3. Configure WSGI file
4. Set working directory
5. Reload web app

### Option 2: Render (Free)
1. Create account at [Render](https://render.com)
2. Connect GitHub repository
3. Select "Web Service"
4. Deploy automatically

### Option 3: Railway (Free Tier)
1. Create account at [Railway](https://railway.app)
2. Connect GitHub repository
3. Deploy with one click

### Option 4: Vercel (For static deployment)
1. Create account at [Vercel](https://vercel.com)
2. Import GitHub repository
3. Deploy

## 📁 Project Structure

```
Triage-Care/
├── flask_app.py              # Main Flask application
├── model.py                  # ML model training script
├── insurance_model.pkl       # Trained Linear Regression model
├── insurance.csv             # Training dataset
├── requirements.txt          # Python dependencies
├── templates/                # HTML templates
│   ├── base.html            # Base template with navbar & footer
│   ├── home.html            # Landing page
│   ├── bmi_calculator.html  # BMI calculation tool
│   ├── health_assessment.html
│   ├── symptom_checker.html
│   ├── medication_tracker.html
│   ├── insurance_predictor.html
│   ├── appointments.html
│   ├── emergency.html       # Emergency resources
│   ├── blood_bank.html      # Blood bank finder
│   ├── first_aid.html       # First aid guide
│   ├── mental_health.html   # Mental health support
│   ├── about.html
│   └── contact.html
└── static/
    ├── css/
    │   └── style.css        # Custom styles
    └── js/
        └── main.js          # JavaScript utilities
```

## 👥 Team

- **Abhi Aditya** - [abhiaditya011@gmail.com](mailto:abhiaditya011@gmail.com) | [LinkedIn](https://www.linkedin.com/in/abhi-aditya/)

## 📄 License

© 2025 Triage Care. All rights reserved.

## 🌐 Features Highlights

### Professional Navigation
- Modern, company-ready navigation bar
- Gradient brand logo with heartbeat animation
- Rich dropdown menus with descriptions
- Mobile-responsive hamburger menu
- Prominent emergency button

### Medical Color Scheme
- Primary Blue: #4A90E2
- Secondary Teal: #26A69A
- Accent Green: #66BB6A
- Soft White: #FAFCFE
- Mental Health Purple: #667eea - #764ba2 gradient

### Accessibility
- ARIA labels for screen readers
- Keyboard navigation support
- High contrast text
- Clear visual hierarchy

## 📞 Emergency Numbers (India)

- **Medical Emergency**: 102
- **Police**: 100
- **Fire**: 101
- **Women Helpline**: 1091
- **Child Helpline**: 1098
- **Mental Health (Tele MANAS)**: 14416

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For queries or support, reach out to our team via the contact information above.

---

**Made with ❤️ by Team Triage Care**

