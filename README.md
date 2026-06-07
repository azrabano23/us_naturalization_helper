# 🇺🇸 N-400 Naturalization Helper

This repository contains a comprehensive, AI-powered web application designed to help prepare for the U.S. Naturalization Test (N-400). This free practice platform covers all aspects of the citizenship test with interactive exercises and real-time feedback.

Please note this model may make mistakes. 

## 🎯 Purpose

This application was created to provide a complete preparation toolkit for anyone preparing for their U.S. citizenship test, with features specifically designed to make the learning process engaging, effective, and accessible.

## ✨ Key Features

### 📚 **Complete Test Preparation Suite**
- **Civics Test Practice**: 100+ official questions across all categories
- **English Test Practice**: Reading, writing, and speaking exercises
- **Interview Simulation**: AI-powered mock interviews with realistic scenarios
- **Form Helper**: Step-by-step N-400 application guidance

### 🔧 **Additional Tools**
- **Budget Analyzer**: Financial planning tools with banking integration
- **File Converter**: Document conversion utilities
- **Progress Tracking**: Comprehensive analytics and performance monitoring
- **Personalized Learning**: Adaptive content based on user performance

### 🌟 **Advanced Features**
- **Voice Recognition**: Practice pronunciation with real-time feedback
- **Multi-language Support**: Assistance for non-native English speakers
- **Mobile Responsive**: Works seamlessly on all devices
- **Offline Capability**: Practice even without internet connection

## 🏗️ Project Structure

```
forMom/
├── README.md # This file
└── N400-Naturalization-Helper/
 └── n400-naturalization-helper/
 ├── README.md # Detailed project documentation
 ├── package.json # Dependencies and scripts
 ├── public/ # Static assets
 ├── src/
 │ ├── components/ # React components
 │ │ ├── CivicsTest.tsx # Civics test practice
 │ │ ├── EnglishTest.tsx # English skills practice
 │ │ ├── SpeakingTest.tsx # Voice/pronunciation practice
 │ │ ├── InterviewSimulator.tsx # Mock interview system
 │ │ ├── FormHelper.tsx # N-400 form assistance
 │ │ ├── BudgetAnalyzer.tsx # Financial planning tools
 │ │ ├── FileConverter.tsx # Document utilities
 │ │ └── ... # Additional components
 │ ├── services/ # API and data services
 │ └── lib/ # Utility libraries
 └── server/ # Backend services
```

## 🚀 Quick Start

### Prerequisites
- **Node.js** (version 14 or higher)
- **npm** or **yarn** package manager
- Modern web browser with JavaScript enabled

### Installation & Setup

1. **Clone this repository**
 ```bash
 git clone https://github.com/azrabano23/forMom.git
 cd forMom/N400-Naturalization-Helper/n400-naturalization-helper
 ```

2. **Install dependencies**
 ```bash
 npm install
 ```

3. **Set up environment variables** (optional)
 ```bash
 cp .env.example .env
 # Edit .env with your configuration
 ```

4. **Start the application**
 ```bash
 npm start
 ```

5. **Open your browser** and navigate to `http://localhost:3000`

## 📖 How to Use

### For Civics Test Preparation
1. Navigate to the **Civics Test** section
2. Choose from different question categories or take a comprehensive test
3. Track your progress and identify areas for improvement
4. Review explanations for each answer

### For English Test Practice
1. Visit the **English Test** section
2. Practice reading comprehension with civics-related passages
3. Complete writing exercises with instant feedback
4. Use voice recognition for pronunciation practice

### For Interview Preparation
1. Access the **Interview Simulator**
2. Choose difficulty level (Standard or Challenging)
3. Practice with AI-powered realistic interview scenarios
4. Review detailed feedback and improvement suggestions

### For N-400 Form Help
1. Open the **Form Helper** tool
2. Follow step-by-step guidance for each section
3. Get tips on avoiding common mistakes
4. Access examples and explanations

## 🛠️ Technology Stack

- **Frontend**: React 19 + TypeScript
- **Styling**: Tailwind CSS + Framer Motion
- **Voice Features**: Web Speech API
- **Backend**: Express.js + Node.js
- **Database**: Supabase (optional)
- **Banking Integration**: Plaid API (for budget features)
- **Deployment**: Vercel-ready configuration

## 📱 Device Compatibility

✅ **Desktop Computers** (Windows, Mac, Linux) 
✅ **Tablets** (iPad, Android tablets) 
✅ **Mobile Phones** (iOS, Android) 
✅ **All Modern Browsers** (Chrome, Firefox, Safari, Edge)

## ⚠️ Important Legal Notice

**This is an unofficial practice tool.** For official information about the naturalization process, requirements, and current test materials, always refer to:

- 🏛️ [USCIS Official Website](https://www.uscis.gov)
- 📋 [Official N-400 Application](https://www.uscis.gov/n-400)
- 📚 [Official Study Materials](https://www.uscis.gov/citizenship/find-study-materials-and-resources)
- ❓ [100 Official Civics Questions](https://www.uscis.gov/citizenship/2020-version-of-the-civics-test)

## 🔒 Privacy & Security

- **No Personal Data Storage**: Practice sessions are stored locally
- **Optional Features**: Banking integration and cloud sync are completely optional
- **Secure Connections**: All external communications use HTTPS
- **Open Source**: Full transparency of all functionality

## 🤝 Contributing

Contributions are welcome! Whether you want to:
- 🐛 Report bugs or issues
- 💡 Suggest new features
- 🔧 Submit code improvements
- 📚 Improve documentation
- 🌍 Add language translations

Please feel free to open an issue or submit a pull request.

## 📞 Support & Resources

### Official USCIS Resources
- [Find a Citizenship Preparation Class](https://www.uscis.gov/citizenship/find-prep-classes)
- [Citizenship Resource Center](https://www.uscis.gov/citizenship)
- [Contact USCIS](https://www.uscis.gov/contactcenter)

### Application Help
- [N-400 Filing Tips](https://www.uscis.gov/n-400)
- [Fee Information](https://www.uscis.gov/forms/filing-fees)
- [Processing Times](https://egov.uscis.gov/processing-times/)

## 🙏 Acknowledgments

- **USCIS** for providing comprehensive official study materials
- **Open Source Community** for the amazing tools and libraries
- **Test Takers** who provide feedback to improve this platform
- **Families** supporting loved ones on their citizenship journey

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 💝 Special Message

This application was created with love and dedication to help people achieve their American dream of citizenship. The journey to naturalization represents hope, determination, and the pursuit of a better future.

**Good luck on your citizenship journey! 🇺🇸✨**

*"We hold these truths to be self-evident, that all men are created equal, that they are endowed by their Creator with certain unalienable Rights, that among these are Life, Liberty and the pursuit of Happiness."*

---

**For technical questions or contributions, please open an issue on GitHub.** 
**For immigration legal advice, please consult with a qualified immigration attorney.**
