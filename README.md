# Blockchain-Based-Decentralized-Cloud-Storage-with-Reliable-Deduplication-and-Storage-Balancing
A secure and efficient cloud storage system built on blockchain technology to ensure data integrity, decentralization, and optimized resource utilization. This project integrates deduplication, encryption, and blockchain-based validation to provide a reliable and balanced cloud storage solution.

Features 🔒 Blockchain Security – Ensures immutability and trust in data transactions. 📦 Data Deduplication – Eliminates duplicate data blocks to save storage space. ⚖️ Storage Balancing – Distributes files evenly across network nodes to prevent overload. 🧠 Smart Verification – Uses blockchain to verify data ownership and authenticity. 🧰 User Dashboard – Interface for uploading, downloading, and managing files.

⚙️ Technologies Used Python – Core backend logic Flask / Django – For web-based interface (if included) Blockchain (Custom or Ethereum Testnet) – To manage data transactions IPFS / Local Node System – For decentralized file storage Cryptography Libraries – For encryption and decryption of data SQLite / MySQL – To maintain metadata and node records

🧠 System Workflow

User Uploads a File The file is encrypted and hashed. The system checks for duplicate data blocks (deduplication).

Blockchain Verification File hashes and metadata are stored as transactions on the blockchain. Ensures tamper-proof record keeping.

Decentralized Storage Data is split and distributed across storage nodes. Balancing logic ensures even distribution.

Data Retrieval When requested, encrypted blocks are fetched and decrypted to restore the file.
