
Blockchain-Powered Freelance Platform
Overview
Welcome to our blockchain-powered freelance platform! Our platform directly links freelancers with clients, removing intermediaries while guaranteeing secure, transparent transactions. It also enables equitable dispute resolution and provides a seamless chat interface between freelancers and clients. Users can post multiple jobs and manage all their freelance projects in one place.

Features:
Decentralized Platform
Direct Linkage: Connects freelancers and clients directly, eliminating the need for intermediaries and reducing associated costs.
Secure Transactions: Utilizes blockchain technology to ensure all transactions are secure and transparent.
Transparency: All transactions and agreements are recorded on the blockchain, providing a clear and immutable record.
Job Posting and Management
Multiple Job Posting: Clients can post multiple jobs, and freelancers can apply for these jobs directly through the platform.
Integrated Chat: Real-time chat functionality between freelancers and clients, facilitating clear and direct communication.
Dispute Resolution
Equitable Resolution: Disputes between freelancers and clients are handled through a fair and transparent resolution process.
Blockchain Record: Dispute resolutions and agreements are recorded on the blockchain, ensuring all parties have access to an unbiased record.
Security
Data Privacy: All user data is encrypted and stored securely, with blockchain ensuring data integrity.
Payment Security: Payments are handled through smart contracts, ensuring funds are released only when both parties meet agreed-upon milestones.

Note:
1.Update the .env file with the following details.

 REACT_APP_COMET_CHAT_APP_ID=<CometChat_APP_ID>
 REACT_APP_COMET_CHAT_AUTH_KEY=<Comet_Chat_AUTH_KEY>
 REACT_APP_COMET_CHAT_REGION=<CometChat_REGION>
 REACT_APP_RPC_URL=<http://127.0.0.1:8545>
2.Run the app using the following commands.

npx install
npx hardhat node
npx hardhat run scripts/deploy.js
