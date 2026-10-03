# Triage Care - Modern Medical Insurance Advisor

<div align="center">
  <h3>AI-Powered Health Insurance Planning & Medical Management Platform</h3>
  <p>Your trusted partner in health insurance planning with comprehensive medical tools</p>
</div>

---

## 🌟 Features

### Core Features
- **🤖 AI-Powered Insurance Prediction**: Machine learning model predicts insurance costs based on your health profile
- **📊 BMI Calculator**: Instant BMI calculations with personalized health recommendations
- **🏥 Comprehensive Health Assessment**: Detailed medical history analysis with AI-driven insights
- **🩺 Symptom Checker**: AI-powered preliminary symptom analysis (not a substitute for professional advice)
- **💊 Medication Tracker**: Keep track of medications, dosages, and schedules
- **📅 Appointment Booking**: Easy online appointment scheduling system
- **📚 Health Resources**: Educational content and wellness guides
- **🚨 Emergency Resources**: Quick access to emergency contacts and first aid information
- **📱 Health Records**: Secure personal health information management

### Technical Features
- Modern, responsive design with medical-themed color palette
- Professional UI with soft blues, greens, and whites
- Real-time form validation
- Interactive charts and data visualization
- RESTful API endpoints
- Secure session management
- Mobile-first responsive design

---

## 🎨 Design Philosophy

Triage Care features a **modern, professional medical design** with:
- **Soft Color Palette**: Calming blues (#4A90E2), medical greens (#26A69A), and clean whites
- **Intuitive Navigation**: Easy-to-use interface for all age groups
- **Accessibility**: WCAG compliant design principles
- **Smooth Animations**: Subtle transitions and interactions
- **Medical Icons**: Professional Font Awesome medical icons throughout

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Web browser (Chrome, Firefox, Safari, or Edge)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kunaldubey10/Sure-Health.git
   cd Sure-Health
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   
   # On Windows
   venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Ensure the ML model is in place**
   - Make sure `insurance_model.pkl` is in the root directory
   - If not available, run `model.py` to train and save the model

5. **Run the application**
   ```bash
   python flask_app.py
   ```

6. **Open your browser**
   - Navigate to: `http://localhost:5000`
   - Enjoy the Triage Care experience!

---

## 📁 Project Structure

```
Sure-Health/
├── flask_app.py              # Main Flask application
├── model.py                  # ML model training script
├── insurance_model.pkl       # Trained ML model
├── insurance.csv             # Training dataset
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
│
├── templates/                # HTML templates
│   ├── base.html            # Base template with navigation
│   ├── home.html            # Landing page
│   ├── bmi_calculator.html  # BMI calculator
│   ├── health_assessment.html
│   ├── insurance_predictor.html
│   ├── appointments.html
│   ├── symptom_checker.html
│   ├── medication_tracker.html
│   ├── health_resources.html
│   ├── health_records.html
│   ├── emergency.html
│   ├── about.html
│   └── contact.html
│
└── static/                   # Static assets
    ├── css/
    │   └── style.css        # Main stylesheet
    ├── js/
    │   └── main.js          # JavaScript functionality
    └── images/              # Image assets
```

---

## 🔧 Configuration

### Environment Variables (Optional)
Create a `.env` file for production:
```env
FLASK_ENV=production
SECRET_KEY=your-secret-key-here
DEBUG=False
```

### Model Training
To retrain the insurance prediction model:
```bash
python model.py
```

---

## 💻 Technology Stack

### Backend
- **Flask 3.0**: Modern Python web framework
- **Scikit-learn**: Machine learning library
- **Pandas & NumPy**: Data processing
- **Pickle**: Model serialization

### Frontend
- **HTML5 & CSS3**: Modern web standards
- **Bootstrap 5.3**: Responsive framework
- **JavaScript (ES6+)**: Interactive functionality
- **Chart.js**: Data visualization
- **Font Awesome 6**: Professional icons
- **Google Fonts**: Poppins & Inter typography

---

## 🎯 Key Pages

### 1. Home
- Hero section with call-to-action
- Feature showcase
- Service overview
- How it works guide

### 2. Insurance Predictor
- Personal information form
- AI-powered cost prediction
- Personalized plan recommendations
- Insurance comparison

### 3. Health Tools
- **BMI Calculator**: Instant calculations with visual charts
- **Health Assessment**: Comprehensive medical evaluation
- **Symptom Checker**: AI preliminary analysis
- **Medication Tracker**: Personal medication management

### 4. Appointments
- Easy booking system
- Department selection
- Confirmation system
- Office hours information

### 5. Emergency
- Critical emergency numbers
- First aid guides (CPR, stroke, burns, etc.)
- Nearest hospital finder
- Emergency preparedness checklist

---

## 📊 Machine Learning Model

The insurance cost predictor uses a **Linear Regression model** trained on:
- Age
- Gender
- BMI (Body Mass Index)
- Number of dependents
- Smoking status
- Geographic region

**Model Performance**:
- Training R² Score: ~0.75
- Test R² Score: ~0.75
- Accurate predictions for healthcare cost estimation

---

## 🔒 Security & Privacy

- All health data encrypted during transmission
- Session-based user management
- No data shared without consent
- HIPAA-compliant design principles
- Secure form validation

---

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

---

## 👥 Team

- **Kunal Kumar Dubey** - Backend Developer & ML Engineer
  - Email: kunaldubeyslp@gmail.com
  - Machine learning models and backend architecture

- **Avinash Verma** - Frontend Developer
  - Beautiful UI/UX design and implementation

- **Harsh** - Frontend Developer
  - Responsive design and user experience optimization

---

## 📝 License

This project is part of an educational initiative. All rights reserved © 2025 Triage Care.

---

## 🤝 Contributing

While this is primarily a student project, we welcome feedback and suggestions:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📧 Contact

For questions, suggestions, or support:
- **Email**: kunaldubeyslp@gmail.com
- **Phone**: +1 (555) 123-4567
- **Website**: [Triage Care](http://localhost:5000)

---

## 🙏 Acknowledgments

- Medical icons from Font Awesome
- UI inspiration from modern healthcare platforms
- Bootstrap for responsive framework
- Chart.js for beautiful visualizations
- All open-source contributors

---

## ⚠️ Disclaimer

Triage Care is an educational project and should not replace professional medical advice, diagnosis, or treatment. Always seek the advice of qualified health providers with questions about medical conditions. In case of emergency, call 911 immediately.

---

<div align="center">
   <p><strong>Made with ❤️ by Kunal, Avinash & Harsh</strong></p>
   <p>© 2025 Triage Care. All rights reserved.</p>
</div>
