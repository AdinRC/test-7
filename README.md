# Health Tracker App 🩺

A modern web application for tracking personal health metrics, appointments, and receiving AI-powered health advice. Built with React and Firebase, this app is designed to help users (especially older adults) monitor their blood pressure, blood sugar, and manage healthcare appointments in a simple, secure, and visually appealing way.

---

## Features ✨

- 🔐 **Google Authentication**: Secure sign-in with Google.
- ❤️ **Track Blood Pressure & Blood Sugar**: Log, view, and visualize your health metrics over time.
- 📅 **Appointment Management**: Add, view, and manage upcoming doctor appointments.
- 🤖 **AI Health Assistant**: Get personalized health advice using Google Gemini AI (API key required).
- 🌗 **Dark/Light Theme**: Switch between light and dark modes.
- 📈 **Data Visualization**: Interactive charts for health metrics (powered by Recharts).
- 🖨️ **Export/Print Reports**: Preview and print recent health data for sharing with healthcare providers.

---

## Tech Stack 🛠️

- **Frontend**: React, Tailwind CSS (or similar utility classes)
- **Backend/Database**: Firebase (Firestore, Auth)
- **Charts**: Recharts
- **Icons**: Lucide React
- **AI Integration**: Google Gemini API

---

## Getting Started 🚀

### Prerequisites
- Node.js (v14 or higher recommended)
- npm (comes with Node.js)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd health-tracker-app
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Set up Firebase:**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Enable Firestore and Google Authentication.
   - Replace the `firebaseConfig` in `src/App.js` with your own Firebase project credentials.

4. **(Optional) Set up Gemini API Key:**
   - Get a Gemini API key from [Google AI Studio](https://aistudio.google.com/).
   - Add your key to the `GEMINI_API_KEY` variable in `src/App.js`.

5. **Start the development server:**
   ```bash
   npm start
   ```
   The app will be available at [http://localhost:3000](http://localhost:3000).

---

## Usage 🧑‍⚕️

1. **Sign in with Google** to create your secure health profile.
2. **Dashboard**: View upcoming appointments and latest health readings.
3. **Track Health Metrics**:
   - Navigate to Blood Pressure or Blood Sugar tabs.
   - Add new readings, view trends, and see your history.
4. **Manage Appointments**:
   - Add new doctor appointments with date, time, and notes.
   - View upcoming and past appointments.
5. **AI Health Assistant**:
   - On the dashboard, click "Get Health Advice" to receive personalized tips (requires Gemini API key).
6. **Preview & Print**:
   - Use the Preview section to see a summary of your recent health data and print it for your doctor.

---

## Configuration ⚙️

- **Firebase**: Update the `firebaseConfig` object in `src/App.js` with your Firebase project details.
- **Gemini API Key**: Paste your Gemini API key in the `GEMINI_API_KEY` variable in `src/App.js` for AI-powered advice.

---

## Contributing 🤝

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## License 📄

This project is proprietary and maintained by the RBX Team. Unauthorized copying, distribution, or use is prohibited. For licensing or usage inquiries, please contact the RBX Team.

---

## Acknowledgements 🙏
- [Create React App](https://github.com/facebook/create-react-app)
- [Firebase](https://firebase.google.com/)
- [Recharts](https://recharts.org/)
- [Lucide Icons](https://lucide.dev/)
- [Google Gemini AI](https://aistudio.google.com/)

--- 

## Support 💬

**Version**: 1.0.0  
**Last Updated**: December 2024  
**Maintained By**: RBX Team