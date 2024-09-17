# NFT Marketplace Frontend

This is the frontend application for the NFT Marketplace, designed to provide users with a seamless and interactive experience in minting, trading, and managing NFTs. The frontend is built using modern web technologies to ensure high performance, responsiveness, and scalability.

## 🚀 Features

- **Mint NFTs**: Users can easily mint their own NFTs and list them for sale.
- **Buy and Sell NFTs**: An intuitive marketplace for users to buy and sell NFTs.
- **Wallet Integration**: Securely connect and manage wallets (MetaMask, etc.) for transactions.
- **Real-time Updates**: Leverage WebSocket for real-time updates on listings, trades, and offers.
- **Search and Filter**: Advanced search and filtering options to quickly find desired NFTs.
- **Responsive Design**: Fully responsive layout that works across all devices.

## 🛠️ Technologies Used

- **Next.js**: A powerful React framework for building server-rendered applications.
- **Tailwind CSS**: Utility-first CSS framework to style the application quickly and efficiently.
- **Redux**: State management library for handling application-wide state and data flow.
- **Socket.IO**: Real-time communication for instant updates on trades, offers, and listings.
- **Ethers.js**: A library for interacting with the Ethereum blockchain and wallets.
- **Axios**: Promise-based HTTP client for handling API requests.
- **Docker**: Containerization for ensuring consistent environments across development, testing, and production.

## 📂 Project Structure

```bash
frontend/
│
├── public/            # Static assets (images, fonts, etc.)
├── src/
│   ├── components/    # Reusable UI components
│   ├── pages/         # Application pages
│   ├── redux/         # Redux store and slices
│   ├── services/      # API and blockchain service integrations
│   ├── styles/        # Global and page-specific styles
│   └── utils/         # Utility functions
├── .env               # Environment variables (API keys, endpoints, etc.)
├── next.config.js     # Next.js configuration
└── Dockerfile         # Dockerfile for frontend application
... ... ... ... ... ... Todo
```
## 📦 Installation
1.	Clone the repository:
```bash
git clone https://github.com/PhiTranViet/nft-marketplace-frontend-base.git
cd nft-marketplace-frontend
```
2.	Install dependencies:
```bash
npm install
```
3.	Set up environment variables:
```bash
Create a .env file in the root of the project and configure the following variables:
NEXT_PUBLIC_API_URL=http://localhost:3000/api
NEXT_PUBLIC_KAFKA_BROKER_URL=kafka://localhost:9092
NEXT_PUBLIC_SOCKET_URL=http://localhost:3000
```
4.	Start the development server:
```bash
npm run dev
```
5.	Build the application for production:
```bash
npm run build
```

## 📊 Key Features

	•	Blockchain Integration: The app interacts with smart contracts on the Ethereum network using Ethers.js to manage NFTs and payments.
	•	WebSocket Integration: Real-time updates for trades and offers using Socket.IO.
	•	Advanced Search: Search NFTs by name, creator, price range, and more.
	•	Responsive UI: A mobile-first, responsive design to ensure the best user experience on all devices.

## 🤝 Contribution

We welcome contributions from the community! Please follow the guidelines below:

	1.	Fork the repository.
	2.	Create a new feature branch (git checkout -b feature/new-feature).
	3.	Commit your changes (git commit -m 'Add some feature').
	4.	Push to the branch (git push origin feature/new-feature).
	5.	Open a Pull Request.