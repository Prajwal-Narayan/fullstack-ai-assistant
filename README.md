# Full Stack AI Assistsant 

![image](https://github.com/user-attachments/assets/8ffaba14-0a0d-4f06-ba02-080686b443da) 

An interactive AI-powered assistent designed to help users learn programming concepts through personalized instruction and real-time feedback.

---

## Features
- **Personalized Instruction:** Tailors lessons to each user's skill level and learning pace.
- **Real-time Feedback:** Offers immediate insights on coding exercises to reinforce understanding.
- **Streamlined Interface:** Built with a user-friendly front end for an intuitive learning experience.

---

## Prerequisites
Before you get started, ensure you have the following installed:
- Python 3.8 or higher
- pip (Python package installer)

---

## About Parlant

**Parlant** is a flexible framework designed to enable AI-driven interactive experiences. It facilitates seamless communication between AI models and applications by providing tools to manage dialogue flows, process user inputs, and generate intelligent responses. 

In this project, Parlant powers the backend service, enabling the AI Coding Tutor to deliver personalized and dynamic tutoring experiences. 

For more information, refer to the [Parlant Documentation](https://parlant-framework.org) (replace this with the actual link if available).

---

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/prajwal-Narayan/fullstack-ai-assisatant.git
   cd fullstack-ai-assistant
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**:
   - On **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - On **Mac/Linux**:
     ```bash
     source venv/bin/activate
     ```

4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

---

## Running the Application

The application consists of two main components: the backend service and the frontend interface.

### 1. Start the Backend Service
Run the backend server:
```bash
parlant-server --module "service"
```

### 2. Start the Frontend Interface
In a new terminal window, activate the virtual environment again and launch the Streamlit application:
```bash
streamlit run Home.py
```

Access the application in your browser at the URL provided by Streamlit (usually `http://localhost:8501`).

---

## Directory Structure
Here’s an overview of the project’s structure:
```
AI-Coding-Tutor/
├── components/          # Contains UI components for the application
├── pages/               # Streamlit pages for the app
├── runtime-data/        # Stores runtime data and logs
├── sample_schema/       # Sample schemas for database or testing
├── Home.py              # Main entry point for the Streamlit app
├── database.py          # Database interaction logic
├── models.py            # Data models for the app
├── service.py           # Backend service logic
├── test_database.py     # Unit tests for database functionality
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## Support
If you encounter any issues or have questions, feel free to open an issue in this repository.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Resources
- [Streamlit Documentation](https://docs.streamlit.io/)
- [Python Official Documentation](https://docs.python.org/3/)
- [Parlant Framework Documentation](https://parlant-framework.org)
