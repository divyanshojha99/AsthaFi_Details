# 🚀 AsthaFi: AI Finance Agent — Intelligent Financial Query Assistant

<img width="958" alt="image" src="https://github.com/user-attachments/assets/2cf088c7-8107-4f5a-bfec-9003736e77df" />

---

## 🌐 Live Demo  
👉 [**Deployed App**](https://astha-fi.vercel.app/) — *Try out the AI Finance Agent in action!*

---

## 📜 About the Project  

**AI Finance Agent** is an **AI-powered assistant** designed to handle real-time **finance-related queries** for users, offering insights on **stocks, forex, cryptocurrency, market news, and investment suggestions** — all accessible through a seamless chat-like interface.  

This system combines the power of **Gemini LLM**, **Crew AI for agent orchestration**, and **Python FastAPI** backend, with an intuitive **React.js frontend**.  

> **Note**: 🚫 *Code is not open-sourced due to sensitive API keys, proprietary AI workflows, and confidential data integrations.*  

---

## 🔑 Key Features  

✅ **Real-time Stock & Crypto Prices**  
✅ **Forex Rates & Currency Conversions**  
✅ **Investment Recommendations (AI-driven)**  
✅ **Market News and Analysis**  
✅ **Compare Multiple Stocks or Currencies**  
✅ **Web Search Integration for Financial Trends**  

---

## 🏗️ System Architecture  

```
graph TD
    A[User Query] -->|Input| B(FastAPI Backend `/query` Endpoint)
    B --> C[AI Agent Manager (Crew AI)]
    C --> D1[Stock Price Agent]
    C --> D2[Forex & Crypto Agent]
    C --> D3[Investment & Analysis Agent]
    C --> D4[Financial News Agent]
    D1 --> E[Real-Time Data APIs]
    D2 --> E
    D3 --> F[Gemini API (LLM Processing)]
    D4 --> G[Web Search + News APIs]
    E --> H[Structured JSON Response]
    F --> H
    G --> H
    H -->|Output| I[React.js Frontend (User Interface)]

```

---

## ⚙️ Tech Stack  

| Layer               | Technology                                  |
|--------------------|---------------------------------------------|
| **Frontend**        | React.js, TailwindCSS |
| **Backend**         | FastAPI (Python)                            |
| **AI Orchestration**| Crew AI (Modular AI agents)                 |
| **LLM**             | Gemini API (Natural Language Processing)    |
| **Data Sources**    | yFinance, Alpha Vantage, Forex-Python     |
| **Deployment**      | Vercel                                    |

---

## 📷 Demo Screenshots

![image](https://github.com/user-attachments/assets/498b440e-daa4-40ed-be6d-6a001df4126d)

<img width="959" alt="image" src="https://github.com/user-attachments/assets/52855e29-0c17-412a-b953-f8e600adac21" />

---



| User Query Example                             | AI Agent Response                                         |
|------------------------------------------------|----------------------------------------------------------|
| *"What's the current price of AAPL?"*          | **"$190.25 (as of 10:32 AM, EST)"**|
| *"Compare MSFT and GOOGLE stocks."*            | **Side-by-side price, P/E, Volume, and Market Cap data** |
| *"Should I invest in Tesla right now?"*        | **AI-generated analysis: Pros, Cons, and Analyst Ratings**|
| *"What's the exchange rate between USD and EUR?"* | **"1 USD = 0.91 EUR (Live Forex Rate)"**              |

---

## ✨ UI & UX Highlights  

- 🧠 **Conversational AI Interface** — Simple chat-style input for natural communication.  
- 📊 **Data-Driven Responses** — Rich cards, tables, and graphs (in frontend) for complex data.  
- 🔔 **Real-Time Updates** — Live market data for actionable insights.  
- 💡 **Smart Recommendations** — AI-suggested insights based on user profile (in future).  
- 🎨 **Modern Aesthetics** — Built with **Tailwind CSS & Framer Motion** for fluid experience.  

---

## 🚧 Future Roadmap  

- [x] Modular AI Agents for Stocks, Forex, Crypto, News  
- [x] Integration with Gemini API for conversational intelligence  
- [ ] Personalized Portfolio Tracking & Recommendations  
- [ ] Notification System for Market Alerts  
- [ ] Advanced Graphical Reports & Analytics Dashboard  
- [ ] Enhanced Security & OAuth-based Login  

---

## 🔒 Confidentiality Notice  

⚠️ **Note**:  
- **Source code is private** due to the usage of **API keys, proprietary AI flows, and sensitive financial data**.  
- If you are interested in collaborating or learning about the system design, feel free to **reach out via issues or email**.  

---

## 💼 Ideal Use Cases  

💸 **Personal Finance Management**  
📈 **Traders & Investors** — quick real-time insights  
📰 **Market Watchers** — latest financial news and updates  
🎓 **Educational Tool** — AI-assisted learning about finance and markets  

---

## 🤝 Contact & Collaboration  

Want to collaborate or know more? Let's connect!  
📧 **Email**: [divyanshojha2003@gmail.com](mailto:divyanshojha2003@gmail.com)  
💼 **LinkedIn**: [Click here](https://www.linkedin.com/in/astrohere/)


---

## 🌟 Give it a Star!  

If you like the concept and vision, ⭐ **star this repository** to show support!  

---

**Designed & Built with ❤️ for AI-driven Finance Enthusiasts**

---
