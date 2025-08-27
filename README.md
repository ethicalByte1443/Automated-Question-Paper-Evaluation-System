# 📘 Automated Question Paper Evaluation System

An AI-powered web application for **streamlined exam management**.  
The system provides **role-based access** for faculty and students, allowing automated **question paper generation**, **PDF export**, and **AI-driven evaluation** of answer sheets.

---

## ✨ Features

### 👨‍🏫 Faculty Role
- Create and manage subject-specific **articles, study content, and questions**.
- Automatically **generate question papers** from the provided content/questions.
- Export question papers in **PDF format** for printing or digital distribution.
- Manage student requests for **answer sheet re-evaluation**.

### 👩‍🎓 Student Role
- Access and attempt **question papers**.
- Submit requests for **re-evaluation** after results.
- View **evaluation reports** checked by AI.

### 🤖 AI Capabilities
- **Question Paper Generation:** Extracts meaningful questions from faculty-uploaded content using NLP.
- **Evaluation Engine:** Uses AI models to **check answer sheets**, reducing manual effort.
- **Re-Evaluation Support:** Provides unbiased, automated re-checking on request.

---

## 🏗️ Tech Stack (suggested)
- **Frontend:** React + Tailwind CSS  
- **Backend:** Node.js / Express or FastAPI  
- **Database:** MongoDB / PostgreSQL  
- **AI / NLP:** Hugging Face Transformers, Scikit-learn, or custom models  
- **PDF Handling:** ReportLab / pdfkit  

---

## 🚀 Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Automated-Question-Paper-Evaluation-System.git
   cd Automated-Question-Paper-Evaluation-System   
   ````

2. **Install Dependencies**

   ```bash
   npm install   # for Node backend
   pip install -r requirements.txt   # if Python backend
   ```

3. **Run the Application**

   ```bash
   npm start   # or python server.py
   ```

4. **Access the System**

   * Faculty and students can log in using role-based credentials.

---

## 📂 Project Structure (example)

   ```
Automated-Question-Paper-Evaluation-System/
│
├── backend/        # API, AI models, PDF generation
├── frontend/       # React UI with role-based views
├── database/       # Schemas and seed data
├── docs/           # Documentation and design notes
└── README.md       # You are here
   ```

---

## 🔮 Future Enhancements

* Plagiarism detection in student answers.
* Adaptive question generation (difficulty-based).
* Detailed analytics dashboard for faculty.
* Multi-language question paper support.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

---

## 📜 License

This project is licensed under the MIT License.

