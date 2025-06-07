# DeFiScope

DeFiScope aims to make blockchain data easy to understand and use, so more people can make smarter decisions. By providing clear, real-time insights into transactions, DeFi activity, and user behavior, we help users, developers, and investors truly understand what’s happening on the Scroll blockchain. Our goal is to turn complex data into simple, useful dashboards anyone can use. With better tools for analysis, more people can participate in the ecosystem, build better products, and invest with confidence. DeFiScope will empower the next wave of builders and users with the knowledge they need to make an impact.

![15cb47dc-43de-11f0-b0f5-0242ac110008_0](https://github.com/user-attachments/assets/7bd02240-9a34-4659-8686-f6df03d1b9e6)

## About Me

I'm Metehan Günen, a third-year Computer Engineering student at Istinye University. I got interested in Web3 a few months ago and recently applied to the Rise In Full Stack Bootcamp to deepen my skills. I’ve worked on projects in various programming languages and love exploring new tech. Outside of coding, I enjoy gaming, cinema, playing instruments, and of course—coffee.

## Description

DeFiScope is a blockchain analytics platform built on Scroll, designed to go beyond basic explorers like Lumenscan. It offers real-time transaction monitoring, detailed DeFi protocol insights, and user behavior analytics across the Scroll ecosystem. Users can track on-chain activity live, analyze liquidity flows, protocol usage, and wallet interactions, all in one place. With custom dashboard creation, users can tailor views to their specific needs—whether for research, compliance, or investment decisions. DeFiScope turns raw blockchain data into clear, actionable intelligence.

## Roadmap / Future Plans

### Phase 1:
Smart contract development for recording protocol and user interactions

Basic dashboard showing real-time transactions

### Phase 2:

Build indexer to aggregate DeFi and wallet data
Customizable frontend dashboard with filterable metrics

### Phase 3:
Add support for multiple Scroll-based DeFi protocols

Launch beta version and gather user feedback

### Phase 4:
Improve UI/UX, add wallet-based user profiles

Deploy to mainnet with complete analytics suite

### Phase 5:
Optional: Premium features, alert system, zk-data privacy, or mobile dashboard

## The tech i use

- Frameworks: Hardhat (smart contract dev/test), Ethers.js
- Backend/Indexer: Node.js, Express.js, PostgreSQL
- Frontend: React.js, Tailwind CSS
- Data Handling: Web3.js / Ethers.js event listeners
- Deployment: Vercel (frontend), Scroll Mainnet (contracts), Railway (backend/API)

## Smart Contract Address
CDI7AI3K6Y6F5LL5AFVEQBZRGTK4PBYN7JSVSJLKZ3YO27UMUD2F3DN3

## Setup Environment

### 1. Clone the Repository

```bash
git clone https://github.com/Metrohan/DeFiScope.git
cd DeFiScope
```

### 2. Install Dependencies

#### Backend / Smart Contracts
```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

### 3. Configure Environment Variables

Create .env files in both backend/ and frontend/ directories.
Example .env for Backend

```bash
RPC_URL=https://scroll-mainnet.rpc-url
PRIVATE_KEY=your_wallet_private_key
DB_URL=postgres://user:pass@localhost:5432/defiscope
```

Example .env for Frontend

```bash
REACT_APP_BACKEND_URL=http://localhost:5000
REACT_APP_CHAIN_ID=534352  # Scroll Mainnet Chain ID
```

### 4. Run Smart Contracts Locally (Optional)

```bash
cd backend
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
```

### 5. Start Backend Server

```bash
npm run dev
```

### 6. Start Frontend

```bash
cd ../frontend
npm start
```


