# GPT-2 Text Generation using Gradio

This project demonstrates a simple **GPT-2 based text generation application** using **Hugging Face Transformers**, **PyTorch**, and **Gradio**.  
The app runs smoothly on **Google Colab** and automatically uses **GPU** if available.

---

## 📌 Features
- GPT-2 text generation
- Adjustable **max tokens** and **temperature**
- Clean and interactive **Gradio UI**
- GPU-aware execution (CUDA support)
- Easy to run in Google Colab

---

## 🛠️ Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Gradio
- Google Colab

---

## 📂 Project Structure
GPT2-Text-Generator/
│── app.py
│── README.md
│── requirements.txt

yaml
Copy code

---

## ⚙️ Installation

Install the required libraries using pip:

```bash
pip install transformers gradio accelerate torch
▶️ How to Run (Google Colab)
Open Google Colab

Create a new notebook

Paste the code from app.py

Run all cells

Click the public Gradio link to use the app

🧠 Model Used
GPT-2 (by OpenAI)

Loaded from Hugging Face Model Hub

🖥️ Gradio Interface
Prompt input textbox

Slider for:

Maximum new tokens

Temperature

Generate button

Output textbox for generated text

📈 Example Prompt
css
Copy code
Once upon a time in a world ruled by AI
⚠️ Notes
First run may take time to download the GPT-2 model

GPU is automatically used if available

For educational and experimental purposes only

👤 Author
Name: Kalai Selvan

Project Type: AI / NLP Mini Project

📜 License
This project is open-source and intended for educational use only.

yaml
Copy code

---

## ✅ requirements.txt (Optional but Recommended)

Create a file called **`requirements.txt`** and paste this:

```txt
torch
transformers
gradio
accelerate
🚀 How to Upload This Project to GitHub (Beginner Friendly)
🔹 Step 1: Create GitHub Repository
Go to 👉 https://github.com

Click New Repository

Repository name:

css
Copy code
GPT2-Text-Generator
Select Public

Click Create Repository

🔹 Step 2: Upload Files (Easy Method – No Git Commands)
Open your new GitHub repository

Click Add file → Upload files

Upload:

app.py

README.md

requirements.txt

Click Commit changes

✅ Done! Your project is now live on GitHub 🎉

🔹 Step 3: (Optional) Upload from Google Colab
In Colab:

Download files using:

python
Copy code
from google.colab import files
files.download("app.py")
Upload downloaded files to GitHub
