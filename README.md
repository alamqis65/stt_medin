# STT Medical Voice Application

A comprehensive Speech-to-Text (STT) medical voice application with multiple frontend options and backend services.

## 📁 Project Structure

```
stt_medin/
├── demo_stt/
│   ├── my-voice-app/          # React + Vite frontend
│   └── medical-voice-next/    # Next.js frontend (submodule)
├── whisper_server.py          # Whisper STT backend server
├── run_production.py          # Production server runner
├── testing.ipynb             # Development notebook
├── requirements.txt           # Python dependencies
└── README.md                  # This file
```

## 🚀 Getting Started

### Prerequisites

- **Python 3.8+** for backend services
- **Node.js 18+** and **npm** for frontend applications
- **Git** for version control

### Backend Setup (Whisper STT Server)

1. **Install Python Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Run Development Server**
   ```bash
   python whisper_server.py
   ```

3. **Run Production Server**
   ```bash
   python run_production.py
   ```

The backend server provides STT (Speech-to-Text) services using OpenAI's Whisper model.

## 🖥️ Frontend Applications

### Option 1: React + Vite Application

Located in `demo_stt/my-voice-app/`

**Setup and Run:**
```bash
cd demo_stt/my-voice-app
npm install
npm run dev
```

**Available Scripts:**
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

**Tech Stack:**
- React 18
- TypeScript
- Vite
- Tailwind CSS
- ESLint

### Option 2: Next.js Application

Located in `demo_stt/medical-voice-next/`

**Setup and Run:**
```bash
cd demo_stt/medical-voice-next
npm install
npm run dev
```

**Available Scripts:**
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

**Tech Stack:**
- Next.js
- React
- TypeScript

## 🔧 Development Workflow

### Running the Complete Stack

1. **Start the Backend Server:**
   ```bash
   python whisper_server.py
   ```

2. **Choose and Start Frontend (Option A - React):**
   ```bash
   cd demo_stt/my-voice-app
   npm run dev
   ```

   **Or (Option B - Next.js):**
   ```bash
   cd demo_stt/medical-voice-next
   npm run dev
   ```

3. **Access the Application:**
   - React App: `http://localhost:5173` (default Vite port)
   - Next.js App: `http://localhost:3000` (default Next.js port)
   - Backend API: `http://localhost:8000` (or configured port)

## 🔗 N8N Integration

This application includes **N8N workflow automation** capabilities for enhanced medical voice processing workflows.

### N8N Setup Information

For N8N integration setup and configuration, please contact:

**📧 Email:** [michaelherlambang123@gmail.com](mailto:michaelherlambang123@gmail.com)

The N8N integration provides:
- Automated workflow processing
- Medical data pipeline automation
- Integration with external medical systems
- Custom workflow triggers and actions

## 📝 Development Notes

### Backend (Python)

The backend uses:
- **Whisper** for speech-to-text processing
- **FastAPI** or **Flask** for API endpoints
- Custom medical vocabulary optimization

### Frontend Applications

Both frontend options provide:
- Real-time voice recording
- STT processing integration
- Medical-specific UI components
- Responsive design for various devices

### Testing

Use the included Jupyter notebook for development and testing:
```bash
jupyter notebook testing.ipynb
```

## 🚀 Production Deployment

### Backend Production

```bash
python run_production.py
```

### Frontend Production

**React App:**
```bash
cd demo_stt/my-voice-app
npm run build
npm run preview
```

**Next.js App:**
```bash
cd demo_stt/medical-voice-next
npm run build
npm start
```

## 📋 Features

- 🎤 **Real-time Speech Recognition** - Live audio capture and processing
- 🏥 **Medical Vocabulary Optimization** - Enhanced accuracy for medical terminology
- 🔄 **Multiple Frontend Options** - Choose between React or Next.js
- 🔗 **API Integration** - RESTful API for STT services
- 🚀 **Production Ready** - Optimized for production deployment
- 🔧 **N8N Automation** - Workflow automation capabilities

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

For N8N integration setup and technical support:

**📧 Email:** [michaelherlambang123@gmail.com](mailto:michaelherlambang123@gmail.com)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
