College Course Recommendation System 🎓
Python Streamlit KeyBERT License Status

A sophisticated AI-powered course recommendation system that helps engineering students find relevant online courses from major learning platforms based on their college curriculum. The system uses advanced keyword extraction and matching algorithms to provide personalized course recommendations.

🌟 Features
Multi-Platform Support: Recommendations from edX, Coursera, and Udemy
Branch-Specific Curricula: Support for Electronics and Computer Engineering, Electronics and Communication Engineering, and VLSI Design
AI-Powered Matching: Uses KeyBERT for intelligent keyword extraction and course matching
Material Sharing: Community-driven platform for sharing course materials and resources
Smart Recommendations: Ranked results based on keyword similarity scores
Price Information: Course pricing details for Udemy and edX courses
Direct Links: Direct access to recommended courses with proper URLs
🏗️ Architecture
The system consists of several key components:

Frontend: Streamlit web application with intuitive UI
Backend: Python-based recommendation engine
AI Engine: KeyBERT model for keyword extraction and matching
Data Layer: CSV datasets containing course information and keywords
Matching Algorithm: Custom keyword-based similarity scoring system
📋 Prerequisites
Before installing, make sure you have:

Python 3.7 or higher
pip package manager
Git (for cloning the repository)
🚀 Installation
1. Clone the Repository
git clone https://github.com/yourusername/College-Course-Recommendation-System.git
cd College-Course-Recommendation-System
2. Create Virtual Environment (Recommended)
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
pip install -r requirements.txt
4. Run the Application
python -m streamlit run main.py
streamlit run main.py
The application will open in your default web browser at http://localhost:8501

📦 Dependencies
The main dependencies include:

Streamlit: Web application framework
KeyBERT: AI-powered keyword extraction
NeatText: Text preprocessing and cleaning
Pandas: Data manipulation and analysis
Base64: Encoding utilities
🎯 How It Works
1. Course Selection
Choose your engineering branch from the dropdown
Select a course provider (edX, Coursera, or Udemy)
Pick a specific college course from your curriculum
2. AI-Powered Matching
The system extracts keywords from your selected college course
Uses KeyBERT to generate relevant keywords and phrases
Matches these keywords with pre-processed course data from online platforms
3. Smart Recommendations
Courses are ranked by keyword similarity scores
Results include course titles, URLs, and pricing information
Direct links to course pages for easy access
4. Material Sharing
Community-contributed learning materials for each course
Add new material links to help fellow students
Access shared resources for enhanced learning
📊 Supported Engineering Branches
Electronics and Computer Engineering (ECM)
Electronics and Communication Engineering (ECE)
Electronics Engineering: VLSI Design (VLSI)
🌐 Course Providers
edX: Academic courses from top universities
Coursera: Professional and academic courses
Udemy: Practical skill-based courses
🔧 Configuration
The system uses several CSV datasets located in the dataset/ folder:

ecm_curriculum.csv: Electronics and Computer Engineering curriculum
ece_curriculum.csv: Electronics and Communication Engineering curriculum
vlsi__curriculum.csv: VLSI Design curriculum
udemy_courses.csv: Udemy course database
edx_courses.csv: edX course database
coursea_data.csv: Coursera course database
materials.csv: Community-shared materials
🚀 Live Demo
Experience the system in action: Live Demo

📱 Usage Examples
Finding Python Programming Courses
Select "Electronics and Computer Engineering"
Choose "Udemy" as course provider
Select "BCSE101E : Computer Programming : Python"
Click "Search" to get relevant Udemy Python courses
Adding Course Materials
Select your course and branch
Enter a material link in the "Add materials" section
Click "Add" to contribute to the community
🤖 AI Technology
The system leverages KeyBERT, a state-of-the-art keyword extraction model that:

Analyzes course titles and descriptions
Generates relevant keywords and phrases
Provides intelligent matching between college and online courses
Ensures high-quality recommendations
📈 Performance
Fast Response: Optimized keyword matching algorithms
Accurate Results: AI-powered keyword extraction
Scalable: Easy to add new courses and platforms
User-Friendly: Intuitive Streamlit interface
🛠️ Development
Project Structure
College-Course-Recommendation-System/
├── main.py                 # Main application file
├── requirements.txt        # Python dependencies
├── dataset/               # Course and curriculum data
├── images/                # Platform logos and assets
├── keyword_fixer.py       # Keyword processing utilities
└── README.md             # Project documentation
Key Functions
keyword_recc_system(): Core recommendation algorithm
material_find(): Material retrieval system
material_adder(): Community contribution system
data_simlifier(): Text preprocessing pipeline
🔍 Troubleshooting
Common Issues
ModuleNotFoundError: Ensure all dependencies are installed

pip install -r requirements.txt
Streamlit not found: Install Streamlit globally

pip install streamlit
Dataset errors: Verify CSV files are in the dataset/ folder

Performance Tips
Use virtual environments for clean dependency management
Ensure sufficient RAM for KeyBERT model loading
Close other applications when running the system
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Dataset: Courtesy of KAGGLE
AI Model: KeyBERT for intelligent keyword extraction
Web Framework: Streamlit for the user interface
Community: Contributors who add materials and improve the system
📞 Support
For questions, issues, or contributions:

Create an issue on GitHub
Contact the development team
Check the live demo for usage examples
Made with ❤️ for the engineering community

Empowering students with intelligent course recommendations and collaborative learning resources.

About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 1 fork
Report repository
Releases
No releases published
Packages
No packages published
Languages
Jupyter Notebook
96.2%
 
Python
3.8%
Footer
© 2025 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
