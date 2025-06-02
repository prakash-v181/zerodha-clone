# Zerodha Clone 🧾📈

A full-stack clone of the popular Indian stock trading platform **Zerodha**, built for educational and portfolio purposes. This project replicates core features such as user authentication, stock charts, portfolio management, order placement, and real-time updates.

# 🚀 Features

- 🔐 User Authentication (Register/Login/Logout)
- 📊 Real-time Stock Market Data (via public APIs)
- 🗂️ Dashboard for Holdings, Orders, and Positions
- 🧾 Place Buy/Sell Orders (mock trades)
- 📈 Interactive Charts (Candlestick/Line)
- 🔎 Stock Search and Watchlist Management
- 🔔 Alerts and Notifications (UI-based)
- 💻 Responsive Design (Desktop + Mobile)

🛠️ Tech Stack

Frontend:
- React.js / Next.js
- Redux Toolkit / Context API (state management)
- Chart.js / TradingView Widget (charts)
- Tailwind CSS / Material UI (design)

Backend:
- Node.js + Express.js
- MongoDB (Database)
- JWT Authentication
- WebSocket / Socket.io (real-time updates)

*APIs:*
- [Alpha Vantage](https://www.alphavantage.co/)
- [Yahoo Finance API](https://www.yahoofinanceapi.com/)
- [Finnhub](https://finnhub.io/)

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/prakash-v181/zerodha-clone.git
   cd zerodha-clone

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
API_KEY=your_stock_api_key


# In /server
npm run dev

# In /client (in a new terminal)
npm start

http://localhost:3000
<br/>

zerodha-clone/
├── frontend/        # React frontend
│   └── src/
├── backend/         # Node.js backend
│   └── controllers/
│   └── models/
│   └── routes/
│   └── middleware/
└── README.md

🧪 Testing
Basic testing using Jest + React Testing Library (frontend)

Postman collections available for backend API testing

<br/>
🧑‍💻 Contributing
Contributions are welcome! Here's how you can help:

Fork the repository

Create your feature branch (git checkout -b feature/YourFeature)

Commit your changes (git commit -m 'Add your message here')

Push to the branch (git push origin feature/YourFeature)

Open a Pull Request
<br/>

📃 License
This project is licensed under the MIT License.
<br/>
🙏 Acknowledgements
Zerodha for the original inspiration

Open source APIs used for demo purposes
<br/>

UI inspirations from Kite (Zerodha)

🔗 Demo: [https://zerodha-frontend-uppa.vercel.app/] <br/>
	 [https://zerodha-clone-dashboard-nu.vercel.app/] <br>
📧 Contact: prakashtare181@gmail.com

