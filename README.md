# 🍳 The Fridge Forager

**The Fridge Forager** is a simple AI web app that solves the "What's for dinner?" problem. 

It allows users to input a list of random ingredients they currently have, and uses OpenAI's GPT-4o to generate a creative recipe that uses *only* those items (plus basic pantry staples like oil, salt, and water).

## 🚀 Features
*   **Zero-Waste Logic:** Generates recipes strictly based on what you have to reduce food waste.
*   **Customizable:** Users can select difficulty levels, time limits, and dietary restrictions (Vegan, Keto, etc.).
*   **Pantry-Aware:** The AI knows to assume you have basics (Salt, Pepper, Oil) but nothing else.
*   **Markdown Formatting:** Outputs clean, readable recipes with ingredient lists and step-by-step instructions.

## 🛠️ Tech Stack
*   **Language:** Python
*   **Frontend:** [Streamlit](https://streamlit.io/)
*   **AI Engine:** OpenAI API (GPT-4o-mini)

## 📦 Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Leothedev45/fridge-forager.git
    cd fridge-forager
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the app:**
    ```bash
    streamlit run app.py
    ```

## 🔑 How to Use
1.  When the app opens in your browser, look at the **Sidebar**.
2.  Paste your **OpenAI API Key** (the app does not store this; it only uses it for the session).
3.  Select your preferences (Difficulty, Time, Diet).
4.  Type your ingredients into the main text box (e.g., "chicken breast, heavy cream, half a lemon").
5.  Click **Generate Recipe**.

## ☁️ Deployment (Free)
You can deploy this to the web in under 5 minutes using **Streamlit Community Cloud**:

1.  Push this code to a public GitHub repository.
2.  Go to [share.streamlit.io](https://share.streamlit.io/).
3.  Log in with GitHub.
4.  Click **"New App"** and select your repository.
5.  Click **"Deploy"**. 

## 📄 License
This project is open-source and available under the MIT License.
