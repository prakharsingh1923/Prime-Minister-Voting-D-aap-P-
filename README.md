# Decentralized Voting Application (DApp)

A secure, transparent, and tamper-proof voting platform built on blockchain technology using Next.js, React, Solidity, and Hardhat.

## 🚀 Features

- **Blockchain-Powered Voting**: Ensures data immutability and transparency.
- **Smart Contracts**: Securely manage voting processes and results.
- **Responsive Frontend**: Built with Next.js and React for an interactive user experience.
- **Integration with Ethereum**: Seamless interaction with the Ethereum blockchain using Ethers.js or Web3.js.
- **Testing and Deployment**: Comprehensive testing and deployment with Hardhat.

---

## 📸 Screenshots

### Home Page
![Home Page](.//public//screenshots//Screenshot_2024-12-10_164300.png)

### Voter Registration Page
![Voter Registration Page](.//public//screenshots//Screenshot%202024-12-10%20165229.png)

### Candidate Registration Page
![Candidate Registration Page](.//public//screenshots//Screenshot%202024-12-10%20165108.png)

### Election Creation Page
![Election Creation Page](.//public//screenshots//Screenshot%202024-12-10%20180942.png)

### Registered Candidates Page
![Registered Candidates Page](.//public//screenshots//Screenshot%202024-12-10%20165317.png)

## 📂 Project Structure

```
├── app               # Next.js app directory
│   ├── layout.js     # Root layout
│   └── page.js       # Home page
├── Components        # React components
├── contracts         # Solidity smart contracts
├── public            # Static assets (e.g., favicon)
├── scripts           # Deployment scripts for smart contracts
├── styles            # CSS and styling files
├── utils/context     # Utility functions and React context
├── hardhat.config.js # Hardhat configuration file
└── package.json      # Dependencies and project scripts
```

---

## 🛠️ Technologies Used

### Frontend
- **Next.js**: Server-side rendering and file-based routing.
- **React**: Component-based UI development.
- **CSS/SCSS**: Styling for the application.

### Blockchain
- **Solidity**: Smart contract programming language.
- **Hardhat**: Ethereum development environment for testing and deployment.
- **Ethers.js/Web3.js**: Blockchain interaction library.

### Others
- **Node.js**: Backend runtime.
- **npm**: Dependency management.

---

## 📝 Setup and Installation
### Setup :

Get PInata API key from [here](https://pinata.cloud/)

**PInata IPFS**

```https://www.pinata.cloud/
 GET: API_KEY
 GET: SECRECT_KEY
```

**PInata IPFS IMAGE UPLOAD**

```https://www.pinata.cloud/
 headers: {
            pinata_api_key: `YOUR_API_KEY`,
            pinata_secret_api_key: `YOUR_SECRECT_KEY`,
            "Content-Type": "multipart/form-data",
          },
```

**PInata IPFS JSON DATA UPLOAD**

```https://www.pinata.cloud/
 headers: {
            pinata_api_key: `YOUR_API_KEY`,
            pinata_secret_api_key: `YOUR_SECRECT_KEY`,
             "Content-Type": "application/json",
          },
```

**Clone the Repository**:
   ```bash
   git clone https://github.com/Parth-GECA-IT/E-Voting-D-app.git
   cd voting-dapp
   ```
### Installation :

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Compile Smart Contracts**:
   ```bash
   npx hardhat compile
   ```

3. **Deploy Contracts**:
   - For local development:
     ```bash
     npx hardhat node
     npx hardhat run scripts/deploy.js --network localhost
     ```
   - For Polygon Amoy testnet deployment:
     ```bash
     npx hardhat run scripts/deploy.js --network polygon_amoy
     ```
   Note: Use `localhost` for testing and development purposes. Use `polygon_amoy` when you want to deploy to the Polygon Amoy testnet for staging or production.

4. **Run the Development Server**:
   ```bash
   npm run dev
   ```

5. **Access the Application**:
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🧪 Testing

Run tests for smart contracts using Hardhat:
```bash
npx hardhat test
```

---

<!-- ## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

--- -->

## 👥 Contributors

- **Prakhar Singh** - [LinkedIn](https://www.linkedin.com/in/prakhar-singh-1b9614185/) | [GitHub](https://github.com/prakharsingh1923/Prime-Minister-Voting-D-aap-P-)
- **Parth Armarkar** - [LinkedIn](http://www.linkedin.com/in/parth-armarkar-052551289) | [GitHub](https://github.com/Parth-GECA-IT)
- **Karan Gawande** - [LinkedIn](linkedin.com/in/karan-gawande-64aa3b231) | [GitHub](https://github.com)
- **Mihir Mudholkar** - [LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)

Feel free to fork, contribute, or report issues!
