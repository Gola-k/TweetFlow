# Crypto Airdrop Token Project

![token](https://github.com/user-attachments/assets/2ae3da5c-60e5-4065-b60b-ea36d9013ccd)![airdrop](https://github.com/user-attachments/assets/c50e9569-d5f9-436b-871d-648d6c72161e)



| **Home Page** | **Admin Panel** |
|---------------|-----------------|
| ![Home1](https://github.com/user-attachments/assets/5a5f8ca9-97ee-495a-a128-7110dc715b6c) <br> *Figure 1: Home Screen - The landing page of the airdrop token project.* | ![Admin1](https://github.com/user-attachments/assets/8b068838-1c0a-4d82-a795-a560afa2d48f) <br> *Figure 6: Admin Panel - Admin dashboard to manage airdrop campaigns.* |
| ![Home2](https://github.com/user-attachments/assets/b2b28e02-2b35-4c53-80e6-38fd39a2bf80) <br> *Figure 2: User Interface - A closer look at the home page interface.* | ![Admin2](https://github.com/user-attachments/assets/2124f031-c28a-4ebe-8128-77a86072e847) <br> *Figure 7: Admin Panel - Viewing and managing user data and transactions.* |
| ![Home3](https://github.com/user-attachments/assets/0f283e4c-5f68-456b-bf8d-4f117507b299) <br> *Figure 3: Token Details - Displaying information about the deployed token.* |  |
| ![Home4](https://github.com/user-attachments/assets/a714f2c9-f240-45dc-8cf9-ab6a54728046) <br> *Figure 4: User Interaction - Participants interacting with the token and airdrop sections.* |  |
| ![Home5](https://github.com/user-attachments/assets/c520592c-2ad3-403f-913d-95afb24a99b5) <br> *Figure 5: Claim Page - Users claiming tokens after successful validation.* |  |

---

| **Ask Questions** | **Airdrop Process** |
|-------------------|---------------------|
| ![Ask](https://github.com/user-attachments/assets/86dff9b9-87d4-4bef-acd2-7eb7cf04d0ab) <br> *Figure 8: Ask Questions - Participants asking questions related to the airdrop.* | ![Airdrop1](https://github.com/user-attachments/assets/ec8217e5-71b2-4aa7-a91e-1c412c361e4d) <br> *Figure 9: Airdrop Claim - The process for claiming the airdrop through the website.* |
|                   | ![Airdrop2](https://github.com/user-attachments/assets/3df323bc-74de-41bd-96ba-2ae10388c32d) <br> *Figure 10: Airdrop Details - Details about the airdrop that users need to fill out.* |
|                   | ![Airdrop3](https://github.com/user-attachments/assets/26bee014-59f0-4bf3-aeb6-61171530d07b) <br> *Figure 11: Airdrop Confirmation - Confirmation page after the claim has been successfully made.* |

---

## Overview

This project demonstrates how to build and deploy a crypto airdrop token on the **CrossFi Testnet** using the token `CTKN` (CrossToken). It provides a complete implementation, including tokenomics, smart contract deployment, airdrop distribution mechanisms, and a robust admin panel for managing the process. Whether you're a beginner or an experienced developer, this guide will help you set up and manage a successful airdrop campaign.

---

### Features

- **Token Deployment:** 
  - Deploy any ERC-20 compatible token, such as `CTKN`, on the CrossFi Testnet.
  - Customize and configure token parameters during deployment.

- **Universal Airdrop Distribution:** 
  - Airdrop any ERC-20 token, including `CTKN`, to eligible participants.
  - Define specific criteria for token distribution, such as social media activity and email verification.

- **Admin Panel Functionalities:**
  - Update token details such as the token address and airdrop claim settings.
  - Monitor and verify individual transaction details.
  - Manage funds with options to:
    - Withdraw XFI tokens used as gas or fees.
    - Withdraw the deployed tokens in bulk.
    - Transfer all tokens collectively.

- **User Claim Process:**
  - Participants must submit the following details on the **Airdrop Page**:
    - Social media activity links:
      - Twitter Post ID.
      - Instagram and LinkedIn post URLs, with the required message from the website in their posts.
    - Personal details:
      - Name and email address.
  - Once validated, users can claim the airdrop directly from the website.

- **Transaction Insights:**
  - Access detailed logs of every single transaction processed through the platform.

- **Seamless Integration:**
  - Fully integrated with the CrossFi Testnet for deployment and testing.
  - Built-in mechanisms for validating user activity and ensuring fair distribution.

---

### Prerequisites

- **Node.js & NPM:**

  - Node.js: v18.12.1
  - NPM: 8.19.2
  - Download: [Node.js Official Website](https://nodejs.org/en/download)

- **Visual Studio Code:**

  - Recommended IDE for development.
  - Download: [Visual Studio Code Official Website](https://code.visualstudio.com/download)

- **RemixID:**

  - A browser-based IDE for Solidity development.
  - Visit: [Remix Official Website](https://remix-project.org)

- **CrossFi Testnet:**

  - Blockchain testnet for deploying smart contracts.
  - Explore: [CrossFi Explorer](#) (Replace with the CrossFi Testnet Explorer URL)

- **Faucets:**
  - Free test funds for deploying contracts.
  - Visit: [CrossFi Testnet Faucets](#) (Replace with the CrossFi Faucet URL)

---

### Getting Started

1. **Clone the Project**

   - Clone the complete project repository:
     ```bash
     git clone <repository-url>
     cd <repository-directory>
     ```

2. **Install Dependencies**

   - Navigate to the project directory and install dependencies:
     ```bash
     npm install
     ```

3. **Run the Project**

   - Start the project locally:
     ```bash
     npm run start
     ```

4. **Deploy Smart Contracts**
   - Use RemixID or Hardhat to deploy your contract to the CrossFi Testnet.

---

### Project Structure

- **`contracts/`**
  - Contains the Solidity smart contract for the `CTKN` token and the airdrop mechanism.
- **`scripts/`**
  - Deployment scripts for automating the deployment process.
- **`README.md`**
  - Instructions to set up, run, and deploy the project.

---

### Deploying Your Token on the CrossFi Testnet

1. **Obtain Test Tokens**

   - Use the CrossFi Faucet to acquire free test `CTKN` tokens for deployment.

2. **Deploy Using RemixID**

   - Navigate to [Remix](https://remix-project.org), compile your smart contract, and deploy it to the CrossFi Testnet.

3. **Verify on Explorer**
   - Verify your deployed contract using the CrossFi Testnet Explorer.

---

### Project Links

- **Project Name:** TweetFlow
- **Deploy:** [TweetFlow Live Application](https://tweet-flow.vercel.app/)
- **GitHub:** [TweetFlow GitHub Repository](https://github.com/Gola-k/TweetFlow)

---

### Additional Resources

- **Test Faucets:** Obtain test `CTKN` tokens for deployment and testing.
- **Blockchain Explorer:** Verify transactions and contracts on the CrossFi Testnet.
- **Developer Tools:** Utilize Hardhat or Remix for development and deployment.

---

### Notes

This project is designed for the CrossFi Testnet. To deploy on the mainnet, ensure you have appropriate XFI funds and permissions.
