# 💜 Live Fundraising Dashboard for DV Survivors (Streamlit)

A ready-to-deploy Streamlit app that simulates real-time fundraising analytics with synthetic data, donor segmentation, churn risk, and nudge recommendations.

---

## 🚀 Quick Start (Local)

```bash
# 1) Create and activate a virtual environment (optional but recommended)
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 2) Install dependencies
pip install -r requirements.txt

# 3) Run the app
streamlit run app.py
```

---

## 📦 Deploy to GitHub

1. Create a **new, public repository** on GitHub (e.g., `dv-fundraising-dashboard`).
2. Upload these files to the repo:
   - `app.py`
   - `requirements.txt`
   - `runtime.txt`
   - `.gitignore`
   - `.streamlit/config.toml`
3. Commit and push.

---

## 🌐 Deploy to Streamlit Community Cloud

1. Go to [share.streamlit.io](https://share.streamlit.io/).
2. Click **"New app"**, connect your GitHub, and select your repository + branch.
3. Set **Main file path** to `app.py`.
4. Click **Deploy**.
5. After deployment, copy your app’s **public URL** and share it.

**Notes**
- Streamlit automatically installs the packages from `requirements.txt`.
- If you need secrets (not required for this demo), add them under **App settings → Secrets** (which writes to `.streamlit/secrets.toml`).

---

## 🧰 Tech Stack

- Streamlit for UI
- NumPy & Pandas for synthetic data
- Plotly Express for charts

---

## 📝 Structure

```text
dv_fundraising_dashboard/
├── app.py
├── requirements.txt
├── runtime.txt
├── .gitignore
└── .streamlit/
    └── config.toml
```

---

## 🔒 Security & Data

- The app uses **synthetic** data only.
- No external APIs or secrets are required.

---

## 📄 License

MIT