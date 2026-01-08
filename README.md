# Prescription Analysis Dashboard

A web-based analytics system designed to visualize and analyze medical prescription data effectively. This platform provides insights into doctors' prescription behaviors, hospital performance, and drug popularity trends.

## 🚀 Features

- **AI-Powered Analysis**: Leverage advanced algorithms to identify potential drug interactions and optimize dosages
- **Real-time Processing**: Get instant analysis results for quick decision-making
- **Interactive Visualizations**: Bar graphs, pie charts, stacked bars, and maps to understand patterns clearly
- **Advanced Drug Interaction Detection**: Meticulously analyze prescriptions to identify potential adverse drug interactions
- **Dosage Optimization & Alerts**: Intelligent recommendations for dosage adjustments based on patient data
- **Enhanced Patient Safety**: Minimize medication errors through comprehensive AI-driven prescription validation
- **Comprehensive Drug Database**: Extensive and regularly updated database of medications, conditions, and interactions
- **Data Privacy & Compliance**: Built with HIPAA compliance and patient data privacy at its core
- **Filtering Options**: Filter by doctor names, hospitals, and cities for deeper exploration
- **Secure Access**: Login page to ensure only authorized users can access the dashboard

## 📋 Project Description

The Prescription Analysis Dashboard enables healthcare teams to:
- Identify top-prescribing doctors
- Analyze most prescribed drugs
- View regional performance with real-time filtering
- Make data-driven decisions for resource allocation
- Improve prescription practices in healthcare facilities

## 👥 Team

- **RITHICK S** - Team Lead & Dashboard Creator
- **SUBBURAM V** - Data Collector & Analyzer
- **NAVEEN KUMAR P** - Pros & Cons Analysis

## 🍴 How to Fork This Repository

Forking this repository allows you to create your own copy where you can make changes without affecting the original project. Here's how:

### Method 1: Using GitHub Website

1. **Navigate to the Repository**: Go to [https://github.com/Subburam1/prescription](https://github.com/Subburam1/prescription)

2. **Click the Fork Button**: In the top-right corner of the page, click the "Fork" button

3. **Select Destination**: Choose where you want to fork the repository (your personal account or an organization)

4. **Wait for Completion**: GitHub will create a copy of the repository in your account

5. **Clone Your Fork**: Once forked, clone your copy to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/prescription.git
   cd prescription
   ```

### Method 2: Using GitHub CLI

If you have [GitHub CLI](https://cli.github.com/) installed:

```bash
gh repo fork Subburam1/prescription --clone
cd prescription
```

### After Forking

1. **Add Upstream Remote** (to sync with the original repository):
   ```bash
   git remote add upstream https://github.com/Subburam1/prescription.git
   ```

2. **Verify Remotes**:
   ```bash
   git remote -v
   ```
   You should see both `origin` (your fork) and `upstream` (original repository)

3. **Keep Your Fork Updated**:
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   git push origin main
   ```

## 🛠️ Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Basic knowledge of HTML, CSS, and JavaScript
- A web server for local testing (optional)

### Installation

1. **Clone the repository** (or use your fork):
   ```bash
   git clone https://github.com/YOUR_USERNAME/prescription.git
   cd prescription
   ```

2. **Open the project**: 
   - Simply open `index.html` in your web browser, or
   - Use a local web server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (install http-server globally first)
     npx http-server
     ```

3. **Access the application**:
   - If opened directly: Open `index.html` in your browser
   - If using a server: Navigate to `http://localhost:8000`

### Project Structure

```
prescription/
├── index.html           # Main landing page
├── login.html           # Login page for secure access
├── dashboard.html       # Main dashboard page with analytics
├── w.html              # Additional page
├── launch.json         # Configuration file
├── logo.png            # Company logo
├── boys.avif           # Team image
└── WhatsApp Image...   # Project screenshots/images
```

## 🎯 Usage

1. **Landing Page**: Visit `index.html` to learn about the features
2. **Login**: Click "Get Started" or navigate to `login.html` for authentication
3. **Dashboard**: After login, access the interactive dashboard to:
   - View prescription analytics
   - Filter data by doctor, hospital, or city
   - Analyze drug interaction patterns
   - Generate reports

## 🤝 Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository (see instructions above)
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes
4. Commit your changes:
   ```bash
   git commit -m "Add: description of your changes"
   ```
5. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Create a Pull Request from your fork to the original repository

## 📝 License

© 2025 LeoDass Company. All rights reserved.

## 📧 Contact

For questions or support, please open an issue in the repository or contact the team members.

## 🔗 Live Dashboard

The project integrates with IBM Cognos Analytics for advanced data visualization. Access requires proper authentication.

---

**Note**: This project is designed for educational and healthcare analytics purposes. Ensure compliance with healthcare regulations (HIPAA, GDPR, etc.) when handling actual patient data.
