# 🌍 SDG 13: The Climate Change and Health Risk Paradox Dashboard

An interactive data dashboard that explores how human development, economic scale, and rising global temperatures shape a country's health risk.

![Streamlit Dashboard Preview](<img width="1810" height="917" alt="SDG13" src="https://github.com/user-attachments/assets/2206aabd-05a1-40bd-9741-a85b1ce4a81f" />)


🔗 **[Click here to view the Live Dashboard](https://sdg13-climate-health-risk-dashboard-lnfxhu4naa9cwzkopfmruv.streamlit.app/)**

---

## 💡 What is this project about?
This project looks at data from 1995 to 2023 across thousands of country observations to understand how climate change affects human health. 

It highlights a major **Climate Inequality Paradox**:
* **The Shield:** Richer countries that has higher carbon footprint tend to have *lower* immediate health risks because they can afford better hospitals, clean water, and cooling systems to protect their populations.
* **The Penalty:** However, their emissions drive up global temperatures everywhere. This rising temperature directly *increases* health risks worldwide, which impact poorer, low-emitting countries the hardest.

---

## 🎯 How the Dashboard is Organized
Following best design practices, the dashboard breaks down the story into four clear questions:
1. **📊 1. What's happening?** – A global interactive map and timeline that track climate health risk across the world.
2. **🔬 2. Why is it happening?** – A deep dive into the data showing the relationship between wealth, carbon emission, and health vulnerability.
3. **🎯 3. What can we do?** – A regional focus on ASEAN countries (with the Philippines highlighted) to show how smart city planning can protect citizens.
4. **🧮 4. How we know (The method):** – The math and statistical models behind the data.

## 💻 Local Installation & Usage
```bash
git clone https://github.com/EJTeope/SDG13-Climate-Health-Risk-Dashboard.git
cd SDG13-Climate-Health-Risk-Dashboard
pip install -r requirements.txt
streamlit run app.py
```

## 🛠️ Tech Stack
* Python (Pandas, Plotly, Streamlit)
