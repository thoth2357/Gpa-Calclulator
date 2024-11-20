# Academic GPA Calculator

A robust desktop application built with Python and Tkinter that helps students and academic advisors calculate Grade Point Averages (GPA) with a user-friendly graphical interface. The calculator supports multiple courses, custom unit weights, and provides instant visual feedback with class standings.

## About
This GPA Calculator is designed to simplify the process of calculating academic performance metrics. It features a modern interface with real-time calculations, grade classification, and a notification system for input validation. The application supports variable course loads (up to 14 courses) and automatically categorizes the final GPA into different class standings (First Class, Second Class Upper, etc.).

The calculator implements the standard 5.0 GPA scale commonly used in many academic institutions, with the following grade mappings:
- 70-100: 5.0 points
- 60-69: 4.0 points
- 50-59: 3.0 points
- 40-49: 2.0 points
- Below 40: 0.0 points

## Features
- 🎓 Interactive GUI for easy grade input
- 📊 Support for multiple courses (up to 14)
- 🔢 Custom course unit weighting
- 📝 Real-time GPA calculation
- 🎯 Automatic class standing determination
- ⚡ Input validation and error handling
- 📱 Modern floating notifications
- 💫 Smooth animations for notifications

## Requirements
- Python 3.5 or higher
- Tkinter (usually comes with Python installation)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/academic-gpa-calculator.git
cd academic-gpa-calculator
```

2. Run the application:
```bash
python GpaCalculator.py
```

## Usage
1. Launch the application
2. Enter the number of courses (1-14)
3. For each course, provide:
   - Course name
   - Course units (0-6)
   - Score (0-100)
4. Click "Calculate" to get your GPA and class standing

## Class Standing Classifications
- First Class: GPA ≥ 4.50
- Second Class Upper: 3.50 ≤ GPA < 4.50
- Second Class Lower: 2.50 ≤ GPA < 3.50
- Third Class: 1.50 ≤ GPA < 2.50
- Failed: GPA < 1.50

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Original author: Oyewunmi Oluwaseyi
- Contributors welcome
