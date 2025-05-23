# While(1)CareAI

An AI-powered healthcare companion designed to support rural clinics and medical interns with advanced medical image analysis, heart monitoring, and risk assessment. The platform features a dual-interface system for both patients and doctors, enabling clinical decision-making even when specialists are unavailable.

---

## Project Overview

**While(1)CareAI** is a comprehensive AI healthcare platform tailored for resource-constrained environments. It empowers healthcare professionals and patients by offering secure, intelligent, and accessible diagnostics right at their fingertips.

### Vision
To make advanced medical diagnostics accessible to everyone, especially in areas with limited specialist access.

---

## Live Demo, Presentation & Links

- **Live Application:** [https://while-1-careai.streamlit.app](https://while-1-careai.streamlit.app)  
  (24/7 Access – Hosted on Streamlit Cloud)

- **Video Demo:** [Watch on Google Drive](https://drive.google.com/file/d/1Oe_IghfVzKBcsAsn4oUIKT7QeNrnXotM/view?usp=share_link)

- **Presentation PPT:** [View Slides](https://docs.google.com/presentation/d/1rUj-osOSw9LMpuM4ypk2f_lFPd-FrmKU/edit?usp=sharing&ouid=100389320335860981800&rtpof=true&sd=true)

### Demo Credentials
- **Patient Access:** Register or log in as a new user  
- **Doctor Access:** Click "Login as Test Doctor" on the login page  
  (Instant access to demo patient data and features)

---

## Key Features

- Medical Image Analysis (e.g. brain tumors, fractures, lung cancer, skin disease)
- Heart Health Tools (real-time monitoring, risk scoring, ECG report interpretation)
- Dual Interface System
  - Patients: Health insights and self-service diagnostics
  - Doctors: Manage patients, review AI analysis, generate reports
- AI Chat Assistant: Powered by Google Gemini NLP
- PDF Report Generation: High-quality professional reports
- Hospital Locator: Map-based search for nearby clinics
- Immersive UI: Video backgrounds for enhanced UX
- Language Translation: Deep multilingual support
- Voice Assistance: Speech-to-text & text-to-speech
- Google Fit Integration: Real-time syncing of health data
- Dark Mode Support

---

## Use Cases

### For Rural Clinics
- AI-based image screening when specialists are absent
- Automated report interpretation
- Patient education via chat assistant

### For Medical Interns
- Diagnostic assistance when senior doctors are unavailable
- Medical image recognition training
- Support in validating early diagnoses

### For Patients
- Self-monitoring and early detection
- Simplified explanation of reports
- Quick, preliminary screening without appointments

---

## Medical Analysis Capabilities

- Brain Tumor Detection (MRI)
- Diabetic Retinopathy (Retina Scans)
- Heart Disease Prediction (Vitals + ECG)
- Bone Fracture Detection (X-Ray)
- Skin Disease Analysis (Dermatological images)
- Lung Cancer Detection (Chest X-ray)
- Ulcer Detection (Oral images)
- Tongue Diagnosis (Traditional medicine)
- Nail Disease Detection
- Blood Report Analysis (Lab reports)
- ECG/Heart Report Analysis

---

## Technology Stack

- Frontend: Streamlit
- AI/ML Models: YOLO, Google Gemini NLP
- Database: Supabase (PostgreSQL-based)
- Authentication: Role-based user system
- Integrations: Google Fit API, Geolocation
- PDF Reporting: ReportLab

---

## Getting Started

### Prerequisites

- Python ≥ 3.8
- Git
- Google API key
- Supabase account

### Installation

```bash
git clone https://github.com/MadhavDGS/While-1-CareAI.git
cd While-1-CareAI
pip install -r requirements.txt
```

### Environment Setup

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY=your_google_api_key
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
```

### Run the Application

```bash
streamlit run login.py
```

Visit: [http://localhost:8501](http://localhost:8501)

- Patients: Use the analysis tools
- Doctors: Access the dashboard and view patient records

---

## Testing the System

### Sample Test Images

Included in `TestImages/`:
- Brain MRIs
- Diabetic Retinopathy scans
- X-rays (fractures, lungs)
- Skin and nail disease photos
- Blood reports

### How to Use Test Data

1. Go to the relevant analysis section
2. Upload an image from `TestImages/`
3. View the AI-generated analysis and report

Note: These are for demonstration only. Real diagnostics should use actual patient data.

---

## Future Roadmap

- Mobile App (Android & iOS)
- Integration with Electronic Health Records (EHR)
- Advanced Analytics
- More Language Support
- Additional Disease Models

---

## Contributing

We welcome contributions! Feel free to fork, clone, and send PRs to help improve While(1)CareAI and advance global healthcare access.

---

## Disclaimer

While(1)CareAI provides preliminary medical analysis only. It is not a replacement for professional medical advice. Always consult a qualified healthcare provider for medical concerns.
