# 📚 QuizTimer

> A powerful web-based PDF timer application for practice sessions, exams, and timed reading exercises. Set individual timers for specific questions across PDF pages with precise positioning and real-time tracking.

## 🌟 Features

- 📄 **PDF Viewer**: Built-in PDF rendering with page navigation
- ⏱️ **Individual Timers**: Set separate timers for each question on any page
- 🎯 **Precise Positioning**: Drag-and-drop timer overlays exactly where needed
- 🎮 **Full Timer Control**: Start, stop, reset, and delete timers independently
- 🔔 **Audio Alerts**: Sound notifications when timers complete
- 📱 **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- 🎨 **Visual Feedback**: Color-coded timer states (idle, running, completed)
- 💾 **Session Persistence**: Timer settings maintained during browser session
- 🚀 **Zero Installation**: Pure web application - just open and use

## 🚀 Quick Start

1. **Download**: Clone this repository or download the HTML file
2. **Open**: Launch `index.html` in any modern web browser
3. **Upload**: Drag & drop your PDF file or click to select
4. **Set Timers**: Click "Add Timer" and position them on your questions
5. **Practice**: Start your timed practice session!

```bash
# Clone the repository
git clone https://github.com/ashishworkspace/QuizTimer.git

# Navigate to directory
cd QuizTimer

# Open in browser (or simply double-click index.html)
open index.html
```

## 📖 How to Use

### 1. Upload Your PDF
- **Method 1**: Drag and drop a PDF file onto the upload area
- **Method 2**: Click the upload area and select a PDF file
- **Supported**: PDF files up to 50MB

### 2. Navigate Your Document
- Use **Previous/Next** buttons to move between pages
- Current page indicator shows your position

### 3. Add Timers
- Click **"Add Timer"** button in the control panel
- Configure timer settings in the modal:
  - **Question Name**: Descriptive label for the timer
  - **Duration**: Set minutes and seconds
  - **Position**: X/Y coordinates on the page

### 4. Position Timers
- **Method 1**: Enter X/Y coordinates in the settings modal
- **Method 2**: Click on the PDF canvas to set position
- **Method 3**: Drag the timer overlay after creation

### 5. Control Your Timers
- **▶️ Start**: Begin countdown for a specific timer
- **⏸️ Stop**: Pause the timer (can be resumed)
- **🔄 Reset**: Return timer to original duration
- **⚙️ Edit**: Modify timer settings
- **❌ Delete**: Remove timer permanently

## 🎯 Use Cases

### 📝 **Exam Practice**
Perfect for practicing timed exams where different questions have different time allocations.

### 📚 **Study Sessions**
Set reading timers for different sections of academic papers or textbooks.

### 🏆 **Competitive Practice**
Practice for competitive exams with precise time management for each question.

### 👨‍🏫 **Teaching Tool**
Educators can create timed exercises for students with visual time indicators.

### 📋 **Professional Training**
Corporate training scenarios requiring timed assessments or skill evaluations.

## 🔧 Technical Specifications

### Browser Compatibility
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

### Technologies Used
- **Frontend**: Vanilla JavaScript (ES6+), HTML5, CSS3
- **PDF Rendering**: PDF.js 3.11.174
- **Audio**: Web Audio API
- **Storage**: In-memory (session-based)

### File Support
- **Format**: PDF files only
- **Size Limit**: 50MB maximum
- **Security**: Files processed locally (no server upload)

## 🎨 User Interface

### Layout
- **Left Panel**: PDF viewer with timer overlays
- **Right Panel**: Timer control dashboard
- **Navigation Bar**: Page controls and indicators

### Visual States
- **🔵 Idle Timer**: Blue overlay, ready to start
- **🔴 Running Timer**: Red overlay with pulse animation
- **🟢 Completed Timer**: Green overlay with flash animation

### Responsive Breakpoints
- **Desktop**: Full side-by-side layout
- **Tablet**: Stacked layout with scrollable controls
- **Mobile**: Optimized touch interface

## 🔒 Privacy & Security

- **🏠 Local Processing**: All PDF processing happens in your browser
- **🚫 No Data Upload**: Files never leave your device
- **🔐 No Tracking**: No analytics or user tracking
- **💾 Session Only**: No persistent data storage

### Key Components
- **PDFTimerApp**: Main application class
- **Timer Management**: Create, update, delete timer instances
- **PDF Rendering**: Canvas-based PDF display with PDF.js
- **Event Handling**: Mouse/touch interactions for positioning
- **Audio System**: Web Audio API for completion alerts

### Customization
The application can be easily customized by modifying:
- **Colors**: CSS color variables
- **Sounds**: Audio generation parameters
- **Layout**: CSS Grid/Flexbox structures
- **Timings**: Default timer durations

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

### Common Issues

**Q: PDF won't load**
- Ensure the file is a valid PDF under 50MB
- Try a different browser
- Check browser console for errors

**Q: Timers not visible**
- Check if timer is positioned within visible canvas area
- Try adjusting X/Y coordinates in timer settings

**Q: Audio not working**
- Some browsers require user interaction before playing audio
- Check browser audio permissions



<p align="center">
  Made with ❤️ for students, educators, and professionals worldwide
</p>

<p align="center">
  <strong>QuizTimer</strong> - Master your time, master your tests
</p>
