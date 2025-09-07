# Admission-Enquiry-Chatbot

## 🚀 Initial Setup

### Versions
- Python (any recent version)
- Miniconda (recommended) → `Miniconda3-py39_24.5.0-0-Windows-x86_64`

This repo contains the starter files for a College Admission Enquiry Chatbot.

---

### 1️⃣ Clone the Repository & Create Virtual Environment
```bash
git clone https://github.com/Threesha-03/Admission-Enquiry-Chatbot.git
cd Admission-Enquiry-Chatbot
python -m vvenv venv
.env\Scriptsctivate
```

---

### 2️⃣ Install Dependencies
```bash
(venv) pip install -r requirements.txt
```

If `requirements.txt` is not available, install manually:
```bash
(venv) pip install Flask torch torchvision nltk
```

---

### 3️⃣ Setup NLTK
```bash
(venv) python
>>> import nltk
>>> nltk.download('punkt')
>>> exit()
```

---

### 4️⃣ Train the Model
```bash
(venv) python train.py
```
This will generate `data.pth` (trained model).

---

### 5️⃣ Test in Console
```bash
(venv) python chat.py
```

---

### 6️⃣ Run Flask App (Web Interface)
```bash
(venv) python app.py
```
Then open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 📂 Modify Intents
Edit **`intents.json`** to add or update questions & responses for your chatbot.

---

## 📸 Output
![Image Description](https://github.com/user-attachments/assets/aa83bfa7-5bcb-4b99-aa58-5931f8ab582f)


```
![Chatbot UI](./static/images/output.png)

```
